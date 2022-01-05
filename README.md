<!--Start the project - Developement with C++ -->
<!--Copyright: Md. Manjurul Haque -->
<!--Position: Software Engineer -->
<!--Company: Frontier Semiconductor Bangladesh Ltd. -->
# Development_with_C-plus-plus
We will learn C++ programming from Scratch to Advance. We will go through the procedure of basic C++ programming to Desktop Application Development. That's why we try to do our coding in VS (Visual Studio).  
Let's start!!!!!!

<!--Setup Environment -->
## Chapter 1 Setup Visual Studio

<!--Visual Studio Download links -->
### 1.1 Download Visual Studio

Download visual studio from the links as you require:
https://visualstudio.microsoft.com/vs/older-downloads/  
In this repository, I personally will use vs2019 version. 

<!--Installation of Visual Studio -->
### 1.2 Install Visual Studio

- Installation is simple like the other SW. Press the install button. It automatically download it's require file from the internet. Maybe it will download > 1.5GB.  
- Maybe take a restart to the PC after installation complete.  

<!--Create new project -->
## Chapter 2 VS Projects

<!--Description of different type of project -->
### 2.1 Different Type of Project

After open the VS, maybe you will see 4 options in the right side(VS 2019). Pressing the **Create a new project** button, you will look a different window with different project type. Different project type use for different task.   
Let's discuss the most usable project type-   
<!--Some Project Description -->
<!--Empty Project -->
#### 2.1.1 Empty Project
- There is no starting file.
- No application frameworks.
- That have no projects.
- This might be preferable in cases where you want to construct your solution and projects from scratch.

<!--Console Application -->
#### 2.1.2 Console App
- A computer program designed to be used via a text-only computer interface.
- No graphical user interface means no pointing device or no visualize interface.
- CMD in windows is a best example.

<!--Make File create project -->
#### 2.1.3 CMake Project
Before understand the CMake Project, Let's understand makefile.  
*A makefile is a special file, containing shell commands, that you create and name makefile (or Makefile depending upon the system).* A makefile that works well in one shell may not execute properly in another shell. The makefile contains a list of rules. These rules tell the system what commands you want to be executed. Make (or rather a Makefile) is a buildsystem - it drives the compiler and other build tools to build your code in cross platform.  
- CMake is a generator of buildsystems. It can produce Makefiles.
- CMake is a way to make your project buildsystem-independent as well.
- It builds modern, cross-platform C++ apps that don't depend on  .sln or .vcxproj files.

<!--Windows Desktop Application -->
#### 2.1.4 Windows Desktop Application
We understand from the topic name that it simply able to makes windows desktop application. Basically it ables to create Win32 program. *Win32 program is an executable application (EXE) written in C or C++, using calls to the Win32 API to create a graphical user interface.*  

<!--Microsoft Foundation Class Library Application -->
#### 2.1.5 MFC App
MFC full meaning is microsoft foundation class library. Like the 2.1.4 it also use for create complex desktop application.  
*Microsoft Foundation Class is a class library in C++ that encapsulates certain portions of the Windows API in order to make it easier for programmers to build lightweight code.*

<!--Dynamic Link Library -->
#### 2.1.6 Dynamic Link Library(DLL)
It's a chunk of code that is a completely separate module. A program can request that the dll file be hooked up to, and it can call procedures in the file by name.

<!--Static Library -->
#### 2.1.7 Static Library
A static library or statically-linked library is a set of routines, external functions and variables which are resolved in a caller at compile-time and copied into a target application by a compiler, linker, or binder, producing an object file and a stand-alone executable.

<!--ATL Project -->
#### 2.1.8 ATL Project
Before going to ATL Project let's discuss what is COM.  
*COM is, simply put, a method for sharing binary code across different applications and languages.* Let's know about ATL Project.
ATL Projects provides Active Template Library (ATL) which helps to create small, fast Component Object Model(COM).

### 2.2 Comparison of Projects

#### 2.2.1 Windows API vs MFC
|Topics|Windows API|MFC|
|---|---|---|
|Full Form|Windows API(Application Programming Interface)|MFC(Microsoft Foundation Class Library)|
|Description|Also known as Win32. Must necessary things for creating program in Windows environment.|MFC is a framework encapsulate certain portion of the Windows API to make easier to the programmers.|
|Pros or Cons|1. In Win32 SDK, you need to manually write code for everything. So you have more independency.</br>2. This lead to errors in code also.|1. MFC is composed of functions that are most commonly used by programmers.</br>2.This lead easy to use.|  

#### 2.2.2 COM vs DLL
**COM(component-object-model)**  
The Component Object Model (COM) is a binary standard that defines how objects are created and destroyed and, most importantly, how they interact with each other. As long as applications follow the COM standard, different applications from different sources can communicate with each other across process boundaries. People use COM to make communication with other applications easy.  

