# About this project
The goal of this fork is to adapt setup scripts to personal needs, including development in WM.

# Original repro
For information about the original see:
https://github.com/Microsoft/windows-dev-box-setup-scripts

## Setting up a VM
Windows 10 VM setup instructions
1. Use Hyper-V's [Quick Create](https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/quick-start/quick-create-virtual-machine) to set up a VM
2. Once signed in to your VM, visit this project in a web browser and click one of the script links in the Readme

# Run the scripts
To run a recipe script, click a link in the table below from your target machine. This will download the Boxstarter one-click application, and prompt you for Boxstarter to run with Administrator privileges (which it needs to do its job). Clicking yes in this dialog will cause the recipe to begin. You can then leave the job unattended and come back when it's finished.

|Click link to run  |Description  |
|---------|---------|
|<a href='http://boxstarter.org/package/url?https://raw.githubusercontent.com/Turochamp/windows-dev-box-setup-scripts/master/dev_host.ps1'>Development Host</a>                | HyperV + My Host Development tools |
|<a href='http://boxstarter.org/package/url?https://raw.githubusercontent.com/Turochamp/windows-dev-box-setup-scripts/master/dev_spring_boot_vm.ps1'>Spring Boot + Web</a>     | My VM Development tools + JDK, JetBrain Tools, VS Code and WSL |

**Notes:**  
1. When the script finishes you will only have a root user with a blank password. You should  manually create a non-root user via `$ sudo adduser [USERNAME] sudo` 
with a non-blank password. Use this user going forward. For more info on WSL please refer to the [documentation](https://docs.microsoft.com/en-us/windows/wsl/about).

# Issues

1. Add Trello app
2. Add VS Community and Git-Win (https://git-scm.com/download/win)?
