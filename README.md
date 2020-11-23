# CS1660 Project Option 1

Pre-Reqs

1. Able to run Docker Desktop on your computer as an administrator, Linux containers
2. At least 50GB of space on your C drive

Steps 
1. Pull the zip file
2. Extract it into one folder
2. Start docker deamon as admin
3. Ensure your drive C is shared in the Docker settings
4. Run 'docker ps' to make sure there are no running containers. (This is to ensure there are no port conflicts)
5. Run 'docker-compose up --build' to build up all the containers This will take some time, until all the dependencies are sorted
6. Launch a web browser, and navigate to 'http://127.0.0.1:80'
7. Please note some of the applications might require you to enter a password or token. This is often a baked-in security feature to ensure authentification.
8. Follow the clear, on-screen instructions to find your token.

From the webpage, you can be able to seamlessly navigate to various other microservice modules. 

To shut down all the containers:
Run 'docker-compose down --volumes'

To list all currently active containers
Run 'docker-compose ps'

To halt the running of the currently active containers
Run 'docker-compose stop'
