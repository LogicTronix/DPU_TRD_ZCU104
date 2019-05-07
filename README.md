# DPU_TRD_ZCU104

----May 3, 2019----
----www.LogicTronix.com----
----email: info@logictronix.com----
----Demo Test Project Version: v3.0----


This is DNNDK DPU TRD for the ZCU104,we have build the "Demo Test" for the ZCU104. 
We followed the PG338 DPU TRD of ZCU102 to build the DPU TRD for the ZCU104 FPGA. 
We have tested and verified the result of the new DPU TRD on ZCU104. 
In this TRD we have Resnet50 of Convolutional Neural Network for teh application of image classification. 
For more details, please visit: PG338 and DNNDK reference can also be found at UF1327, Xilinx.

For more details, please visit our complete [ste-by-step] tutorial: https://logictronix.com/our-resources/machine-learning-with-fpga/dpu-trd-for-zcu104/ .

There is also an Xilinx Forum thread where this project "DPU TRD for ZCU104" was discussed: https://forums.xilinx.com/t5/Deephi-DNNDK/DPU-TRD-for-ZCU104/td-p/958695


Here is the "Demo Test" download link of google drive [141MB]: https://drive.google.com/open?id=1AyxDg1TRwMIcIaAdqrQdf2cvw4Nj0uen


===RUN the Application on your ZCU104===
================Steps===================
1. Download above "Demo Test", extract it, copy all the contents of "ZCU104_dpu_trd_test" folder into SD Card, now eject the card and put on ZCU104.

2. Make ready the ZCU104 as the DNNDK User Guide, UG1327[Page 18] of Xilinx.
3. power cycle [turn on] the FPGA board
4. open the serial ternimal program and connect with ZCU104 at 115200 baud rate
5. change directory to "home"
6. run "./resnet50.elf"
7. Now you must see the result on the terminal.


For connecting the ZCU104 in ethernet interface, please follow "DNNDK User Guide UG1327, Page 24"
=========================================

If you get any queries then write us at: info@logictronix.com
