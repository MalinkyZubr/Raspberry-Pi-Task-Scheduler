# Raspberry-Pi-Task-Scheduler
## Purpose
Often, I find myself testing network enabled applications on a raspberry pi I have connected via ethernet to my wifi router. In these situations I have to interface with my pi via ssh, download the application from somewhere like github, and then run it manually. That gets awfully annoying to set up and manage. I want to create a task scheduler that can work in place of SSH which can take a yaml file to configure a job on the raspberry pi, and retrieve its information to return it to me working somewhere else. 
