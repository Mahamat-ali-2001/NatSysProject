# Net&Sys Assignment: Running Containers for Application Development

Group Name: __AL-NUJUM__. 

Team Mates:
1. __MAHAMAT ALI ADAM__ and __2129455__
2. __ZUMMON MD ASADUZZAMAN__ and __2213853__
3. __FARUQ MD OMAR__ and __2134787__

## Rules
1. You are allowed to have **3 group** members..
2. When you complete the assignment, make sure to submit the repository link of your cloned project. Make sure all the files are as what you aspect in your repository. 
3. Answer all questions in the **README.md**, in your own repository. Either use the online VSCode, terminal or github to edit. Answers are expected where you see __Fill answer here__.
4. Learn how to use markdown. https://www.w3schools.io/file/markdown-introduction/

## Forking this project repository
1. First thing you need in doing this assignment is to have a github account. Make sure to sign up at https://www.github.com
2. The second thing you need is to fork the Net&Sys Assignment repository in your own github account. 

    1. Go to https://github.com/ZainabBashi/NatSysProject and click fork to copy the project into your own repository
    2. Make sure that the new fork is now in your own repository

***Questions:***

1. What is the link of the fork Net&Sys Assignment in your repository. ***(1 mark)*** __https://github.com/Mahamat-ali-2001/NatSysProject__.
2. How many files and folders are in this repository. ***(1 mark)*** __We have 1 file(README.md) and 1 folder(images)__.


## Exploring github codespaces

1. The next thing that we will be doing is exploring codespaces. First of all, read about codespaces https://docs.github.com/en/codespaces/overview#what-is-a-codespace
2. Then go to the link https://github.com/codespaces and we shall start a new codespace.  
3. Click on ***New codespace***.
4. Choose your own Net&Sys Assignment repository to start your codespace.

 <img src="./images/newcodespace.png" width="50%">

5. Once you have created you codespace, you will see the following. You might already be familiar with this, since it will look similar to VSCode. 

 <img src="./images/UIwebvscode.png" width="70%">

6. You will see the [README file](./README.md) file. One is a preview of how it looks like on the web, and the other is the editing view in markdown language. 
7. Edit the [README file](./README.md). Make sure you have your group details correct, ie, group name and team members along with their matric Numbers. 
8. Once you have finish editing, click File->Save or ***ctrl-s*** to save it. 
9. After saving, you will notice an M or U next to your file. You will need to commit any changes, whenever you make changes so that it is uploaded to the github repository. 

 <img src="./images/SourceControlUI.png" width="70%">

10. Click on the source control, hint: its on the left side panel, and it will list down the files that have been modified or updated. Click on commit. It will then ask you "Would you like to stage all your changes and commit them directly?" Just say yes, and a new tab will appear. Type a message to log what you have done, and click on the check mark. 

 <img src="./images/CommittingUI.png" width="70%">

11. After that, sync the changes to the main repository. 
12. Make sure to commit and sync your files to the main repository, or else, your work will be lost since it is not saved into the main repository when you submit your project.

***Questions:***

1. What is default OS used to run the virtual environment for codespaces. ***(1 mark)*** __The default OS used to run the virtual environment for Codespaces is Ubuntu__.
2. What are the two options of RAM, disk and vcpu configuration you can have in running codespaces . ***(1 mark)*** __Codespaces offers two configuration options: a standard setup with 4 GB of RAM, 32 GB of disk space, and 2 vCPUs, and a premium setup with 8 GB of RAM, 64 GB of disk space, and 4 vCPUs__.
3. Why must we commit and sync our current work on source control? ***(1 mark)*** __Committing and syncing our current work on source control is crucial for maintaining version control, enabling effective collaboration, ensuring data backup, and keeping the project consistent across all team members' work__.

## Exploring the Terminal

1. Look at the TERMINAL tab. Explore and run commands according to the questions below. 
2. You can include your answers as images, or cut and paste the output here. If you are cutting and pasting your answers, wrap your answers in the codeblock clause in markdown. For example, if i run the command **whoami** the the output would look like the one below.
```bash
@joeynor ➜ /workspaces/OSProject (main) $ whoami 
codespace
```



