# clidis
A command line display manager to start your desktop more intractive!

![clidis preview](https://raw.githubusercontent.com/virtualdemon/clidis/master/screenshot/screenshot.png)

![RepoSize](https://img.shields.io/github/repo-size/hamidrezakp/clidis.svg) ![Contributors](https://img.shields.io/github/contributors/hamidrezakp/clidis.svg?style=flat-square)
    
## HOW TO USE

1. download the script with `curl` or `wget` : 
	
    `wget https://raw.githubusercontent.com/hamidrezakp/clidis/master/clidis -O ~/.clidis`

	`curl https://raw.githubusercontent.com/hamidrezakp/clidis/master/clidis -o ~/.clidis`
	        
2. change script permission (just once!) : 

	`chmod +x ~/.clidis`

3. run it from tty when there isn't any display manager running : 

	`~/.clidis`

## AUTOMATIC RUN AFTER LOG IN

1. disable your current display manager : 

    `sudo systemctl disable display-manager.service`

2. append the following line into your login shell profile (`zsh` -> **~/.zprofile** | `fish` -> **~/.config/fish/config.fish** | `bash` -> **~/.bash_profile**) : 
    
    `exec bash $HOME/.clidis`
    
    if you don't know what's your login shell, just run this command : 
    
    `echo $SHELL`
    
### TODO
   [x] Adding squares to select options
   [x] Adding vim key's for moving around options
   [ ] Adding power options ( reboot, shutdown , ... )
   [ ] Adding Sabooh (@mostafaAsadi) option to login page
   [ ] Adding systemd-analyze to login page
   [ ] Adding config file
    
### MORE

>  special thanks to :
    MisterH
    virtualdemon
    
Made with :heart: for cli users!
