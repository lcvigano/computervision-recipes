# Contributions

The *contrib* directory contains code which is not part of the main Computer Vision repository but deemed to be of interest and aligned with the goals of this repository. The code does not need to follow our strict coding guidelines, and in fact none of it is tested via our devops pipeline, and might be buggy, not maintained, etc.

Each project should live in its own subdirectory ```/contrib/<project>``` and contain a README.md file with detailed description what the project does and how to use it. In addition, when adding a new project, a brief description should be added to the table below.


## Scenarios
| Directory | Project description | Build status (optional) |
|---|---|---|
| [Action recognition](action_recognition) | Action recognition to identify in video/webcam footage what actions are performed (e.g. "running", "opening a bottle") and at what respective start/end times.| |
| [Crowd counting](crowd_counting) | Counting the number of people in low-crowd-density (e.g. less than 10 people) and high-crowd-density (e.g. thousands of people) scenarios. | [![Build Status](https://dev.azure.com/team-sharat/crowd-counting/_apis/build/status/lixzhang.cnt?branchName=lixzhang%2Fsubmodule-rev3)](https://dev.azure.com/team-sharat/crowd-counting/_build/latest?definitionId=49&branchName=lixzhang%2Fsubmodule-rev3)|

## Tools
| Directory | Project description | Build status (optional) |
|---|---|---|
| [vm_builder](vm_builder) | This script helps users create a single Ubuntu Data Science Virtual Machine with a GPU with the computer vision recipes repo installed and ready to be used. If you find the script to be out-dated or not working, you can create the VM using the Azure portal or the Azure CLI tool with a few more steps. | |
| [vmss_builder](vmss_builder) | This script helps you setup a cluster of virtual machines with the computer vision recipes repo pre-installed using VMSS. This cluster is designed to be temporal, ie to be spun up and torn down. Users for this cluster will be prescribed a username/password/ip. This setup can be used for hands-on / lab sessions when you need to prepare multiple VM environments for a short period.|
