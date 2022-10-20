# Minecraft Server Setup

## Introduction

Hi! My name is Pedro and I'm from Portugal. This repository helps you to easly setup (step by step) a **Minecraft Server** from starting the server locally to "publishing" it online (using **Cloudflare**) for your friends to join and play. 


## [STEP 1] Clone or download the repository

To clone the project with **git** just follow the steps shown in the image below, or just **download the .zip file** of the repository.

 ![GitClone](help\gitclone.png)

## [STEP 2] Download JAVA

You will need to download the version of Java **compatible** with the Minecraft's version you want your server to run (you can easily find the right one in the Internet). If you wanna run the latest version, you can download it [here](https://www.oracle.com/java/technologies/downloads/).

## [STEP 3] Server setup (local)

After you cloned/downloaded the repository, you wanna download [the latest version](https://www.minecraft.net/en-us/download/server) (or a specific version with mods or not) of the **.jar file** of the server and name it **"server.jar"** (the version from the one present in repository is 1.19.2).
After that you will run the file **start_server.bat** (by clicking it) and wait until you see the following error:

 ![EULA_Error](help\error_eula.png)

To solve this you gonna have to edit the generated file **eula.txt** and change the code ``eula=false`` to ``eula=true``, and then run it again.

 ![Setup_local](help\setup_local.png)

Now your server is running locally in your machine. To stop the server just type "stop" in the command-line.
Now let's run the server **online**.

## [STEP 3] Pick a domain and add it to Cloudflare

You will need to get a domain for your server. You can pick one **FREE** at [Freenom](https://www.freenom.com/en/index.html).
Then, you will need to [create an account](https://dash.cloudflare.com/sign-up) at **Cloudflare**, or [login](https://dash.cloudflare.com/login) if you have already one.

 ![Domain](help\pick_domain.png)

For further steps watch [this video](https://www.youtube.com/watch?v=1HMHTQhuV9w) to help you out.

## [STEP 4] Add your server and Play :D

For the final step you will just need to add your server in Minecraft by specifing your domain you just created.

 ![Multiplayer](help\multiplayer.png)
 
 ![Add_server](help\add_server.png)
 
 ![Server_info](help\server_info.png)
 
Enjoy your server! Hope this helped you :)