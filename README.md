# MyQtTryouts
* Echo Server : Simple TCP/IP socker programing tryouts on Qt 
* QtConsole : Simple console application tryouts on Qt 
* QtQuick : Qml application theme testing 
* QtCustomControl : Custom control development testing
* #### Vfp : Qt widget application which I try to figure out 
    - `How to impliment MVVM approach in c++ and Qt`
    - `How to json file parsing works in Qt libraries`
    - `How to resource management works in Qt Application`
    - `Theme and styling etc. testing`


# Requirements ...

* You should have latest version of cmake 
* VsCode will be a plus but cmake already handle the build envoirement generation
* If you want to use debug helper make sure qt5.natvis file should be defined in `launch.json` file like ..

```
    "configurations": [        
        {
            "name": "(Windows) Launch",
            "type": "cppvsdbg",
            "request": "launch",
            "program": "${workspaceFolder}/build/ProjectName.exe",
            "args": [],
            "stopAtEntry": false,            
            "cwd": "${workspaceFolder}",
            "symbolSearchPath": "${workspaceFolder}/build/",            
            "environment": [],
            "externalConsole": false,
            "visualizerFile": "${workspaceFolder}/../qt5.natvis"
        }
    ]

```

* If you wanna use it with vscode, make sure you've installed cmake extension
* The source file and folder should be updated wrt. cmake build output inside of the build folder compile_commands.json file