Because *COM is a binary standard, it is language independent.* You do not have to use C++ to implement COM. You can use any language that supports tables of function pointers.  

**DLL (dynamic-link library)**  
A file that contains one or more functions that are compiled, linked, and stored separately from the processes that use them. The operating system maps the DLLs into the address space of the calling process when the process is starting, or while it is running. So, *DLL will language, comiler and version dependent.*  

We can say that a COM object can be implemented as a EXE or a DLL.

#### 2.2.3 Static Library vs DLL
|Topics|Static Library|DLL(Dynamic-Library)|
|---|---|---|
|Files|Static libraries gather object files into one|Dynamics exist as separate files outside the executable|
|Files Adding Time|Files link before it becomes and executable binary means in the compilation time|These files do not added on compilation time|
|Compilation|Static library compile again and again|DLL does not need to compile again and again|
|Spped|Faster compiling time and speed|Less speed than static library|
|Memory|It may become large files as it have a copy at executable|Mmeory saving when ruuning multiple library files because a copy of the files create outside the executable file|
|Loading times|Less loading times|Comparetively loading times|

## Chapter 3 New Project in VS
Now we are learning only the basics of C++ programming. So we need a environment where we can give input and also we can see the output. As now we are in basics, so we go with the console application. Becaus it provides the simplest way to give input and see output. Let's start with creating a console application!!!!!  

### 3.1 Create a New Project
1. Open the visual Studio 2019 or any other version you prefer.
2. There are 4 options in the right side of the open window. Press the **Creat a new project** option.
3. Select the **Console App** option.
4. Press the **Next** button in the bottom right side.
5. Give a project name under the project name option.
6. Select the location where you want to save the project.
7. Press the **Create** buuton in the bottom right side.

### 3.2 Understand VS project
After successfully create a project you will see  
- A code editor with some basic code, where you can modify the code as your wish.
- In right side solution explorer show all the files list use in the project. 
- In the bottom section will show you the error and the successful compilation of the code.

## Chapter 4 Run the First Program
Let's delete all the things write in the code editor. We will write the code again by understanding and run the program. Let's understand!!!!

### 4.1 Change the filename
In the **solution explorer** you will see a option **source files**. Expand the options, you see the file with .cpp extesnion. Click on the name and change the name as you wish with keeping the .cpp extension. I chnage the name to **helloworld.cpp**.

### 4.2 Write your first program
Write the code in the code editor - 
```
#include <iostream>
using namespace std;

int main()
{
	cout<<"Hello World!!!"<<endl;
	return 0;
}
```

### 4.3 Run the Program
- Press the **Build** option from the top menu. It will expand and show some more options. Press the **Build Solution** options. Then you will see the compilation result in bottom output window. If the code is successfully compiled then it shows -  
*===Build: 1 succeeded failed, 0 up-to-date 0 skipped ===*
- Then press the **Debug** option from the top menu and select **Start Debugging** or **Start without debugging** options. 
- This opens a console and show you output **Hello World!!!**.

Congratulations!!! You write your first program.

### 4.4 Understand the Program
**#include < iostream >**  
"#" indicates that the following line is a preprocessor directive and should be processed by the preprocessor before compilation by the compiler.  
So, "#include" is a preprocessor directive that tells the preprocessor to include header files in the program.  
"< >" indicate the start and end of the file name to be included.  
"iostream" is a header file that contains functions for input/output operations (cin and cout).  
Now to sum it is must need things to write C++ program.  

*Note: The preprocessors are the directives, which give instructions to the compiler to preprocess the information before actual compilation starts.*  

**using namespace std**  
When we run a program to print something, “using namespace std” says if you find something that is not declared in the current scope go and check std. using namespace std; are used. It is because computer needs to know the code for the cout, cin functionalities and it needs to know which namespace they are defined.  

**main**  
The main function serves as the starting point for program execution.  

**cout**  
Show the output to the console. It is define in the iostream header.  

**return 0**  
Main function has no return, that's the reason it return value 0.  

## Chapter - 5 Basic C++ Programming - 1 
### 5.1 Data Type & Memory
Let's discuss the most uses data types -  
|Data Type|Memory Size(Byte)|Representation|Note|
|---|---|---|---|
|Integer|4|int|P/N|
|Signed Integer|4|signed int|Same as Normal Integer|
|Unsigned Integer|4|unsigned int|P|
|Short Integer|2|short int|P/N|
|Long Integer|4/8|long int|P/N|
|Long Long Integer|8|long long int|P/N|
|Float|4|float|P/N, 23 bit value,8 bits exponent|
|Double|8|double|P/N, 52 bit value, 11 bits exponent|
|Long Double|12|long double|P/N, 64 bit value, 15 bit exponent|
|Character|1|char|P/N|
|Unsigned Character|1|unsigned char|P/N|
|Boolean|1 byte|bool|1 or 0|
