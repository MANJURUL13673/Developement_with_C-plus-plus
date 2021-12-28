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

After open the VS, maybe you will see 4 options in the right side(VS 2019). Pressing the **Create a new project** button, you will look a different window with different project type.  
<!--Project Type -->
1. Empty Project
2. Console App
3. CMake Project
4. Windows Desktop Wizard
5. Windows Desktop Application
6. Blank Solution
7. MFC App
8. Dynamic Link Library (DLL)
9. Static Library
10. Shared Items Project
11. ATL Project
12. MFC Dynamic-Link Library
13. Makefile Project
14. MFC ActiveX Control
15. Native Unit Test Project
16. Google Test
17. Dynamic-Link Library with exports (DLL)  

Let's discuss the most usable project properties-   
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



