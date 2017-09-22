# VSTS hosted pool image - Visual Studio 2017 on Windows Server 2016

Version 2017.09.1

## Installed components

| Component | Version | Location |
|-----------|---------|----------|
| Visual Studio 2017 Enterprise with the following workloads <ul> <li> Universal Windows Platform development </li><li> .NET desktop development </li><li> Desktop development with C++</li><li>ASP.NET and web development</li><li>Azure development</li><li>Node.js development</li><li>Data storage and processing</li><li>Office/SharePoint development</li><li>Mobile development with .NET</li><li>.NET Core cross-platform development</li></ul> | 15.3.5 * | C:\Program Files (x86)\Microsoft Visual Studio\2017\Enterprise |
| .NET Core | 2.0.0 with SDK 2.0.0 | C:\Program Files\dotnet (in PATH)<br/> C:\Program Files\dotnet\sdk\2.0.0 |
| | 1.1.4 with SDK 1.1.4 | C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.1.4<br/>C:\Program Files\dotnet\sdk\1.1.4 |
| | 1.1.2 with SDK 1.0.4 | C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.1.2<br/>C:\Program Files\dotnet\sdk\1.0.4 |
| | 1.1.1 with SDK 1.0.3 | C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.1.1<br/>C:\Program Files\dotnet\sdk\1.0.3 |
| | 1.0.7 with SDK 1.1.4 | C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.0.7<br/>C:\Program Files\dotnet\sdk\1.1.4 |
| | 1.0.5 with SDK 1.0.4 | C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.0.5<br/>C:\Program Files\dotnet\sdk\1.0.4 |
| | 1.0.4 with SDK 1.0.3 | C:\Program Files\dotnet\shared\Microsoft.NETCore.App\1.0.4<br/>C:\Program Files\dotnet\sdk\1.0.3 |
| Git | 2.14.1 | in PATH |
| Git LFS | 2.3.0 * | in PATH |
| Node.js | 6.10.0 | in PATH |
| npm | 3.10.10 | in PATH |
| Docker | 17.10.0-ee-preview-2 * | in PATH |
| Docker-compose | 1.16.1 * | in PATH |
| JDK | 1.8.0_112 | C:\Program Files\Java\jdk1.8.0_112 (\bin in PATH) |
| | 1.8.0_102 ** | C:\java\jdk\1.8.0_102 |
| | 1.7.0_75 ** | C:\java\jdk\1.7.0_75 |
| | 1.6.0_45 ** | C:\java\jdk\1.6.0_45 |
| Cmake | 3.8.0-rc4 | in PATH |
| Ant | 1.9.7 | in PATH |
| Maven | 3.2.2 | in PATH |
| Python 64 bit | 3.6.2 | in PATH |
| | 2.7.13 | C:\Python27amd64 |
| Powershell | 5.1.1715 |
| Azure/AzureRM Powershell modules | 2.1.0 | Installed module |
| | 3.8.0 | Saved in C:\Modules\azure_3.8.0 and C:\Modules\azurerm_3.8.0 |
| | 4.2.1 | Saved in C:\Modules\azure_4.2.1 and C:\Modules\azurerm_4.2.1 |
| Azure CLI | 2.0.14 | in PATH |
| Microsoft Azure Service Fabric SDK | 2.7.198.9494 | |
| Microsoft Azure Service Fabric | 5.7.198.9494 | |
| WiX Toolset | 3.11 * | |
| WiX Toolset Visual Studio 2017 Extension | 0.9.21.62588 * | |
| SQL Server Data Tools for VS 2017 | 14.0.16121.0 * | |
| SQL Server Data Tier Application Framework (x64) | 14.0.3757.2 * | |
| Android SDK Build Tools | 25.2.5 | C:\Program Files (x86)\Android\android-sdk\build-tools\25.0.2 |
| | 25.0.1 | C:\Program Files (x86)\Android\android-sdk\build-tools\25.0.1 |
| | 25.0.0 | C:\Program Files (x86)\Android\android-sdk\build-tools\25.0.0 |
| | 24.0.3 | C:\Program Files (x86)\Android\android-sdk\build-tools\24.0.3 |
| | 24.0.2 ** | C:\Program Files (x86)\Android\android-sdk\build-tools\24.0.2 |
| | 24.0.1 ** | C:\Program Files (x86)\Android\android-sdk\build-tools\24.0.1 |
| | 24.0.0 ** | C:\Program Files (x86)\Android\android-sdk\build-tools\24.0.0 |
| | 23.0.3 | C:\Program Files (x86)\Android\android-sdk\build-tools\23.0.3 |
| | 23.0.2 ** | C:\Program Files (x86)\Android\android-sdk\build-tools\23.0.2 |
| | 23.0.1 ** | C:\Program Files (x86)\Android\android-sdk\build-tools\23.0.1 |
| | 22.0.1 ** | C:\Program Files (x86)\Android\android-sdk\build-tools\22.0.1 |
| | 21.1.2 ** | C:\Program Files (x86)\Android\android-sdk\build-tools\21.1.2 |
| | 20.0.0 ** | C:\Program Files (x86)\Android\android-sdk\build-tools\20.0.0 |
| | 19.1.0 ** | C:\Program Files (x86)\Android\android-sdk\build-tools\19.1.0 |
| Android SDK Platforms | 7.1.1 (API 25) | C:\Program Files (x86)\Android\android-sdk\platforms\android-25 |
| | 7.0 (API 24) | C:\Program Files (x86)\Android\android-sdk\platforms\android-24 |
| | 6.0 (API 23) | C:\Program Files (x86)\Android\android-sdk\platforms\android-23 |
| | 5.1.1 (API 22) ** | C:\Program Files (x86)\Android\android-sdk\platforms\android-22 |
| | 5.0.1 (API 21) ** | C:\Program Files (x86)\Android\android-sdk\platforms\android-21 |
| | 4.4.2 (API 19) ** | C:\Program Files (x86)\Android\android-sdk\platforms\android-19 |

\* Upgraded from previous update of image

\** Will be removed in the next update of image

## Known issues

None
