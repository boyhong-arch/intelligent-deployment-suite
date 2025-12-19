# 智运维一键装机与备份软件
This software is designed to run on the Windows operating system. It enables fully automated system installation, restoration, or one-click backup with a single restart of the computer.
Language: Simplified Chinese
Operating Environment: Windows 7 and above
Alternative Cloud Download Link: 
https://pan.baidu.com/s/14GdA6JoX44GQm91hwxRD8w?pwd=zgzg Code: zgzg
https://www.123865.com/s/Gm29-A7t4?pwd=zgzg# Code:zgzg

# 开发背景
The origin of this tool dates back many years ago, when I stumbled upon a problematic one-click installation source code archive in a QQ group chat. Over the years, I have intermittently worked on it—modifying, patching, and extensively "borrowing" ideas from the UI and functionalities of similar software. I have removed a significant amount of unclean code from the original program, corrected UI recognition issues specific to Windows 10 and Windows 11, and added a prompt upon launch that asks users if they wish to perform a backup, prioritizing data security based on my practical work needs. Now, I am sharing it with the community.

# 核心优势
Compared to similar software, this tool offers the following key advantages:
Clean & Trustworthy: It is clean, clean, and clean! Unlike some one-click installers found online that modify your homepage or bundle unwanted software, this one absolutely does not. (Prerequisite: The system image you use must also be clean.)
Fully Automated Operation: It runs within the current Windows system and can perform fully automated one-click installation or backup after restarting the computer. Imagine the convenience for remote system installation scenarios. (Remember to check the "Unattended" option.)
Completely Free: It is free software with no usage restrictions whatsoever.

# 已知局限
The overall file size is somewhat large. This is because it incorporates a maintenance version of PE (Preinstallation Environment) by the respected developer kuer as its base (to which I have added additional hardware drivers and software). I would also like to express my gratitude to kuer and many other generous contributors online for their selfless sharing.

# 使用指南 (Easy to Use)
The software is designed to be very user-friendly:
Install System Image: (Instructions for installing a system image would go here).
<img width="616" height="890" alt="必看：一键系统安装方法" src="https://github.com/user-attachments/assets/c51bf4b6-d441-4932-a0a3-8e6a40ea1fe3" />

Install Built-in Maintenance PE to Boot Menu: (Instructions for adding the PE to the boot menu would go here).
<img width="583" height="814" alt="安装PE到本地系统" src="https://github.com/user-attachments/assets/ecd0bef1-0e57-4a62-84fe-776f4fbd02c6" />

Backup Current System: (Instructions for backing up the current system would go here).
<img width="560" height="400" alt="备份系统教程" src="https://github.com/user-attachments/assets/b438fdec-3506-403c-8e11-4e73c258f97f" />

Backup Current System Drivers (Relies on PowerShell. This feature will not work if this component has been excessively removed from your current system).
<img width="744" height="585" alt="备份系统驱动及mas在线调用等等" src="https://github.com/user-attachments/assets/a039bb39-9f44-431f-8226-c51b378add1d" />
