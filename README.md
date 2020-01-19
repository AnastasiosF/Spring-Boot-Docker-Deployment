# Spring Boot Docker Deployment

### Run
1. Create a folder and put all the files inside of it
2. `cd` inside the folder
3. Change the gym.jar with your own `jar file`
4. Replace in `Dockerfile` the `gym.jar` with your own `jar file` name 
5. `docker build -t <your own tag> . `

### Info
Inside spring `application.properties` you have to set the IP Address of 
host machine. Don't put `localhost` as an IP Address !!! 
