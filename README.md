# SmartMove
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fchkp-ofirs%2FSmartMove.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fchkp-ofirs%2FSmartMove?ref=badge_shield)

Check Point SmartMove tool enables you to convert 3rd party database with firewall security policy and NAT to Check Point database.

At the moment, the tool parses Cisco ASA, FirePower with ASA syntax, Juniper JunosOS/ScreenOS, Fortinet FortiOS, PaloAlto PAN-OS and PaloAlto Panorama configurations and converts the objects, NAT and firewall policy to a Check Point R80.10 compliant policy. The tool is planned to support additional vendors and security configurations in the future.

The tool generates bash scripts by utilizing Check Point Management API's command line interface, to migrate the converted policy into a R80.10 Management (or Multi-Domain) server.

For SmartMove tool release notes and latest updates, please refer to Check Point [sk115416](https://supportcenter.checkpoint.com/supportcenter/portal?eventSubmit_doGoviewsolutiondetails=&solutionid=sk115416)


## Smart Connector and PaloAlto Panorama Instructions
'Smart Connector' and 'PaloAlto Panorama' are using external reasorces.

* Dowload the required package from the Check Point Support Center: <br>
[Dwonload](https://supportcenter.checkpoint.com/supportcenter/portal?action=portlets.DCFileAction&eventSubmit_doGetdcdetails=&fileid=110747)
* Extract the downloaded package into this path inside your project:<br> 
```SmartMove\SmartMove\compressors\```
* Rebuild the solution:
  * In Solution Explorer, choose or open the solution. 
  * On the menu bar, choose Build, and then choose Rebuild Solution.

# cp_mgmt_api_python_sdk
Check Point API Python Development Kit simplifies the use of the Check Point Management APIs. The kit contains the API library files, and sample files demonstrating the 
capabilities of the library. The kit is compatible with python 2 and 3.

## Instructions
https://github.com/CheckPointSW/cp_mgmt_api_python_sdk



## Development Environment
The tool is developed using Microsoft C# language and .Net framework version 4.5 (WPF application). The project solution file is configured for Microsoft Visual Studio 2012 and above.

From version 9.1 the tool is developed using Python language version 3.7.

### Note:
Please create the pull request with a request to merge into the staging branch instead of into the master branch. 

This allows us to do testing, and to make any additional edits or changes after the merge but before merging to master.

### A Note About Maintenance:

NOTICE! Maintenance of this program is on a ''best effort'' basis. 
We try to get to issues and pull requests as quickly as we can. 


## 💧 Community
Join the welcoming community of Check Point SmartMove developers at [CheckMATES](https://community.checkpoint.com/t5/SmartMove/bd-p/smartmove) 

## 🚀 Contributing
To contribute a feature or idea to SmartMove, create an post explaining your idea or bring it up at [CheckMATES](https://community.checkpoint.com/t5/SmartMove/bd-p/smartmove) 

If you find a bug, please create an post and notify us at [CheckMATES](https://community.checkpoint.com/t5/SmartMove/bd-p/smartmove) 

If you find a security vulnerability, please report us as soon as possible: [Report a Potential Security Issue](https://www.checkpoint.com/security-issue/) 

To create a pull request , please read [contributing](https://github.com/CheckPointSW/SmartMove/blob/master/.github/contributing.md) 


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fchkp-ofirs%2FSmartMove.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fchkp-ofirs%2FSmartMove?ref=badge_large)