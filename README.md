# wordpress-docker
Enhanced ready-to-go wordpress instance. Install latest MySQL phpAdmin and Wordpress as Docker Containers

## Step 1

Install Docker Desktop

https://www.docker.com/products/docker-desktop/

## Step 2

Install WSL2 for Windows 

https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi

## Step 3

Run Docker Dekstop

## Step 4

Download the docker-compose.yaml file and save it in an empty Folder.

## Step 5

Open the docker-compose.yaml file in VS Code. Open a PowerShell Terminal in VS Code and type:

cd "/path/to/your/docker-compose.yaml"
docker compose up

## Step 6

Wait till the Docker Containers are Up you can verify in 'Docker Desktop' under 'Containers'. 
![Wordpress to go](https://user-images.githubusercontent.com/44142520/200366968-e8c9c4ff-728c-4c1a-8e5a-098e767287f3.png)

## Step 7

localhost:8000 is for wordpress
localhost:8080 is for phpAdmin

## Step 8

Enjoy :)!


