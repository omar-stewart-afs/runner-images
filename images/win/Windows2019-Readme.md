| Announcements |
|-|
| [[All OSs] .NET 3.1 will be removed from the images on July, 3](https://github.com/actions/runner-images/issues/7667) |
***
# Windows Server 2019
- OS Version: 10.0.17763 Build 4499
- Image Version: 20230630.1.0

## Windows features
- Windows Subsystem for Linux (WSLv1): Enabled

## Installed Software

### Language and Runtime
- Bash 5.2.15(1)-release
- Node 18.16.1

### Package Management
- Helm 3.12.0
- NPM 9.5.1
- NuGet 6.6.1.2
- Yarn 1.22.19

#### Environment variables
| Name                    | Value        |
| ----------------------- | ------------ |
| VCPKG_INSTALLATION_ROOT | C:\vcpkg     |

### Tools
- 7zip 23.01
- azcopy 10.19.0
- Bicep 0.18.4
- Docker 24.0.2
- Docker Compose v1 1.29.2
- Docker Compose v2 2.19.1
- Docker-wincred 0.7.0
- Git 2.41.0.windows.1
- Git LFS 3.3.0
- Kubectl 1.27.3
- Mercurial 5.0
- OpenSSL 1.1.1u
- WiX Toolset 3.11.2.4516
- yamllint 1.32.0

### CLI Tools
- Azure CLI 2.49.0
- Azure DevOps CLI extension 0.26.0
- GitHub CLI 2.31.0
- Hub CLI 2.14.2


#### Packages
- Clippy 0.1.70

### Browsers and Drivers
- Google Chrome 114.0.5735.199
- Chrome Driver 114.0.5735.90
- Microsoft Edge 114.0.1823.67
- Microsoft Edge Driver 114.0.1823.67

#### Environment variables
| Name              | Value                              |
| ----------------- | ---------------------------------- |
| CHROMEWEBDRIVER   | C:\SeleniumWebDrivers\ChromeDriver |
| EDGEWEBDRIVER     | C:\SeleniumWebDrivers\EdgeDriver   |

### Shells
| Name          | Target                            |
| ------------- | --------------------------------- |
| gitbash.exe   | C:\Program Files\Git\bin\bash.exe |
| msys2bash.cmd | C:\msys64\usr\bin\bash.exe        |
| wslbash.exe   | C:\Windows\System32\bash.exe      |

### Databases

### Database tools
- Azure CosmosDb Emulator 2.14.12.0

### Visual Studio Enterprise 2019
| Name                          | Version         | Path                                                           |
| ----------------------------- | --------------- | -------------------------------------------------------------- |
| Visual Studio Enterprise 2019 | 16.11.33801.447 | C:\Program Files (x86)\Microsoft Visual Studio\2019\Enterprise |

### .NET Core Tools
- .NET Core SDK: 6.0.119, 6.0.203, 6.0.314, 6.0.411
- .NET Framework: 4.7.2, 4.8
- Microsoft.AspNetCore.App: 6.0.5, 6.0.19
- Microsoft.NETCore.App: 6.0.5, 6.0.19
- Microsoft.WindowsDesktop.App: 6.0.5, 6.0.19
- nbgv 3.6.133+2d32d93cb1

### PowerShell Tools
- PowerShell 7.2.12

#### Powershell Modules
- Az: 9.3.0
- Azure: 2.1.0 (Default), 5.3.0
- AzureRM: 2.1.0 (Default), 6.13.1
- Az (Cached): 1.0.0.zip, 1.6.0.zip, 2.3.2.zip, 2.6.0.zip, 3.1.0.zip, 3.5.0.zip, 3.8.0.zip, 4.3.0.zip, 4.4.0.zip, 4.7.0.zip, 5.5.0.zip, 5.9.0.zip, 6.6.0.zip, 7.5.0.zip
- Azure (Cached): 3.8.0.zip, 4.2.1.zip, 5.1.1.zip
- AzureRM (Cached): 3.8.0.zip, 4.2.1.zip, 5.1.1.zip, 6.7.0.zip
- AWSPowershell: 4.1.363
- DockerMsftProvider: 1.0.0.8
- MarkdownPS: 1.9
- Microsoft.Graph: 1.28.0
- Pester: 3.4.0, 5.5.0
- PowerShellGet: 1.0.0.1, 2.2.5
- PSScriptAnalyzer: 1.21.0
- PSWindowsUpdate: 2.2.0.3
- VSSetup: 2.2.16
```
Azure PowerShell module 2.1.0 and AzureRM PowerShell module 2.1.0 are installed
and are available via 'Get-Module -ListAvailable'.
All other versions are saved but not installed.
```

### Cached Docker images
| Repository:Tag                                                            | Digest                                                                   | Created    |
| ------------------------------------------------------------------------- | ------------------------------------------------------------------------ | ---------- |
| mcr.microsoft.com/dotnet/framework/aspnet:4.8-windowsservercore-ltsc2019  | sha256:1c8e6d213d957497d12eb3ea2e462c64ba6b8ae88cc6c828bd5a0a9494274858  | 2023-06-23 |
| mcr.microsoft.com/dotnet/framework/runtime:4.8-windowsservercore-ltsc2019 | sha256:49aad131a4250da60e604cdeaac75c7b39fdb7665cfe5d7f45ac288e5e6861b1  | 2023-06-23 |
| mcr.microsoft.com/dotnet/framework/sdk:4.8-windowsservercore-ltsc2019     | sha256:7f3424f6c04d174c4e6c5e96f437b00e42ed5af958a73ea915d96ccf4d26c89e  | 2023-06-23 |
| mcr.microsoft.com/windows/nanoserver:1809                                 | sha256:81ab2c2f7ac2edf154915667f33ef9e2e77fdbe092c7cc562fff1fcf1762de22  | 2023-06-21 |
| mcr.microsoft.com/windows/servercore:ltsc2019                             | sha256:341ab68cf115626b5181a9621c2054f71ea6637d05f9d312c2b45a4204c0b94d  | 2023-06-21 |

