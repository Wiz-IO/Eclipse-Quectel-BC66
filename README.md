# Eclipse-Quectel-BC66
Basic settings for Eclipse + Quectel BC66 IoT NB
Version 1.0.0


Use Eclipse from OpenCPU M66 (is ready for BC66)

Use Compiler from OpenCPU BC66 (gcc 4.8.3 for cortex-m4 + maths)

*note: BC66 Modules NB used FP Hard fpv4-sp-d16*

Copy / Paste from THIS_PROJECT\make: 
* cs-make.exe
* cs-rm.exe
to YOUR_PATH_TO\COMPILER\4.8.3\bin
        
This Project - Properties:
* C/C++ Build - Environment - edit PATH = YOUR_PATH_TO\COMPILER\4.8.3\bin 
* C/C++ Build - Settings - Tab Toolchains:   
        * edit Global path: YOUR_PATH_TO\COMPILER\4.8.3\bin   
    
APPLY, OK  (is ready for compile)     
    
*This Project - Properties - C/C++ Build - plus your favorite settings settings... *
   
    
Clean / Compile  

Make Target - BUILD

Upload...
