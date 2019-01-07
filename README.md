# gr-Merapi
Author: Handiko Gesang Anugrah Sejati, S.T.

This project is about an SDR based decoder which run in GNU Radio platform to receive telemetry transmission from Balerante Station (Mt. Merapi). This transmission contains 6 data fields (horizontal & vertical vibration, temperature, humidity, rain measurement, and sulphuric compound gas. The data protocol was made by Mr. Angga and sponsored by PT. Datto Asia Technology and Sensor and Sistem Telecontrol Lab, Universitas Gadjah Mada.

# Dependencies
* GNU Radio V.3.7.10 and Up
* Boost
* SWIG
* CMAKE
* GR-OSMOSDR
* RTL-SDR

* `sudo apt-get update && sudo apt-get upgrade -y`
* `sudo apt-get install libboost-all-dev swig cmake git gcc -y`
* `sudo apt-get install gnuradio gr-osmosdr rtl-sdr`

# Installation
* `git clone https://github.com/handiko/gr-Merapi.git`
* `cd gr-Merapi`
* `mkdir build`
* `cd build`
* `cmake ../ -DCMAKE_INSTALL_PREFIX=/usr`
        OR
* `cmake ../ -DCMAKE_INSTALL_PREFIX=/usr/local`
        (depends on your system)
* `make`
* `sudo make install`
* `sudo ldconfig`