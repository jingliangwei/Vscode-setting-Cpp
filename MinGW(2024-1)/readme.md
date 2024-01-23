2024年1月重新安装配置了vscode环境，这次仅使用MinGW编译器，并将这次的配置文件备份于此。
关于这些备份文件需做几点说明如下：
1. 如有编译器安装路径和源文件路径的变动，需做如下更改：

（1）c_cpp_properties.json中"compilerPath": "C:/mingw64/bin/g++.exe"为编译器安装路径

（2）launch.json中"program": "E:\\vs code\\2024-1-15\\.vscode\\exe\\a.exe"为编译生成的可执行文件（.exe）存放路径

（3）launch.json中"miDebuggerPath": "C:\\mingw64\\bin\\gdb.exe"为编译器安装路径

（4）tasks.json中"command": "C:\\mingw64\\bin\\g++.exe"为编译器安装路径

（5）tasks.json 中"args": [...],中的"E:\\vs code\\2024-1-15\\.vscode\\exe\\a.exe"为编译生成的可执行文件（.exe）存放路径

2. 这些配置文件将编译源文件生成的可执行文件（.exe）统一存放于\.vscode\exe文件夹中，以保持主工作区只有源文件，干净利落。
3. 将可执行文件（.exe）统一命名为“a.exe”可以解决原来源文件使用中文命名时无法编译的问题。            