# RISC-V-Nixie
Nixie Clock using the GD32VF103 RISC-V microcontroller by GigaDevices and the swiss precise RTC RV-3032-C7 by Micro Crystal AG.

For tubes, IN-8 tubes will be used as they can be mounted into sockets. Since the original, soviet sockets are quite bulky, individual pin sockets will be mounted instead.

## Status
The current status of the project, which steps are done or still need to be do. Currently only revision A is in testing, a revision that has some slight imperfections that will be tackled in the next revision. Since parts have been already delivered, revision A will be used to extensively test the PCB, in particular the dimming of the tubes and the high-voltage step-up circuitery.
Task | Comments
------------ | -------------
Initial Schematic | :heavy_check_mark:
Initial Layout & BOM | :heavy_check_mark:
Assembling PCB | :heavy_check_mark:
Power-ON Test, Voltage levels | :heavy_check_mark:
Initialising / Testing the MCU | :heavy_check_mark:
Writing basic I/O functions | In Progress... :grey_question:
Writing the clock programm | -

## Images
![Lower assembled PCB](https://github.com/gfcwfzkm/RISC-V-Nixie/blob/main/images/IMG_20210522_102124.jpg)
![Upper assembled PCB](https://github.com/gfcwfzkm/RISC-V-Nixie/blob/main/images/IMG_20210522_102314.jpg)
![PCBs + Tubes assembled](https://github.com/gfcwfzkm/RISC-V-Nixie/blob/main/images/IMG_20210522_104633.jpg)
![Conformal coating TOP](https://github.com/gfcwfzkm/RISC-V-Nixie/blob/main/images/IMG_20210526_070233.jpg)
![Conformal coating BOTTOM](https://github.com/gfcwfzkm/RISC-V-Nixie/blob/main/images/IMG_20210526_070308.jpg)
![Spacing between high-voltage pins of the upper PCB and the lower PCB's buttons / transformer](https://github.com/gfcwfzkm/RISC-V-Nixie/blob/main/images/IMG_20210526_070404.jpg)
![Initial Power test, no magic smoke & all voltages within specs!](https://github.com/gfcwfzkm/RISC-V-Nixie/blob/main/images/IMG_20210526_075324.jpg)
