![Alt text](/screenshot.png?raw=true "Screenshot")  

### Extremly Simple Quickstart  
(without starti3, xfce4 chroot installed as primary chroot for sudo startxfce4, and without VPN):  

Download menu.sh on chromebook in Downloadsfolder  
1.In Chromebrowser press ctrl+alt+t for terminal.  
2.Type "shell"+enter  
3.Type "cp ~/Downloads/menu.sh ~/menu.sh"+enter  
4.Type "chmod +x ~/menu.sh"+enter  
5.Type "echo "bash ~/menu.sh" >> ~/.bashrc"+enter  
6.Type "exit"+enter  
  
Repeat 2  
  
### Uninstall:  
1+2  
Select Exit  
Type "vi ~/.bashrc"+enter  
Go to line with bash ~/menu.sh"  
Press "dd"  
*Deleted the wrong line? Press Esc-key, Type ":q!"+enter, start vi again  
Press Esc-key  
Type ":wq"+enter  
Type "exit"+enter  
  
  
### Advanced: cat menu.sh and see comments on bottom  
  
  
Thanks to original scriptauthor oToGamez for providing a bash-menu without dependencies like dialog and inspiring me to write dialog-based ChromeOS Stuff  
