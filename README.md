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
## Chapter 2 Create a New Project

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
|Pros or Cons|1. Problem to use Win32 SDK that you need to manually write code for everything.</br>2. This lead to errors in code.|1. MFC is composed of functions that are most commonly used by programmers.</br>2.This lead easy to use.|  

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


