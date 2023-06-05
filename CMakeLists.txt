cmake_minimum_required(VERSION 3.16)

idf_component_register(SRCS "Adafruit_ST77xx.cpp" "Adafruit_ST7735.cpp" "Adafruit_ST7789.cpp" 
                        INCLUDE_DIRS "."
                        REQUIRES arduino Adafruit_BusIO Adafruit-GFX-Library)

project(Adafruit-ST7735-Library)