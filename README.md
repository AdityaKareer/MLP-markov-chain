# MLP-markov-chain

DON BOSCO INSTITUTE OF TECHNOLOGY
Department of Information and Technology
Course: ITL503
INDEX
Sr. No. Name Date PgNo.
A Self Study 11/7/23
1 & 2 Git installation and versioning 25/7/23
3
Jenkins installation
JDK connectivity
Java & Python programming
08/8/23
Parameterized
Pipeline
Shell Scripting
29/8/23
Maven Project 5/9/23
4 Assignment 1:
CI/CD
Implementation of login Id & password using
Jenkins pipeline
Mini project ISO file creation using Docker
Hosting of mini project ISO file on DockerHub
29/8/23-
12/9/23
5 Docker Installation and Basic commands 12/09/23
6 Assignment 2:
Installation and demonstration of Ansible
12/09/23 -
24/09/23
EXPERIMENT A : SELF STUDY
1. What is devops?
DevOps is a software development approach that combines development (Dev) and
operations (Ops) teams to improve collaboration, communication, and efficiency
throughout the software development lifecycle. It aims to automate processes, eliminate
silos, and foster a culture of continuous integration, delivery, and deployment. DevOps
practices involve using tools, such as version control, continuous integration, and
containerization, to streamline development, testing, and deployment processes. By
adopting DevOps, organizations can achieve faster time to market, improved software
quality, and increased customer satisfaction.
2. List down the stages of development & operations.
The stages of development and operations in the software development lifecycle can
vary depending on the specific methodology or framework being followed. However,
here are the commonly recognized stages:
a) Planning: This phase involves defining project objectives, requirements gathering,
and creating a roadmap for development and operations.
b) Development: In this stage, developers write and test code, design software
architecture, and build the application or system according to the requirements.
c) Continuous Integration: This phase involves integrating code changes frequently and
automatically to ensure that the software remains stable and functional.
d) Testing: Quality assurance engineers perform various types of testing, including unit
testing, integration testing, system testing, and acceptance testing, to identify and fix
bugs and ensure software reliability.
e) Deployment: This stage involves deploying the software to production servers or
cloud environments, making it available for users.
f) Operations: Once the software is deployed, operations teams monitor and manage the
system, ensuring its availability, performance, and scalability. They also handle user
support and perform maintenance tasks.
g) Continuous Delivery/Deployment: Organizations that adopt continuous delivery or
continuous deployment practices automate the process of releasing new features or
updates to the software, allowing for faster and more frequent releases.
h) Monitoring and Feedback: This stage involves monitoring the software's
performance, collecting user feedback, and making improvements based on the
feedback and monitoring data.
3. For every stage of devops. Mention at least two tools and a line detail about each
tool.
Here are two commonly used tools for each stage of the DevOps process:
1. Planning:
Jira: Jira is a widely used project management tool that helps teams plan, track,
and manage software development projects. It provides features such as issue tracking,
task management, and agile project management.
Trello: Trello is a visual collaboration tool that allows teams to organize and
prioritize tasks using boards, lists, and cards. It provides a simple and intuitive interface
for managing projects and tasks.
2. Development:
- Git: Git is a distributed version control system that allows developers to track
changes in their codebase, collaborate with others, and manage different versions of their
software. It provides features like branching, merging, and conflict resolution.
- Bitbucket: Bitbucket is a web-based version control repository hosting service
that supports both Git and Mercurial. It provides features like code collaboration, pull
requests, and continuous integration.
3. Continuous Integration:
- Jenkins: Jenkins is an open-source automation server that facilitates continuous
integration and delivery of software projects. It allows developers to automate the build,
test, and deployment process, ensuring that code changes are integrated smoothly.
- CircleCI: CircleCI is a cloud-based continuous integration and delivery platform
that automates software builds, tests, and deployment. It provides a scalable and
customizable environment for running CI/CD pipelines.
4. Testing:
- Selenium: Selenium is a popular open-source framework for automating web
browsers. It allows developers to write tests in various programming languages to verify
the functionality of web applications across different browsers and platforms.
- JUnit: JUnit is a unit testing framework for Java. It provides a simple and
flexible way to write and run tests for Java applications, ensuring that each unit of code
behaves as expected.
5. Deployment:
- Docker: Docker is an open-source platform that allows developers to automate
the deployment of applications inside lightweight, portable containers. It provides an
efficient and consistent environment for running applications across different systems.
- Kubernetes: Kubernetes is an open-source container orchestration platform that
automates the deployment, scaling, and management of containerized applications. It
provides features like load balancing, service discovery, and self-healing capabilities.
6. Operations:
- Nagios: Nagios is a powerful monitoring and alerting tool that helps IT teams
monitor the health and performance of their infrastructure, servers, and network devices.
It provides real-time monitoring, notifications, and reporting capabilities.
- Zabbix: Zabbix is an open-source monitoring software that allows organizations
to monitor and track the performance and availability of their IT infrastructure. It offers
features such as network monitoring, server monitoring, and application monitoring.
7. Continuous Delivery/Deployment:
- AWS CodePipeline: AWS CodePipeline is a fully managed continuous delivery
service that helps teams automate their software release process. It allows developers to
build, test, and deploy applications using various AWS services.
- GitLab CI/CD: GitLab CI/CD is a built-in continuous integration and continuous
deployment tool provided by GitLab. It enables developers to automate the entire
software development lifecycle, from code commit to production deployment.
8. Monitoring and Feedback:
- New Relic: New Relic is a monitoring and observability platform that provides
real-time insights into the performance and health of applications, infrastructure, and
customer experiences. It helps teams identify and resolve issues before they impact
end-users.
- Grafana: Grafana is an open-source data visualization and monitoring tool that
allows teams to create interactive dashboards and graphs to analyze and monitor metrics
from various data sources. It provides a flexible and customizable interface for
visualizing data.
4. What do you mean by version control or versioning?
Version control, also known as versioning or source control, is a system or process used
in software development to manage changes to source code, documents, or any other type
of files over time. It provides a way to track and organize modifications, additions, and
deletions made to files, allowing multiple people to collaborate on a project while
keeping track of the history of changes.
The primary goals of version control are:
1. Collaboration: Version control enables multiple developers to work on the
same codebase simultaneously without interfering with each other's work. Changes can
be integrated and merged together.
2. History and Tracking: Version control systems maintain a detailed history of all
changes made to files, including who made the changes, when they were made, and what
specific modifications were performed. This historical information is invaluable for
understanding the evolution of a project and for troubleshooting issues.
3. Reproducibility: Version control allows you to recreate the state of a project at any
point in its history. This is crucial for reproducing specific versions of software or
documents, which can be important for debugging or maintaining compatibility.
4. Backup and Recovery: Version control serves as a form of backup by storing
previous versions of files. This can be useful for recovering lost or mistakenly deleted
work.
5. Branching and Merging: Version control systems provide the ability to create
separate branches of the codebase, which allows developers to work on different features
or fixes independently. Branches can later be merged back together, combining the
changes made in each branch.
Version control systems can be categorized into two main types: centralized and
distributed.
• Centralized Version Control: In a centralized system, there is a single, central
repository that stores all versions of files. Developers check out files from this repository,
make changes, and then check them back in. Examples of centralized version control
systems include Subversion (SVN) and Perforce.
• Distributed Version Control: In a distributed system, each developer has their own
local copy of the entire repository, including the complete history. Developers can work
independently, commit changes to their local copy, and then share those changes with
others by pushing them to a shared remote repository. Examples of distributed version
control systems include Git and Mercurial.
5. What is a microservice & lightweight , monolithic server.
Microservices and monolithic architectures are two different approaches to designing and
structuring software applications. The terms "lightweight" and "monolithic server" can
also be used in the context of these architectural styles. Let's break down each concept:
1. Microservices: Microservices architecture is an approach to building applications as
a collection of small, loosely coupled services that can be developed, deployed, and
scaled independently. Each microservice is responsible for a specific, well-defined
functionality of the application. These services communicate with each other through
well-defined APIs (often over HTTP/REST or message queues).
Advantages of microservices include:
• Scalability: Each microservice can be scaled independently based on demand.
• Flexibility: Different services can be developed using different technologies or
programming languages.
• Ease of Maintenance: Changes or updates to one microservice have minimal impact
on others.
• Resilience: Failures in one microservice do not necessarily affect the entire
application.
• Team Autonomy: Different teams can work on different microservices concurrently.
Challenges of microservices include:
• Complexity: Managing a distributed system can be complex, especially in terms of
communication and data consistency.
• Deployment and Monitoring: Managing multiple services and their deployments can
be challenging.
• Testing: End-to-end testing can be more complicated due to the distributed nature of
the architecture.
2. Monolithic Architecture: In a monolithic architecture, an application is built as a
single, self-contained unit. All the components and functionality of the application are
tightly integrated into a single codebase. This approach was common in traditional
software development.
Advantages of monolithic architecture include:
• Simplicity: Easier development and testing due to the centralized nature of the
application.
• Deployment: Deploying a monolithic application is relatively straightforward.
Challenges of monolithic architecture include:
• Scalability: Scaling the application as a whole can be more challenging, as all
components are interconnected.
• Flexibility: Making changes to one part of the application can impact the entire
system.
• Maintenance: As the application grows, it can become harder to manage and
maintain.
3. Lightweight Monolithic Server: The term "lightweight monolithic server" is not a
standard architectural concept but can refer to a monolithic application that is designed to
be efficient and lightweight in terms of its resource usage and performance. This might
involve optimizing code, minimizing dependencies, and focusing on efficient data
processing
EXPERIMENT 1 & 2
Git installation and versioning
Aim: To install git (local repository) and synchronize with github (remote repository) and
perform version controlling.
Steps for installation and version control:
git config
Usage: git config –global user.name “[name]”
Usage: git config –global user.email “[email address]”
This command sets the author name and email address respectively to be
used with your commits.
git init
Usage: git init [repository name]
This command is used to start a new repository.
git clone
Usage: git clone [url]
This command is used to obtain a repository from an existing URL.
git add
Usage: git add [file]
This command adds a file to the staging area.
Usage: git add *
This command adds one or more to the staging area.
git commit
Usage: git commit -m “[ Type in the commit message]”
This command records or snapshots the file permanently in the version
history.
Usage: git commit -a
This command commits any files you’ve added with the git add command
and also commits any files you’ve changed since then.
git diff
Usage: git diff
This command shows the file differences which are not yet staged.
Usage: git diff –staged
This command shows the differences between the files in the staging area
and the latest version is present.
Usage: git diff [first branch] [second branch]
This command shows the differences between the two branches
mentioned.
git reset
Usage: git reset [file]
This command unstages the file, but it preserves the file contents.
Usage: git reset [commit]
This command undoes all the commits after the specified commit and
preserves the changes locally.
Usage: git reset –hard [commit] This command discards all history and
goes back to the specified commit.
git status
Usage: git status
This command lists all the files that have to be committed.
git rm
Usage: git rm [file]
This command deletes the file from your working directory and stages the
deletion.
git log
Usage: git log
This command is used to list the version history for the current branch.
Usage: git log –follow[file]
This command lists version history for a file, including the renaming of files
also.
git show
Usage: git show [commit]
This command shows the metadata and content changes of the specified
commit.
git tag
Usage: git tag [commitID]
This command is used to give tags to the specific commit.
git branch
Usage: git branch
This command lists all the local branches in the current repository.
Usage: git branch [branch name]
This command creates a new branch.
Usage: git branch -d [branch name]
This command deletes the feature branch.
git checkout
Usage: git checkout [branch name]
This command is used to switch from one branch to another.
Usage: git checkout -b [branch name]
This command creates a new branch and also switches to it.
git merge
Usage: git merge [branch name]
This command merges the specified branch’s history into the current
branch.
git remote
Usage: git remote add [variable name] [Remote Server Link]
This command is used to connect your local repository to the remote
server.
git push
Usage: git push [variable name] master
This command sends the committed changes of master branch to your
remote repository.
Usage: git push [variable name] [branch]
This command sends the branch commits to your remote repository.
Usage: git push –all [variable name]
This command pushes all branches to your remote repository.
Usage: git push [variable name] :[branch name]
This command deletes a branch on your remote repository.
git pull
Usage: git pull [Repository Link]
This command fetches and merges changes on the remote server to your
working directory.
git stash
Usage: git stash save
This command temporarily stores all the modified tracked files.
Usage: git stash pop
This command restores the most recently stashed files.
Usage: git stash list
This command lists all stashed changesets.
Usage: git stash drop
This command discards the most recently stash009564ed changeset.
Get Token
1. Log into GitHub.
2. Click on your name / Avatar in the upper right corner and select Settings.
3. On the left, click Developer settings.
4. Select Personal access tokens and click Generate new token.
5. Give the token a description/name and select the scope of the token. ...
6. Click Generate token.
7. This configures the computer to remember the complex token by enable caching of
the credentials.
git config --global credential.helper cache
8. If needed, you can later clear the token from the local computer by running
git config --global --unset credential.helper
Once GIT is configured,
git config --global user.name &quot;&quot;
git config --global user.email &quot;&quot;
git config -l
we can begin using it to access GitHub. In this example I perform a git
clone command to copy a repository to the local computer. When prompted for the
username and password, enter your GitHub username and the previously
generated token as the password.
Git clone url
Conclusion: Successfully performed and installed git commands and version control.
References:
https://www.digitalocean.com/community/tutorials/how-to-install-git-on-ubuntu-22-04
EXPERIMENT 3
Installation of Jenkins and to perform CI/CD
Aim: Installation of Jenkins and to perform Continuous Integration/Continuous Development
Steps for installation:
Step 1 — Installing Jenkins
The version of Jenkins included with the default Ubuntu packages is often behind the latest
available version from the project itself. To ensure you have the latest fixes and features, use the
project-maintained packages to install Jenkins.
First, add the repository key to your system:
wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key |sudo gpg --dearmor -o
/usr/share/keyrings/jenkins.gpg
The gpg --dearmor command is used to convert the key into a format that apt recognizes.
Next, let’s append the Debian package repository address to the server’s sources.list:
sudo sh -c 'echo deb [signed-by=/usr/share/keyrings/jenkins.gpg]
http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'
The [signed-by=/usr/share/keyrings/jenkins.gpg] portion of the line ensures that apt will verify
files in the repository using the GPG key that you just downloaded.
After both commands have been entered, run apt update so that apt will use the new repository.
sudo apt update
Finally, install Jenkins and its dependencies:
sudo apt install jenkins
Now that Jenkins and its dependencies are in place, we’ll start the Jenkins server.
Step 2 — Starting Jenkins
now that Jenkins is installed, start it by using systemctl:
sudo systemctl start jenkins.service
Since systemctl doesn’t display status output, we’ll use the status command to verify that Jenkins
started successfully:
sudo systemctl status jenkins
If everything went well, the beginning of the status output shows that the service is active and
configured to start at boot:
Output
● jenkins.service - Jenkins Continuous Integration Server
Loaded: loaded (/lib/systemd/system/jenkins.service; enabled; vendor preset: enabled)
Active: active (running) since Mon 2022-04-18 16:07:28 UTC; 2min 3s ago
Main PID: 88180 (java)
Tasks: 42 (limit: 4665)
Memory: 1.1G
CPU: 46.997s
CGroup: /system.slice/jenkins.service
└─88180 /usr/bin/java -Djava.awt.headless=true -jar /usr/share/java/jenkins.war
--webroot=/var/cache/jenkins/war --httpPort=8080
Now that Jenkins is up and running, adjust your firewall rules so that you can reach it from a web
browser to complete the initial setup.
Step 3 — Opening the Firewall
To set up a UFW firewall, visit Initial Server Setup with Ubuntu 22.04, Step 4- Setting up a
Basic Firewall. By default, Jenkins runs on port 8080. Open that port using ufw:
sudo ufw allow 8080
Note: If the firewall is inactive, the following commands will allow OpenSSH and enable the
firewall:
sudo ufw allow OpenSSH
sudo ufw enable
Check ufw’s status to confirm the new rules:
sudo ufw status
You’ll notice that traffic is allowed to port 8080 from anywhere:
Output
Status: active
To Action From
-- ------ ----
OpenSSH ALLOW Anywhere
8080 ALLOW Anywhere
OpenSSH (v6) ALLOW Anywhere (v6)
8080 (v6) ALLOW Anywhere (v6)
With Jenkins installed and a firewall configured, you have completed the installation stage and
can continue with configuring Jenkins.
Step 4 — Setting Up Jenkins
To set up your installation, visit Jenkins on its default port, 8080, using your server domain name
or IP address: http://your_server_ip_or_domain:8080
You should receive the Unlock Jenkins screen, which displays the location of the initial
password:
In the terminal window, use the cat command to display the password:
sudo cat /var/lib/jenkins/secrets/initialAdminPassword
Copy the 32-character alphanumeric password from the terminal and paste it into the
Administrator password field, then click Continue.
The next screen presents the option of installing suggested plugins or selecting specific plugins:
We’ll click the Install suggested plugins option, which will immediately begin the installation
process.
When the installation is complete, you’ll be prompted to set up the first administrative user. It’s
possible to skip this step and continue as admin using the initial password from above, but we’ll
take a moment to create the user.
Note: The default Jenkins server is NOT encrypted, so the data submitted with this form is not
protected. Refer to How to Configure Jenkins with SSL Using an Nginx Reverse Proxy on
Ubuntu 22.04 to protect user credentials and information about builds that are transmitted via the
web interface.
Enter the name and password for your user:
You’ll receive an Instance Configuration page that will ask you to confirm the preferred URL
for your Jenkins instance. Confirm either the domain name for your server or your server’s IP
address:
After confirming the appropriate information, click Save and Finish. You’ll receive a
confirmation page confirming that “Jenkins is Ready!”:
Click Start using Jenkins to visit the main Jenkins dashboard:
At this point, you have completed a successful installation of Jenkins.
Conclusion: Successfully installed jenkins.
References:
https://www.digitalocean.com/community/tutorials/how-to-install-jenkins-on-ubuntu-22-04
Experiment 3:
Jenkin 2
Aim: To create shell script, pipeline and parameterized program in Jenkin
Steps to execute shell script using Jenkins: Terminal commands
nano commands
make a free style project and name it
go to build steps and select execute shell
enter the command to execute in shell and save
copy the path of the shell program to workspace
Steps for Jenkins CI/CD Pipeline:
Click on new item and create new pipeline
click ok ; and go to the advanced project options as shown in the below image
click on advanced dropdown and set the project display name
now go to the pipeline section ; choose pipeline script from the drop down ; now ,there will be a
small dropdown showing at the right side of the script editor ; select Hello world from that drop
down and save
now you will be in the dashboard of your pipeline
click build now from the sidebar available to the left ; wait for 1-2 minutes and your dashboard
will be updated like this
now our stage is deployed ; but that lets try some error in the script ; so first lets create some
error in the script that we wrote in the script editor ; click on configure on the left sidebar
now go the pipeline section ; purposely make error in the script so that we can come to now
about failure in the stage deployment ; sample of (script with error is given below); click on
save
now click on build now from sidebar ; you should get such output
So till now we have known stage deployment ; lets learn how to build a job using jenkins
pipeline click on configure from the sidebar ; and correct the error that we have made.
Now lets automate building of our freestyle project that we did in previous experiment my
jenkins dashboard looks like
now lets automate building of ‘exp3_first’ project
Note :- project name may differ ; copy your project name my project name was
‘exp3_first’ ; use your project name in the pipeline script
now click on your pipeline which is failed click on configure
go to the pipeline section ; edit script as below ; click on save
now click on build now from the sidebar
you will get similar type of output on your pipeline dashboard
Steps for Jenkins Parameterized Program:
Terminal commands: Create a shell script and give it execution permission.
#!/bin/bash
username=$1
password=$2
if [[ "$username" == "admin" && "$password" == "Dbit2023" ]]; then
echo "Hello $username"
else
echo "Invalid username or password"
fi
Now create a freestyle project and create 2 parameters: username and password.
Under build step select Execute shell and copy the path to your shell script and don't forget to
add parameters.
This is what the output would look like.
Conclusion: Successfully implemented shell script, pipeline and parameterized Jenkins program.
References:
https://www.youtube.com/watch?v=Rs-bTXQ8mjA
https://www.youtube.com/watch?v=AqITZLJ5eZ4
https://www.youtube.com/watch?v=I712r_Jtar4
Experiment 3:
Jenkin 3
Aim: To implement and execute Maven project
Procedure:
Step1: Check if Maven is available in the project style, if no install the plugin using
manage plugins -> plugin -> search for maven -> choose the button -> choose the item -> below
click on download and install and restart button -> installation will start -> wait for a while ->
once completed
Step 2: Add Maven configuration in Jenkins
Go to manage Jenkins -> Tools and add the maven configuration details shown below
Step 3: After installing the plugin, Maven project has been enabled to select as job type
● After creating the project, Click on build
● In build section, add the path of pom file
● Add the goal to be performed
Step 4: Click on save and build the project. You’ll see the output of build succeeded in console
output.
Conclusion: Successfully built a Maven project using Jenkins
References: https://www.youtube.com/watch?v=o2gAw929--g
Assignment 1
Aim: CI/CD
Implementation of login Id & password using Jenkins pipeline
Mini project ISO file creation using Docker
Hosting of mini project ISO file on DockerHub
Steps for Jenkins CI/CD Pipeline:
Click on new item and create new pipeline
click ok ; and go to the advanced project options as shown in the below image
click on advanced dropdown and set the project display name
now go to the pipeline section ; choose pipeline script from the drop down ; now ,there will be a
small dropdown showing at the right side of the script editor ; select Hello world from that drop
down and save
now you will be in the dashboard of your pipeline
click build now from the sidebar available to the left ; wait for 1-2 minutes and your dashboard
will be updated like this
now our stage is deployed ; but that lets try some error in the script ; so first lets create some
error in the script that we wrote in the script editor ; click on configure on the left sidebar
now go the pipeline section ; purposely make error in the script so that we can come to now
about failure in the stage deployment ; sample of (script with error is given below); click on
save
now click on build now from sidebar ; you should get such output
So till now we have known stage deployment ; lets learn how to build a job using jenkins
pipeline click on configure from the sidebar ; and correct the error that we have made.
Now lets automate building of our freestyle project that we did in previous experiment my
jenkins dashboard looks like
now lets automate building of ‘exp3_first’ project
Note :- project name may differ ; copy your project name my project name was
‘exp3_first’ ; use your project name in the pipeline script
now click on your pipeline which is failed click on configure
go to the pipeline section ; edit script as below ; click on save
now click on build now from the sidebar
you will get similar type of output on your pipeline dashboard
Steps for Mini project ISO file creation using Docker & hosting of mini project ISO file on
DockerHub
Step 1: Create a directory and add dockerfile in it
Step 2: Add the website files in the directory and following code in dockerfile
FROM httpd
COPY . /usr/local/apache2/htdocs
Step 3: Build the dockerfile into an ISO
docker build -t website .
docker images
Step 4: When you run this command, it will start a Docker container from the website image,
and you can access the website within the container by visiting http://localhost:1002 in your web
browser, assuming your Docker daemon is running on your local machine.
docker run -d -p 1002:80 website
docker ps -a
Step 5: This command tags the "website" image with a new name "dhruuvnaik5/website." If
there is a tag associated with the "website" image, it will also be inherited by the new image.
docker ps -a
docker image tag [image name] [username]/[repository name]
docker images
Step 6: Push the image onto DockerHub
docker push [username]/[repository name]
Step 7: Now you may stop the running containers
docker stop [containerId]
docker ps -a
Conclusion: Successfully implemented CI/CD pipeline in Jenkins and uploaded Mini Project
ISO file on DockerHub
References: https://www.youtube.com/watch?v=kbQeceF9RgA
Experiment 5:
Docker installation and basic commands
Prerequisite: Knowledge about Docker, DockerHub, Container and Virtual Machine
Aim: To install docker and practice basic commands
Steps for Installing Docker on Ubuntu:
1. Open the terminal on Ubuntu.
2. Remove any Docker files that are running in the system, using the following command:
$ sudo apt-get remove docker docker-engine docker.io
After entering the above command, you will need to enter the password of the root and press
enter.
3. Check if the system is up-to-date using the following command:
$ sudo apt-get update
4. Install Docker using the following command:
$ sudo apt install docker.io
You’ll then get a prompt asking you to choose between y/n - choose y
5. Install all the dependency packages using the following command:
$ sudo snap install docker
6. Before testing Docker, check the version installed using the following command:
$ docker --version
7. Pull an image from the Docker hub using the following command:
$ sudo docker run hello-world
Here, hello-world is the docker image present on the Docker hub.
8. Check if the docker image has been pulled and is present in your system using the following
command:
$ sudo docker images
9. To display all the containers pulled, use the following command:
$ sudo docker ps -a
10. To check for containers in a running state, use the following command:
$ sudo docker ps
You’ve just successfully installed Docker on Ubuntu!
Basic Commands:
1. docker –version
This command is used to get the current version of the docker
docker - -version [OPTIONS]
By default, this will render all version information in an easy-to-read layout.
2. docker pull
Pull an image or a repository from a registry
docker pull [OPTIONS] NAME[: TAG|@DIGEST]
To download an image or set of images (i.e. A Repository) , Once can use docker pull command
Example:
$ docker pull dockerimage
3. docker run
This command is used to create a container from an image
docker run [OPTIONS] IMAGE [COMMAND] [ARG...]
The docker run command creates a writeable container layer over the specified image and then
starts it using the specified command.
The docker run command can be used with many variations, One can refer to the following
documentation docker run.
4. docker ps
This command is used to list all the containers
docker ps [OPTIONS]
The above command can be used with other options like - all or –a
docker ps -all: Lists all containers
Example:
$ docker ps
$ docker ps -a
5. docker exec
This command is used to run a command in a running container
docker exec [OPTIONS] CONTAINER COMMAND [ARG...]
Docker exec command runs a new command in a running container.
Refer to the following article for more detail regarding the usage of the docker exec command
docker exec.
6. docker stop
This command is used to stop one or more running containers.
docker stop [OPTIONS] CONTAINER [CONTAINER...]
The main process inside the container will receive SIGTERM, and after a grace period,
SIGKILL. The first signal can be changed with the STOPSIGNAL instruction in the container’s
Dockerfile, or the --stop-signal option to docker run.
Example:
$ docker stop my_container
7. docker restart
This command is used to restart one or more containers.
docker restart [OPTIONS] CONTAINER [CONTAINER...]
Example:
$ docker restart my_container
8. docker kill
This command is used to kill one or more containers.
docker kill [OPTIONS] CONTAINER [CONTAINER...]
Example:
$ docker kill my_container
9. docker commit
This command is used to create a new image from the container image.
docker commit [OPTIONS] CONTAINER [REPOSITORY[:TAG]]
Docker commit command allows users to take an existing running container and save its current
state as an image
There are certain steps to be followed before running the command
● First , Pull the image from docker hub
● Deploy the container using the image id from first step
● Modify the container (Any changes ,if needed)
● Commit the changes
Example:
$ docker commit c3f279d17e0a dev/testimage:version3.
10. docker push
This command is used to push an image or repository to a registry.
docker push [OPTIONS] NAME[: TAG]
Use docker image push to share your images to the Docker Hub registry or to a self-hosted one.
Example:
$ docker image push registry-host:5000/myadmin/rhel-httpd:lates
Conclusion: Successfully installed Docker and pulled images
References:
https://www.simplilearn.com/tutorials/docker-tutorial/how-to-install-docker-on-ubuntu
https://www.knowledgehut.com/blog/devops/basic-docker-commands
https://hub.docker.com/
https://www.oreilly.com/member/login/
Assignment 2
Aim: Installation and demonstration of Ansible.
Prerequisites:
To follow this tutorial, you will need:
● One Ansible Control Node: The Ansible control node is the machine we’ll use to connect
to and control the Ansible hosts over SSH. Your Ansible control node can either be your
local machine or a server dedicated to running Ansible, though this guide assumes your
control node is an Ubuntu 20.04 system. Make sure the control node has:
● A non-root user with sudo privileges. To set this up, you can follow Steps 2 and 3
of our Initial Server Setup Guide for Ubuntu 20.04. However, please note that if
you’re using a remote server as your Ansible Control node, you should follow
every step of this guide. Doing so will configure a firewall on the server with ufw
and enable external access to your non-root user profile, both of which will help
keep the remote server secure.
● An SSH keypair associated with this user. To set this up, you can follow Step 1 of
our guide on How to Set Up SSH Keys on Ubuntu 20.04.
● One or more Ansible Hosts: An Ansible host is any machine that your Ansible control
node is configured to automate. This guide assumes your Ansible hosts are remote
Ubuntu 20.04 servers. Make sure each Ansible host has:
● The Ansible control node’s SSH public key added to the authorized_keys of a
system user. This user can be either root or a regular user with sudo privileges. To
set this up, you can follow Step 2 of How to Set Up SSH Keys on Ubuntu 20.04.
Step 1 — Installing Ansible:
To begin using Ansible as a means of managing your server infrastructure, you need to install the
Ansible software on the machine that will serve as the Ansible control node.
From your control node, run the following command to include the official project’s PPA
(personal package archive) in your system’s list of sources:
sudo apt-add-repository ppa:ansible/ansible
Press ENTER when prompted to accept the PPA addition.
Next, refresh your system’s package index so that it is aware of the packages available in the
newly included PPA:
sudo apt update
Following this update, you can install the Ansible software with:
sudo apt install ansible
Your Ansible control node now has all of the software required to administer your hosts. Next,
we will go over how to add your hosts to the control node’s inventory file so that it can control
them.
Step 2 — Setting Up the Inventory File:
The inventory file contains information about the hosts you’ll manage with Ansible. You can
include anywhere from one to several hundred servers in your inventory file, and hosts can be
organized into groups and subgroups. The inventory file is also often used to set variables that
will be valid only for specific hosts or groups, in order to be used within playbooks and
templates. Some variables can also affect the way a playbook is run, like the
ansible_python_interpreter variable that we’ll see in a moment.
To edit the contents of your default Ansible inventory, open the /etc/ansible/hosts file using your
text editor of choice, on your Ansible control node:
sudo nano /etc/ansible/hosts
Note: Although Ansible typically creates a default inventory file at etc/ansible/hosts, you are free
to create inventory files in any location that better suits your needs. In this case, you’ll need to
provide the path to your custom inventory file with the -i parameter when running Ansible
commands and playbooks. Using per-project inventory files is a good practice to minimize the
risk of running a playbook on the wrong group of servers.
The default inventory file provided by the Ansible installation contains a number of examples
that you can use as references for setting up your inventory. The following example defines a
group named [servers] with three different servers in it, each identified by a custom alias:
server1, server2, and server3. Be sure to replace the highlighted IPs with the IP addresses of your
Ansible hosts.
/etc/ansible/hosts
[servers]
server1 ansible_host=203.0.113.111
server2 ansible_host=203.0.113.112
server3 ansible_host=203.0.113.113
[all:vars]
ansible_python_interpreter=/usr/bin/python3
The all:vars subgroup sets the ansible_python_interpreter host parameter that will be valid for all
hosts included in this inventory. This parameter makes sure the remote server uses the
/usr/bin/python3 Python 3 executable instead of /usr/bin/python (Python 2.7), which is not
present on recent Ubuntu versions.
When you’re finished, save and close the file by pressing CTRL+X then Y and ENTER to
confirm your changes.
Whenever you want to check your inventory, you can run:
ansible-inventory --list -y
You’ll see output similar to this, but containing your own server infrastructure as defined in your
inventory file:
Output
all:
children:
servers:
hosts:
server1:
ansible_host: 203.0.113.111
ansible_python_interpreter: /usr/bin/python3
server2:
ansible_host: 203.0.113.112
ansible_python_interpreter: /usr/bin/python3
server3:
ansible_host: 203.0.113.113
ansible_python_interpreter: /usr/bin/python3
ungrouped: {}
Now that you’ve configured your inventory file, you have everything you need to test the
connection to your Ansible hosts.
Step 3 — Testing Connection:
After setting up the inventory file to include your servers, it’s time to check if Ansible is able to
connect to these servers and run commands via SSH.
For this guide, we’ll be using the Ubuntu root account because that’s typically the only account
available by default on newly created servers. If your Ansible hosts already have a regular sudo
user created, you are encouraged to use that account instead.
You can use the -u argument to specify the remote system user. When not provided, Ansible will
try to connect as your current system user on the control node.
From your local machine or Ansible control node, run:
ansible all -m ping -u root
This command will use Ansible’s built-in ping module to run a connectivity test on all nodes
from your default inventory, connecting as root. The ping module will test:
● if hosts are accessible;
● if you have valid SSH credentials;
● if hosts are able to run Ansible modules using Python.
You should get output similar to this:
Output
server1 | SUCCESS => {
"changed": false,
"ping": "pong"
}
server2 | SUCCESS => {
"changed": false,
"ping": "pong"
}
server3 | SUCCESS => {
"changed": false,
"ping": "pong"
}
If this is the first time you’re connecting to these servers via SSH, you’ll be asked to confirm the
authenticity of the hosts you’re connecting to via Ansible. When prompted, type yes and then hit
ENTER to confirm.
Once you get a "pong" reply back from a host, it means you’re ready to run Ansible commands
and playbooks on that server.
Note: If you are unable to get a successful response back from your servers, check our Ansible
Cheat Sheet Guide for more information on how to run Ansible commands with different
connection options.
Step 4 — Running Ad-Hoc Commands (Optional):
After confirming that your Ansible control node is able to communicate with your hosts, you can
start running ad-hoc commands and playbooks on your servers.
Any command that you would normally execute on a remote server over SSH can be run with
Ansible on the servers specified in your inventory file. As an example, you can check disk usage
on all servers with:
ansible all -a "df -h" -u root
Output
server1 | CHANGED | rc=0 >>
Filesystem Size Used Avail Use% Mounted on
udev 3.9G 0 3.9G 0% /dev
tmpfs 798M 624K 798M 1% /run
/dev/vda1 155G 2.3G 153G 2% /
tmpfs 3.9G 0 3.9G 0% /dev/shm
tmpfs 5.0M 0 5.0M 0% /run/lock
tmpfs 3.9G 0 3.9G 0% /sys/fs/cgroup
/dev/vda15 105M 3.6M 101M 4% /boot/efi
tmpfs 798M 0 798M 0% /run/user/0
server2 | CHANGED | rc=0 >>
Filesystem Size Used Avail Use% Mounted on
udev 2.0G 0 2.0G 0% /dev
tmpfs 395M 608K 394M 1% /run
/dev/vda1 78G 2.2G 76G 3% /
tmpfs 2.0G 0 2.0G 0% /dev/shm
tmpfs 5.0M 0 5.0M 0% /run/lock
tmpfs 2.0G 0 2.0G 0% /sys/fs/cgroup
/dev/vda15 105M 3.6M 101M 4% /boot/efi
tmpfs 395M 0 395M 0% /run/user/0
...
The highlighted command df -h can be replaced by any command you’d like.
You can also execute Ansible modules via ad-hoc commands, similarly to what we’ve done
before with the ping module for testing connection. For example, here’s how we can use the apt
module to install the latest version of vim on all the servers in your inventory:
ansible all -m apt -a "name=vim state=latest" -u root
You can also target individual hosts, as well as groups and subgroups, when running Ansible
commands. For instance, this is how you would check the uptime of every host in the servers
group:
ansible servers -a "uptime" -u root
We can specify multiple hosts by separating them with colons:
ansible server1:server2 -m ping -u root
For more information on how to use Ansible, including how to execute playbooks to automate
server setup, you can check our Ansible Reference Guide.
Playbook 1: install_apache.yml
This Ansible playbook is designed to install the Apache web server (with PHP support) on target
hosts. It uses the "apt" package manager to install Apache on Ubuntu-based systems and the
"dnf" package manager to install Apache on CentOS-based systems. The "become: true" ensures
that Ansible executes the tasks with elevated privileges, typically using "sudo" or "root" access.
---
- hosts: all
become: true
tasks:
- name: install apache2 package
apt:
name:
- apache2
- libapache2-mod-php
state: latest
update_cache: yes
when: ansible_distribution == "Ubuntu"
- name: install httpd package
dnf:
name:
- httpd
- php
state: latest
update_cache: yes
when: ansible_distribution == "CentOS"
This playbook can further be condensed by using an inventory file to store variable values.
install_apache.yml
—--
- hosts: all
become: true
tasks:
- name: install apache and php
package:
name:
- "Template:Apache package"
- "Template:Php package"
state: latest
update_cache: yes
inventory file (with host variables added)
172.16.250.132 apache_package=apache2 php_package=libapache2-mod-php
172.16.250.248 apache_package=httpd php_package=php
In the inventory file, you define host variables for each target host. The "apache_package" and
"php_package" variables specify the respective package names for Apache and PHP, tailored to
the specific distribution of each host. The "package" module is used to install the packages
defined by the "apache_package" and "php_package" variables on each host.
To run the playbook we use the command:
ansible-playbook --ask-become-pass install_apache.yml
Playbook 2: create_user.yml
---
- name: Create a new user
hosts: all
become: true
tasks:
- name: Add a new user
user:
name: dhruuv
state: present
password: your_encrypted_password # Optional, use an encrypted
password or set it later
shell: /bin/bash
createhome: yes
This playbook creates a new user with the specified attributes. You can specify an encrypted
password for the user or leave it empty to set the password later.
Conclusion:
In this assignment, we’ve installed Ansible and set up an inventory file to execute ad-hoc
commands from an Ansible Control Node.
Once you’ve confirmed you’re able to connect and control your infrastructure from a central
Ansible controller machine, you can execute any command or playbook you desire on those
hosts.
References:
https://www.youtube.com/watch?v=VANub3AhZpI&t=1s
https://www.youtube.com/watch?v=Egnsb89T0Rs
https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-ansible-on-ubu
ntu-20-04
https://www.coachdevops.com/2020/04/install-ansible-on-ubuntu-how-to-setup.html
