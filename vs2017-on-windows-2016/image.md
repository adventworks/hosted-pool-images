# VSTS Hosted VS2017 image

Version 2017.10.02

The following software is installed on machines in the VSTS **Hosted VS2017** pool.

Components marked with **\*** have been upgraded since the previous version of the image.

## Visual Studio 2017 Enterprise *

_Version:_ 15.4.0<br/>
_Location:_ C:\Program Files (x86)\Microsoft Visual Studio\2017\Enterprise

The following workloads are installed with Visual Studio 2017:
* [Universal Windows Platform development](_img/uwp.png)
* [.NET desktop development](_img/dotnet.png)
* [Desktop development with C++](_img/cpp.png)
* [ASP.NET and web development](_img/uwp.png)
* [Azure development](_img/azure.png)
* [Node.js development](_img/nodejs.png)
* [Data storage and processing](_img/data.png)
* [Office/SharePoint development](_img/office.png)
* [Mobile development with .NET](_img/mobile.png)
* [.NET Core cross-platform development](_img/dotnet-xplat.png)
* [Visual Studio extension development](_img/extension.png) *
* [Additional components](_img/individual.png)

## SQL Server Data Tools for VS 2017

_Version:_ 14.0.16121.0<br/>
_SQL Server Data Tier Application Framework (x64) Version:_  14.0.3757.2

## WIX Tools

_Toolset Version:_ 3.11<br/>
_WIX Toolset Studio 2017 Extension Version:_ 0.9.21.62588<br/>
_Environment:_
* WIX: Installation root of WIX

## .NET Core

The following runtime/SDK combinations are installed.

#### 2.0.0 with SDK 2.0.0

_Runtime location:_ C:\Program Files\dotnet\shared\Microsoft.NETCore.App\2.0.0<br/>
_SDK location:_ C:\Program Files\dotnet\sdk\2.0.0<br/>
_Environment:_
* PATH: contains location of dotnet.exe

#### 1.1.4 with SDK 1.1.4

_Runtime location:_ C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.1.4<br/>
_SDK location:_ C:\Program Files\dotnet\sdk\1.1.4

#### 1.1.2 with SDK 1.0.4

_Runtime location:_ C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.1.2<br/>
_SDK location:_ C:\Program Files\dotnet\sdk\1.0.4

#### <span style="color:#ED2836">1.1.1 with SDK 1.0.3</span>

_Warning: This version will be removed in a future update of the image.<br/>_
_Runtime location:_ C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.1.1<br/>
_SDK location:_ C:\Program Files\dotnet\sdk\1.0.3

#### 1.0.7 with SDK 1.1.4

_Runtime location:_ C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.0.7<br/>
_SDK location:_ C:\Program Files\dotnet\sdk\1.1.4

#### <span style="color:#ED2836">1.0.5 with SDK 1.0.4</span>

_Warning: This version will be removed in a future update of the image.<br/>_
_Runtime location:_ C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.0.5<br/>
_SDK location:_ C:\Program Files\dotnet\sdk\1.0.4

#### <span style="color:#ED2836">1.0.4 with SDK 1.0.3</span>

_Warning: This version will be removed in a future update of the image.<br/>_
_Runtime location:_ C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.0.4<br/>
_SDK location:_ C:\Program Files\dotnet\sdk\1.0.3

## Powershell

_Version:_ 5.1.1715

## Azure/AzureRM Powershell modules

#### 2.1.0

This version is installed and is available via `Get-Module -ListAvailable`

#### 3.8.0

This version is saved but not installed.<br/>
_Location:_ C:\Modules\azure_3.8.0 and C:\Modules\azurerm_3.8.0

#### 4.2.1

This version is saved but not installed.<br/>
_Location:_ C:\Modules\azure_4.2.1 and C:\Modules\azurerm_4.2.1

## Azure CLI

_Version:_ 2.0.14<br/>
_Environment:_
* PATH: contains location of az.cmd

## Azure Service Fabric *

_SDK Version:_ 2.8.211.9494<br/>
_Runtime Version:_ 6.0.211.9494

## Git

_Version:_ 2.14.1<br/>
_Environment:_
* PATH: contains location of git.exe

## Git LFS

_Version:_ 2.3.0<br/>
_Environment:_
* PATH: contains location of git-lfs.exe
* GIT_LFS_PATH: location of git-lfs.exe

## Node.js

_Version:_ 6.10.0<br/>
_Environment:_
* PATH: contains location of node.exe<br/>

