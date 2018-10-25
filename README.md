# Eclipse-Quectel-BC66
Basic settings for Eclipse + Quectel BC66 IoT NB
This Version 1.0.0

* Use Eclipse from OpenCPU M66 (is ready for BC66)
* Use Compiler from OpenCPU BC66 (gcc 4.8.3 for cortex-m4 + maths)
* Firmware, USB Drivers, Quectel IoT Flash Tool https://app.box.com/s/3wrkh1yzn09yuyb5f8v5vllmlir0571s

Get from archive folder (it is Eclipse Workspace) OpenCPU_BC66

Copy/Paste from OpenCPU_BC66\Hello\make 
* cs-make.exe
* cs-rm.exe
to YOUR_PATH_TO\COMPILER\4.8.3\bin
        
This Project - Properties:
* C/C++ Build - Environment - edit PATH = YOUR_PATH_TO\COMPILER\4.8.3\bin 
* C/C++ Build - Settings - Tab Toolchains: edit Global path: YOUR_PATH_TO\COMPILER\4.8.3\bin   
        
*note: BC66 Modules NB used FP Hard fpv4-sp-d16* 
    
APPLY, OK  (is ready for compile)     
    
*This Project - Properties - C/C++ Build - plus your favorite settings settings*
   
    
Clean / Compile  

Make Target - BUILD

Upload to module
