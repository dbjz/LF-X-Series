LayerFused X-series printers Klipper Configuration files.

The configurations here are setup to be used with the LayerFused X-Series printers.  They include the X201, X301, X401, and X501.

If you plan to use these config files, please read through the configuration file for which board you choose.  There are comment lines that describe what you should/need to change depending on which printer you are using. All of the config files are currently setup for Sensorless Homing with TMC2209s for all drivers, with 1.8 degree steppers and a 2mm lead leadscrew (single start) as well as 2GT 20 tooth pulleys. LayerFused nor I are responsible for any damage that may be caused by using these configuration files. PLEASE verify your settings and if you are unsure please reach out and or research the klipper documentation. https://www.klipper3d.org/Overview.html 

Also be sure to grab the client.cfg and LF_macros.cfg and add those as well. These macros have been configured and tested to "Work" with whichever configuration you are using.  Simply put the LF_macros.cfg in the proper location and be sure to [include LF_macros.cfg] in the main printer.cfg and the macros will present themselves in the macro section of Fluidd or MainSail. 

If you have questions or need assistance you can reach out on the MakersMashup Discord Server. https://discord.gg/gZ3rgq6E
