# RedistributableChecker
An updated version of bitbeans' Redistributable Checker. Check if Microsoft Visual C++ Redistributable Packages are installed.
* [General info](#general-info)
* [Packages](#technologies)
* [Setup](#setup)

## General info
An updated version of bitbeans' Redistributable Checker. Check if Microsoft Visual C++ Redistributable Packages are installed.
	
## Packages
Can check for the following packages:
Microsoft Visual C++ Redistributable Package 2015 - 2019 (x86) ✔️
Microsoft Visual C++ Redistributable Package 2015 - 2019 (x64) ✔️
Microsoft Visual C++ Redistributable Package 2017 (x86) ✔️
Microsoft Visual C++ Redistributable Package 2017 (x64) ✔️
Microsoft Visual C++ Redistributable Package 2015 (x86) ✔️
Microsoft Visual C++ Redistributable Package 2015 (x64) ✔️
Microsoft Visual C++ Redistributable Package 2013 (x86) ✔️
Microsoft Visual C++ Redistributable Package 2013 (x64) ✔️
Microsoft Visual C++ Redistributable Package 2012 (x86) ✔️
Microsoft Visual C++ Redistributable Package 2012 (x64) ✔️
Microsoft Visual C++ Redistributable Package 2010 (x86) ✔️
Microsoft Visual C++ Redistributable Package 2010 (x64) ✔️
Microsoft Visual C++ Redistributable Package 2008 (x86) ✔️
Microsoft Visual C++ Redistributable Package 2008 (x64) ✔️
Microsoft Visual C++ Redistributable Package 2005 (x86) ✔️
Microsoft Visual C++ Redistributable Package 2005 (x64) ✔️
	
## Setup
To run this project, install it locally using npm:

```csharp
using RedistributableChecker;

if (RedistributablePackage.IsInstalled(RedistributablePackageVersion.VC2013x64)) {
  //go on
}
```