> Note: You can install and use another version of Node on the hosted agents using the [Node tool installer](https://docs.microsoft.com/en-us/vsts/build-release/tasks/tool/node-js) task.

## npm

_Version:_ 3.10.10<br/>
_Environment:_
* PATH: contains location of npm.cmd

## Docker

_Version:_ 17.10.0-ee-preview-2<br/>
_Environment:_
* PATH: contains location of docker.exe

## Docker-compose

_Version:_ 1.16.1<br/>
_Environment:_
* PATH: contains location of docker-compose.exe

## Java Development Kit

#### 1.8.0_112

_Environment:_
* JAVA_HOME: location of JDK
* PATH: contains bin folder of JDK

#### 1.8.0_102

_Location:_ C:\java\jdk\1.8.0_102

#### 1.7.0_75

_Location:_ C:\java\jdk\1.7.0_75

#### <span style="color:#ED2836">1.6.0_45</span>

_Warning: This version will be removed in a future update of the image.<br/>_
_Location:_ C:\java\jdk\1.6.0_45

## Ant

_Version:_ 1.9.7<br/>
_Environment:_
* PATH: contains location of ant.cmd
* ANT_HOME: location of ant.cmd
* COBERTURA_HOME: location of cobertura-2.1.1.jar

## Maven *

_Version:_ 3.5.0<br/>
_Environment:_
* PATH: contains location of mvn.bat
* M2_HOME: Maven installation root

## Cmake

_Version:_ 3.8.0-rc4<br/>
_Environment:_
* PATH: contains location of cmake.exe

## Python (64 bit)

#### 3.6.2
_Environment:_
* PATH: contains location of python.exe

#### 2.7.13

_Location:_ C:\Python27amd64

## Android SDK Build Tools

#### 26.0.2 *

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\26.0.2

#### 25.0.2

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\25.0.2

#### 25.0.1

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\25.0.1

#### 25.0.0

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\25.0.0

##### 24.0.3

_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\24.0.3

#### <span style="color:#ED2836">24.0.2</span>

_Warning: This version will be removed in a future update of the image.<br/>_
_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\24.0.2

#### <span style="color:#ED2836">24.0.1</span>

_Warning: This version will be removed in a future update of the image.<br/>_
_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\24.0.1

#### <span style="color:#ED2836">24.0.0</span>

_Warning: This version will be removed in a future update of the image.<br/>_
_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\24.0.0

#### 23.0.3

_Warning: This version will be removed in a future update of the image.<br/>_
_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\23.0.3

#### <span style="color:#ED2836">23.0.2</span>

_Warning: This version will be removed in a future update of the image.<br/>_
_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\23.0.2

#### <span style="color:#ED2836">23.0.1</span>

_Warning: This version will be removed in a future update of the image.<br/>_
_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\23.0.1

#### <span style="color:#ED2836">22.0.1</span>

_Warning: This version will be removed in a future update of the image.<br/>_
_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\22.0.1

#### <span style="color:#ED2836">21.1.2</span>

_Warning: This version will be removed in a future update of the image.<br/>_
_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\21.1.2

#### <span style="color:#ED2836">20.0.0</span>

_Warning: This version will be removed in a future update of the image.<br/>_
_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\20.0.0

#### <span style="color:#ED2836">19.1.0</span>

_Warning: This version will be removed in a future update of the image.<br/>_
_Location:_ C:\Program Files (x86)\Android\android-sdk\build-tools\19.1.0

## Android SDK Platforms

#### 8.0.0 (API 26) *

_Location:_ C:\Program Files (x86)\Android\android-sdk\platforms\android-26

#### 7.1.1 (API 25)

_Location:_ C:\Program Files (x86)\Android\android-sdk\platforms\android-25

#### 7.0 (API 24)

_Location:_ C:\Program Files (x86)\Android\android-sdk\platforms\android-24

#### 6.0 (API 23)

_Location:_ C:\Program Files (x86)\Android\android-sdk\platforms\android-23

#### <span style="color:#ED2836">5.1.1 (API 22)</span>

_Warning: This version will be removed in a future update of the image.<br/>_
_Location:_ C:\Program Files (x86)\Android\android-sdk\platforms\android-22

#### <span style="color:#ED2836">5.0.1 (API 21)</span>

_Warning: This version will be removed in a future update of the image.<br/>_
_Location:_ C:\Program Files (x86)\Android\android-sdk\platforms\android-21

#### <span style="color:#ED2836">4.4.2 (API 19)</span>

_This version will be removed in a future update of the image.<br/>_
_Location:_ C:\Program Files (x86)\Android\android-sdk\platforms\android-19

## Android NDK

_Version:_ R13b<br/>
_Environment:_
* ANDROID_NDK_HOME: Location of NDK
* ANDROID_NDK_PATH: Location of NDK
