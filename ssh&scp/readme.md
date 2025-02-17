# SSH Connection method 

  ## In This section I will show you how to `connect/access` any `linux/windows` machine.
  # Linux Method 
  `SSH CONNECTION` : ssh stand for Secure Shell.
  suppose that you are on linux machine: 
  Here i am using kali Linux. 
  open `terminal` Type 
  `ssh`

  If it not installed, it showed  `Do you want to install it ? (Y/n)` press `Y` . After installed type : 
  
  ```Sudo systemctl status ssh``` -- (ssh status).
  
  If if is is inactive then type `sudo systemctl start sshd`. -- ( Start ssh)

  It will active, then again check the `ssh status`
  ![ssh running status](<ssh_enable_ running.png>)

  If not running then type `sudo systemctl restart sshd`.
  If it not working then install `openssh-server`

  ---------------------

  # Windows Method 

  First go to the windows app features type : `Win + I`, go to features > add new app > type open . install `openssh-server and openssh client`. 

  open Powershell `Run as administrator` type   `Get-Service sshd` - (ssh status)
  
  If it inactive type: `Start-Service sshd` - ( active ssh)

  check the status again. 
  ![Win ssh status](<win_enable_ssh.png>)

-----------------------------------

 # Connecting from windows to Linux 
- Open powershell and type: `ssh username@Ip_Address`
- Enter password and done!
  ![Win to Linux Connection](<win_Linux.png>)
----------------------
# Connecting form Linux to windows

  - open terminal and type `ssh username@iP_Address`
  - Enter password and boom!
  ![Linux to Windows Connection](<linux_Windows.png>)

# SCP : stand for `SECURE FILE COPY`

  ## Useses: [SCP](https://www.geeksforgeeks.org/scp-command-in-linux-with-examples/)


  ________________________________
  # 
                                            HAPPY HACKING 
                                            



                             ____  _______    ______  __ _    ____________ 
                          / __ \/ ____/ |  / / __ \/ /| |  / /____/ ___\\
                         / /_/ / __/  | | / / / / / / | | / / __/ / /_/ /
                        / _, _/ /___  | |/ / /_/ / /__| |/ / /___/ _, _/  
                       /_/ |_/_____/  |___/\____/_____/___/_____/_/ |_|   
                                    Written By ROOT~REVOLVER