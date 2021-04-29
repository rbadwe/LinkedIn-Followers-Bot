## linkedin bot for sending connect requests 

This is a fork of https://github.com/VirtualGoat/LinkedIn-Followers-Bot . 

To run this 

1. clone the git repo
2. get geckodriver/chromedriver executable - (selenium gives problems on linux if the driver is in a priviledged directory )
    1. Firefox  - Get the executable from AUR or firefox site and move it to Home/youlocation 
    2. Chromedriver  - if you have chrome/chromium installed the executable can be found at usr/lib/chromium ( for arch )
    copy and paste it at the home/yourlocation
       
3. make the driver file executable with chmod +x
4. run the automation_script.py in the Linkedin-Followers-bot directory 
5. when asked for path to driver put the above home/yourlocation/chromedriver

#### requirement
1. selenium 
---
Issues 
1. Linkedin  site layout changes  frequently hence the xpath for buttons may not be valid and you may need to replace them
2. After 15 something requests it will give a  prompt and the bot will stop . ( simplest way ive found is to 
   autorun the script 4-5 times a day or you can add modification to the automation_script.py)
   
---
If you can and want to improve this please contribute to the original project . 

---