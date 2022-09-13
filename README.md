## Description

An ESP-IDF library for the DHT series of low-cost temperature/humidity sensors.

You can find DHT tutorials [here](https://learn.adafruit.com/dht).

# Requirements
 * Library built as c++. In case of ESP-IDF examples (written in pure C) you need to rename main.c into main.cpp and add <code>extern "C"</code> before app_main() function

        /**
         *  @file main.cpp
         *  
         */
        
        #include "DHT.h"
    
        extern "C" void app_main() {
          DHT dht( GPIO_NUM_4, DHT_TYPE_AM2301, 0 );
        }

# Dependencies
 * Espressif ESP-IDF framework

# Contributing
Contributions are welcome!  Not only you’ll encourage the development of the library, but you’ll also learn how to best use the library and probably some C++ too

MIT license, check license.txt for more information
All text above must be included in any redistribution

#how to install
