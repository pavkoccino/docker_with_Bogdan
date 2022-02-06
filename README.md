# Docker: The Complete Practical Guide by Bogdan Stashchuk
Following Docker: The Complete Practical Guide by Bogdan Stashchuk

### Docker installation on WIN
- Just follow the installation process of the Docker desktop.
- I was installing Docker Desktop.

### Docker notes
- If there are no processes run inside the container, Docker automatically stops the container.
- Busybox image - really small linux image with large set of utilities. For example Ubuntu image has around 64 MB where babybox has 1.22 MB.

### Docker commands
```
docker --list
docker --help
docker run hello-world //Tries to run contained with image hello-world, since it won't find it, it will automatically pull it from docker hub and run it
docker ps //List of running containers
docker ps -a //History of container runs, alternatively I can use docker container ls -a
docker images //List of local images
docker run -it ubuntu //Keeps the container alive and I can work inside it
```


### CMD commands
```
cls //clears the terminal
```

### Linux commands
```
CTRL + L //clears the terminal
ls //listing folders
ls bin //listing folders inside bin
cat /etc/os-release //reads the item and prints it to the standart output
hostname
hostname -i
echo "Hello"
exit
mkdir my-folder
cd directory
touch file.txt
```
