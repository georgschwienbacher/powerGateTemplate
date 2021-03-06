# powergate-generic-sample

[![Windows](https://img.shields.io/badge/Platform-Windows-lightgray.svg)](https://www.microsoft.com/en-us/windows/)
[![PowerShell](https://img.shields.io/badge/PowerShell-5-blue.svg)](https://microsoft.com/PowerShell/)
[![.NET](https://img.shields.io/badge/.NET%20Framework-4.7-blue.svg)](https://dotnet.microsoft.com/)
[![Vault](https://img.shields.io/badge/Autodesk%20Vault-2020-yellow.svg)](https://www.autodesk.com/products/vault/)
[![Vault VDS](https://img.shields.io/badge/Autodesk%20Vault%20DataStandard-2020-yellow.svg)](https://www.autodesk.com/products/vault/)

[![powerGate](https://img.shields.io/badge/coolOrange%20powerGate-20-orange.svg)](https://www.coolorange.com/en-eu/connect.html#powerGate)
[![powerGate Server](https://img.shields.io/badge/coolOrange%20powerGate%20Server-20-orange.svg)](https://www.coolorange.com/en-eu/connect.html#powerGate)
[![powerJobs](https://img.shields.io/badge/coolOrange%20powerJobs-20-orange.svg)](https://www.coolorange.com/en-eu/enhance.html#powerJobs)
[![powerEvents](https://img.shields.io/badge/coolOrange%20powerEvents-20-orange.svg)](https://www.coolorange.com/en-eu/enhance.html#powerEvents)

## Disclaimer

THE SAMPLE CODE ON THIS REPOSITORY IS PROVIDED "AS IS" WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESSED OR IMPLIED, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, OR NON-INFRINGEMENT.

THE USAGE OF THIS SAMPLE IS AT YOUR OWN RISK AND **THERE IS NO SUPPORT** RELATED TO IT.

## Description

This sample demonstrates an ERP integration for Autodesk Vault Professional/Workgroup and Autodesk Inventor by using the coolOrange products powerGate, powerGate Server, powerJobs and powerEvents. It not only adds live views on ERP data to Vault and Inventor but also improves Vault workflows by resticting state changes when ERP data is incomplete and by creating and uploading PDF files to the ERP system when a Vault file or Vault item is released.

It is highly customizable and at the same time it works out-of-the-box with a built-in mockup-ERP system. However, this sample can be extended to work with any ERP system.

## Screenshots

![Sample Inventor](Images/Readme_Inventor.png)
![Sample Vault BOM](Images/Readme_Vault_BOM.png)

## Features

TBD!

## Prerequisites

### Autodesk Software
Autodesk Vault 2020 Professional, Autodesk Inventor 2020 and Autodesk Vault DataStandard for Vault and Inventor needs to be installed.

### coolOrange Software 
coolOrange powerGate, coolOrange powerGate Server, coolOrange powerJobs and coolOrange powerEvents needs to be installed.  
coolOrange software can be obtained from the [coolOrange Download Portal](https://download.coolorange.com)

## Installation
Install the latest version from the repository [Releases](https://github.com/coolOrangeLabs/powerGateTemplate/releases/latest) page. The following installers are available: 

### powerGate Server plugin
This setup contains a powerGate Server plugin. It needs to be installed on the machine that hosts coolOrange powerGate Server.

### Vault DataStandard customizations & powerEvents
This setup contains Autodesk Vault DataStandard customizations and coolOrange powerEvents workflow enhancements. It needs to be installed on all Vault client machines. Autodesk Vault DataStandard and coolOrange powerEvents are required on these machines, too.

### powerJobs
This setup contains powerJobs jobs. It needs to be installed on the machine that hosts a Autodesk Vault JobProcessor and coolOrange powerJobs.

## Usage

The script located [createGithubRepository.ps1](https://github.com/coolOrangeProjects/PowerShell.Extensions/tree/master/Others/Automated%20Repository%20Creation) allows a dynamic creation of a new repository under `https://www.github.com/coolOrangeProjects`. The repository copies source code, issues, labels, projects and wiki from this template.

## Configuration

#### Wiki
The wiki under https://github.com/coolOrangeLabs/powerGateTemplate.wiki represents the exact same structure and files which will be created if a new repository of powerGateTemplate is created. Each change in these files will also be applied to new repositories of powerGateTemplate. 
The following strings are modifed when using the script:
| File | Expresson | Expected Value |
| - | - | - |
| Home.md |{REPO_NAME} | The name of the repository | 
| Client-Installation.md |{YEAR} | The version/year of the Autodesk products |


## Product Documentation

[coolOrange powerGate](https://www.coolorange.com/wiki/doku.php?id=powergate)  
[coolOrange powerGate Server](https://www.coolorange.com/wiki/doku.php?id=powergateserver)  
[coolOrange powerJobs](https://www.coolorange.com/wiki/doku.php?id=powerjobs)  
[coolOrange powerEvents](https://www.coolorange.com/wiki/doku.php?id=powerevents)


## Author
coolOrange s.r.l.  
Channel Readiness Team

![coolOrange](https://user-images.githubusercontent.com/36075173/46519882-4b518880-c87a-11e8-8dab-dffe826a9630.png)
