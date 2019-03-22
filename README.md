This repository contains micropython firmware from various esp32 builds - some I've done myself (esp-now) and others I've just found on github.
Here is a list with description:
Directory <esp-now>
nowfirmware.bin                             Firmware I built from the nickzoic/micropython-esp32/esp32-espnow repo ***** use this *****


Directory <MicroPython_LoBo_esp32_all       Firmware I obtained which is the "loboris" micropython repository and it has a number of nice
                                              "goodies" in the directory there are flash scripts and a sample command to flash manually.
                                              
                                              
Directory <MicroPython_LoBo_esp32_psram_all Firmware I obtained which is the "loboris" mp repository for an ESP32 with psram support.  It will
                                              work if you don't have psram, but you'll get an error message on boot-up.
                                              
Directory <vanilla mp binaries>             Firmware I found online which contains supported releases of mp for the ESP8266 boards.
combined.bin                                I believe this is a build from the nickzoic/micropython-esp32 repo that does not contains
                                              esp-now support.  Don't know what it has more than the standard, supported mp for esp32 releases.
esp32-20190214-v1.10-98-g4daee3170.bin      This is the esp32 build to test my ttgo LoRa boards.  Works great but no esp-now support
                                              
                                              
Directory <built for me>                    Firmware I had built by an online service (for free).  These are for the esp8266 boards.
nodemcu-master-12-modules-2018-12-02-23-26-21-float.bin   
nodemcu-master-12-modules-2018-12-02-23-26-21-integer.bin


Directory <ESP8266Flasher.exe>              A utility to flash esp8266 boards.  Google it and get some doc.  
ESP8266Flasher.exe