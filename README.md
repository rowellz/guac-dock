# guac-dock

guac-dock is a containerized instance of the apache based vnc/ssh client software running in a docker-compose environment.
Once running, you can access the application at localhost:8088/guacamole. 
## Getting Started

### Clone the Repository
```sh
git clone https://github.com/yourusername/guac-dock.git
cd guac-dock
```

### Run the Shell Script
```sh
./prepare.sh
```

### Start the Docker Containers
```sh
docker-compose up
```

### Restarting
Remove the directories generated from running the previous commands, all which can also be found in the .gitignore. Once removed, rerun the shell & docker scripts. 