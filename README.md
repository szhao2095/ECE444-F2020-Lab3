# ECE444-F2020-Lab4&5
[dock]: images/Docker_VS_VM.png "Docker vs VM"
[dock1]: images/dockerstep1.png "Folder screenshot"
[dock2]: images/dockerstep2.png "Docker build command"
[dock3]: images/dockerstep3.png "Docker run command and container instance"
[dock4]: images/dockerstep4.png "Chrome screenshot"
[dock5]: images/dockerstep5.png "Docker image id"
[dock6]: images/dockerstep6.png "Docker desktop screenshot"


# Activity 1
This is a branch of ECE444-F2020-Lab3:lab4_Microservice_Experiment

# Activity 2
To create a docker image of this repo, first clone it into your local file directory and navigate to it.
![alt text][dock1]

Build the docker image with the following command (all relevant docker commands can be found in docker_commands.txt)
docker build -t ece444-f2020-lab3 .
![alt text][dock2]

Start the docker image with the following command,
docker run -d -p 5000:5000 ece444-f2020-lab3
![alt text][dock3]
You can verify that it is up by typing docker container ls -a and verifying that the STATUS shows Up X minutes.

Screenshot of the working site at localhost:5000
![alt text][dock4]

More verification of the image and running container instance
![alt text][dock5]
![alt text][dock6]


# Activity 3
**Briefly summarize the differences between Docker and Virtual Machine.**
![alt text][dock]
Credit https://www.youtube.com/watch?v=TvnZTi_gaNc

Docker and VMs are abstraction of different levels. Virtual machines isolates systems by giving each running OS/image it's own hardware resources such as CPU and memory. Docker allows it's own images to run on the same OS thus essentially only isolating the applications. Docker is more efficient with resources since it does not have to allocate resources that may otherwise be under utilized.


# ECE444-F2020-Lab3
Flask - "Simple web form"

This is a clone of: https://github.com/miguelgrinberg/flasky

[act1ss]: images/Activity1.png "Activity 1 screenshot"
[act2ss1]: images/Activity2_1.png "Activity 2 screenshot 1"
[act2ss2]: images/Activity2_2.png "Activity 2 screenshot 2"
[act2ss3]: images/Activity2_3.png "Activity 2 screenshot 3"
[act2ss4]: images/Activity2_4.png "Activity 2 screenshot 4"

# Activity 1
![alt text][act1ss]

# Activity 2
![alt text][act2ss1]
![alt text][act2ss2]
![alt text][act2ss3]
![alt text][act2ss4]

# Activity 3
**Briefly summarize the difference between SQL or NoSQL database.**

SQL databases are relational and uses tables with a variable number of rows and a fixed number of columns that have to be 
defined on the creation of the table. The tables and columns model the data of the kind of object to be stored. SQL databases
focuses on storing the data efficiently and avoiding duplication.

NoSQL databases are instead document-oriented and key-value databases which has an advantage in querying speed at the expense of 
duplicate entries.

https://www.xplenty.com/blog/the-sql-vs-nosql-difference/#:~:text=SQL%20databases%20are%20vertically%20scalable,data%20like%20documents%20or%20JSON.


