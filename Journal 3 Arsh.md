# Journal 3
Author: **Arshjit Sansoe**<br/>
Date: **12/10/2021**<br/>
Group: **Arshjit Sansoe**, **Kofi Osel**, and **George Aziz**
## Completed the process of deploying our website on Nginx
It took a long process to make files with touch and copy and paste our website code for each file into our new files.
We decided to delete the old files from the path **"/var/www/html"** for each team members folder and replace them with 
all the files. We used the command **scp** which does a secure copy of our files. Firstly, we had to copy the folder
into the vps main directory, then copy the files to the **"/var/www/html"** path. For both of these tasks we had to use
**scp** command. Once done, we just had to change the main html file names to **index.html**. Afterwards, we just opened
our websites on the Google Chrome browser. 
## Setting up Jekyll Website on our systems
Before anything, we had to install **Ruby** and **Bundle** on our systems. We used the commands
**sudo apt-get install ruby-full build-essential**, **bundle install**, & **sudo gem install jekyll bundler**. Once we
were done installing all the Jekyll dependencies, we made a new directory with static website inside it. We created the 
directory and installed Jekyll inside the new directory with the command **"sudo jekyll new myblog"** and named the
directory **"myblog"**. After we went into the new directory called **"myblog"** with the command**cd myblog**. We ran
the Jekyll website we generated with **sudo bundle exec jekyll serve** Once the command **sudo bundle exec jekyll
serve** successfully ran, we opened it with the link **http://localhost:4000/**.
## Images & Resources
### Completed the process of deploying our website on Nginx
- ![](https://github.com/KofiOsel/gittest2/blob/master/test/Screenshot%202021-12-07%20230920.png?raw=true)
- ![](https://github.com/KofiOsel/gittest2/blob/master/test/Screenshot%202021-12-07%20231005.png?raw=true)
- ![](https://github.com/KofiOsel/gittest2/blob/master/test/Screenshot%202021-12-07%20231056.png?raw=true)
- ![](https://github.com/KofiOsel/gittest2/blob/master/test/Screenshot%202021-12-07%20231216.png?raw=true)
- ![](https://github.com/KofiOsel/gittest2/blob/master/test/Screenshot%202021-12-07%20231440.png?raw=true)
- ![](https://github.com/KofiOsel/gittest2/blob/master/test/Screenshot%202021-12-10%20204018.png?raw=true)
- ![](https://github.com/KofiOsel/gittest2/blob/master/test/Capture.JPG?raw=true)
- Git Repository:<br/>https://github.com/jojo0105/UnixFinalProject
- Git Repository:<br/>https://github.com/KofiOsel/gittest2