***Questions:***

Look at the TERMINAL tab. Run the following commands and provide the output here. 

1. Run the command **pwd** . ***(1 mark)*** __![image](https://github.com/Mahamat-ali-2001/NatSysProject/assets/172935800/2ecffd44-3aba-411d-91f0-8cebbb6eb358)
__.
2. Run the command **cat /etc/passwd** . ***(1 mark)*** __![image](https://github.com/Mahamat-ali-2001/NatSysProject/assets/172935800/8b92371a-fb43-492c-bb11-ebd0bf716082)
__.
3. Run the command **df** . ***(1 mark)*** __![image](https://github.com/Mahamat-ali-2001/NatSysProject/assets/172935800/91fb2c22-2f24-4e6e-a27c-ff2594968fc0)
e__.
4. Run the command **du** . ***(1 mark)*** __![image](https://github.com/Mahamat-ali-2001/NatSysProject/assets/172935800/bc0192e2-e12e-49f2-b0e9-18b52d052c2f)
__.
5. Run the command **ls** . ***(1 mark)*** __![image](https://github.com/Mahamat-ali-2001/NatSysProject/assets/172935800/e257c576-327a-46d8-8462-23936ac0b6b0)
__.
6. Run the command **ls -asl** . ***(1 mark)*** __![image](https://github.com/Mahamat-ali-2001/NatSysProject/assets/172935800/e6182ed7-3730-42de-beb4-43f29519ffb9)
__.
7. Run the command **free -h** . ***(1 mark)*** __![image](https://github.com/Mahamat-ali-2001/NatSysProject/assets/172935800/5fec4887-79f3-4e4c-a143-2d3b6ae514fc)
__.
8. Run the command **cat /proc/cpuinfo** . ***(1 mark)*** __![image](https://github.com/Mahamat-ali-2001/NatSysProject/assets/172935800/d63dd3c9-35d1-4d86-8ec4-5ddaad813d75)
![image](https://github.com/Mahamat-ali-2001/NatSysProject/assets/172935800/387ed2bc-e2cc-49bc-b458-f003bb5a3a59)

__.
10. Run the command **top** and type **q** to quit. ***(1 mark)*** __![image](https://github.com/Mahamat-ali-2001/NatSysProject/assets/172935800/75fefd18-6983-45ce-bcee-c24f4eb90bfc)
__.
11. Run the command **uname -a**. ***(1 mark)*** __![image](https://github.com/Mahamat-ali-2001/NatSysProject/assets/172935800/758120bd-385c-4954-8204-ba606b74fa13)
__.
12. What is the available free memory in the system. ***(1 mark)*** __the available free memory in the system: 490Mi__.
13. What is the available disk space mounted on /workspace. ***(1 mark)*** __the available disk space mounted on /workspace: 5.9Gi__.
14. Name the version and hardware architecture of the linux Virtual environment. ***(1 mark)*** __the version and hardware architecture of the linux Virtual environment: Linux codespaces-c7127a 6.5.0-1021-azure #22~22.04.1-Ubuntu SMP__.
15. What is the difference between **ls** vs **ls -asl**. ***(1 mark)*** __The ls command lists files and directories in the current directory, showing basic information like filenames. In contrast, ls -asl provides a detailed listing that includes all files (including hidden ones), along with comprehensive information such as permissions, ownership, file sizes, and timestamps. It's particularly useful for gaining a complete view of directory contents and understanding file attributes at a glance.
__.
16. What is the TLB size of the Virtual CPU. ***(1 mark)*** __The TLB size of the Virtual CPU: 2560 4k pages__.
17. What is the CPU speed of the Virtual CPU. ***(1 mark)*** __The CPU speed of the Virtual CPU: 3142.202__.
18. What is the top running process that consumes the most CPU cycles. ***(1 mark)*** __The top running process that consumes the most CPU cycles: 34889 codespa+ __.

## Running your own container instance.

1. At the terminal, run a linux instance. By typing the following command. 
```
docker pull debian
docker run --detach -it debian
```
2. This will run the debian container. To check if the debian container is running, type
```bash
@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS         PORTS     NAMES
f65be1987f84   debian    "bash"    4 minutes ago   Up 4 minutes             romantic_jackson
```

3. Keep note of the name used by your container, this is usually given random names unless you specify your own name. Now run a bash command on the container. Make sure you use the name of your container instead of the one shown here. 
```bash
docker exec -i -t romantic_jackson /bin/bash
```

4. Create a file on the container. First you must make sure you are in the bash command prompt of the container. The container is new, and does not have any software other than the debian OS. To create a new file, you will need an editor installed. In the bash shell of the container, run the package manager apt-get to install nano text editor. 

```bash
root@f65be1987f84:~# apt-get update      

root@f65be1987f84:~# apt-get install nano

root@f65be1987f84:~# cd /root

root@f65be1987f84:~# nano helloworld.txt
```

5. Edit your helloworld.txt, create your messsage and save by typing ctrl-X. Once saved, explore using the container to see where the file is located. Then exit the shell, by typing **exit**.

6. Stop the container and run **docker ps -a**, and restart the container again. Is your file in the container still available?
```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker restart romantic_jackson
```

7. Stop the container and delete the container. What happened to your helloworld.txt?

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker rm romantic_jackson
```

***Questions:***

1. Are files in the container persistent. Why not?. ***(1 mark)*** __Files in the container are not persistent by default because containers are designed to be ephemeral, meaning they are temporary and stateless. When a container is deleted, all the data within the container's file system is lost unless volumes or bind mounts are used to store data outside the container's lifecycle. In this case, since no volumes were used, the helloworld.txt file is lost when the container is removed.__.
2. Can we run two, or three instances of debian linux? . ***(1 mark)*** __Yes, we can run multiple instances of Debian Linux. Docker allows us to run multiple containers simultaneously from the same or different images. Each container runs in its own isolated environment, so we can have multiple instances of Debian running concurrently by simply using the docker run command multiple times. Each instance will have its own unique container ID and can be managed independently.__.

## Running your own container with persistent storage

1. In the previous experiment, you might have notice that containers are not persistent. To make storage persistent, you will need to mount them. 
At the terminal, create a new directory called **myroot**, and run a instance of debian linux and mount myroot to the container. Find out the exact path of my root, and mount it as the root folder in the debian container. 
2. Create a file in /root on the container, the files should also appear in myroot of your host VM.

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ mkdir myroot
@joeynor ➜ /workspaces/OSProject (main) $ cd myroot/
@joeynor ➜ /workspaces/OSProject/myroot (main) $ pwd
/workspaces/OSProject/myroot

@joeynor ➜ /workspaces/OSProject/myroot (main) $ docker run --detach -it -v /workspaces/OSProject/myroot:/root debian
```

***Questions:***

1. Check the permissionof the files created in myroot, what user and group is the files created in docker container on the host virtual machine? . __(2 mark)__ __files created in docker container on the host virtual machine will have ownership set to the root user and root group__.
2. @Mahamat-ali-2001 ➜ /workspaces/NatSysProject/myroot/myroot (main) $ cd /workspaces/NatSysProject  # Change to the parent directory of myroot
@Mahamat-ali-2001 ➜ /workspaces/NatSysProject (main) $ sudo chown -R codespace:codespace myroot
@Mahamat-ali-2001 ➜ /workspaces/NatSysProject (main) $ 
```bash
//use sudo and chown
sudo chown -R codespace:codespace myroot

```
*** __Yes, I have successfully changed the ownership and permissions of the files within /workspaces/NatSysProject/myroot to the codespace user.__.***

## You are on your own, create your own static webpage

1. Create a directory called webpage in your host machine
2. Inside the directory, create a page index.html, with any content you would like
3. Then, run the apache webserver and mount the webpage directory to it. Hint:
```bash
## the -p 8080:80 flag points the host port 8080 to the container port 80

docker run --detach -v /workspaces/OSProject/webpage:/usr/local/apache2/htdocs/ -p 8080:80 httpd
```

4. If it works, codespace will trigger a port assignment and provide a URL for you to access your webpage like the one below.

 <img src="./images/websitelink.png" width="70%">


5. You can also see the Port in the **PORTS** tab, next to the terminal tab.

6. You can then access your website by adding an index.html towards the end of your url link, like the one below. 

 <img src="./images/helloworldweb.png" width="70%">

***Questions:***

1. What is the permission of folder /usr/local/apache/htdocs and what user and group owns the folder? . ***(2 mark)*** __Permissions: -rw-r--r--
User: UID 1000
Group: GID 1000__.
2. What port is the apache web server running. ***(1 mark)*** __Port Apache Web Server is Running On: Port 80 inside the Docker container.__
3. What port is open for http protocol on the host machine? ***(1 mark)*** __Open Port for HTTP Protocol on Host Machine: Port 8080 is open for HTTP on your host machine.__

## Create SUB Networks

1. In docker, you can create your own private networks where you can run multiple services, in this part, we will create two networks, one called bluenet and the other is rednet
2. Run the docker create network to create you networks like the ones below
```bash
## STEP 1:
## Create Networks ##
docker network create bluenet
docker network create rednet`

## STEP 2: (automatically running)
## Create (1) Container in background called "c1" running busybox image ##
docker run -itd --net bluenet --name c1 busybox sh
docker run -itd --net rednet --name c2 busybox sh
```
***Questions:***

1. Describe what is busybox and what is command switch **--name** is for? . ***(2 mark)*** __Busybox: BusyBox is a single executable that provides simplified versions of many standard Unix utilities. It is designed for environments with limited resources                                              --name switch: This switch allows you to specify a custom name for the container. It's useful because it provides a human-readable and identifiable name instead of relying on container IDs.__. 
2. Explore the network using the command ```docker network ls```, show the output of your terminal. ***(1 mark)*** __![image](https://github.com/Mahamat-ali-2001/NatSysProject/assets/172935800/4bfe88fd-cd4e-4017-a8fc-5de662f0d99c)
__ 
3. Using ```docker inspect c1``` and ```docker inspect c2``` inscpect the two network. What is the gateway of bluenet and rednet.? ***(1 mark)*** __The gateway of bluenet:172.18.0.1                        The gateway of bluenet:172.19.0.1__                                                                                                                                                                            __![image](https://github.com/Mahamat-ali-2001/NatSysProject/assets/172935800/d4fdd7d7-74f5-4709-a5b7-e83f99a15d4a)
__
4. What is the network address for running container c1 and c2. __![image](https://github.com/Mahamat-ali-2001/NatSysProject/assets/172935800/bbae9cf5-226c-402c-868d-9fe5ee68d8a7)__
__for running container c1:172.18.0.2 , for running container c2:172.19.0.2__                                                                                                      
6. Using the command ```docker exec c1 ping c2```, which basically issue a ping from container c1 to c2. Are you able to ping? Show your output . ***(1 mark)*** __![image](https://github.com/Mahamat-ali-2001/NatSysProject/assets/172935800/8a401302-4c94-4465-aa01-0b72f173730f)
__

## Bridging two SUB Networks
1. Let's try this again by creating a network to bridge the two containers in the two subnetworks
```
docker network create bridgenet
docker network connect bridgenet c1
docker network connect bridgenet c2
docker exec c1 ping c2  __![image](https://github.com/Mahamat-ali-2001/NatSysProject/assets/172935800/1d7e9f88-0230-4ef9-ac54-1d175fe8568c)
__
```

## What to submit

1. Make sure to commit all changes on your source control, and make sure your source control is sync to the repository. 
2. Check your repository link, to see if all the files and answers are included in the repository. 
3. Submit through italeem, by providing the link to your repository.
4. Due by ***30 May, 2024***
