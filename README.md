# DS-Command-Line
 Tracking progress of course data science at the command line by Jeroen Janssens (https://www.datascienceatthecommandline.com/index.html)

### Getting Started
1) Create a new machine in virtualbox (make sure you allocate more than 8GB disk space)
2) Download Ubuntu ISO file (https://ubuntu.com/download)
3) In virtualbox right-click your machine, select Settings
4) Select "Storage" tab
5) Under "Controller: IDE" select "Empty"
6) Click the little CD button on the right side & find your ISO file
7) Open your machine to install the os
8) Follow instructions here to install docker on linux: https://medium.com/@mbyfieldcameron/docker-on-windows-10-home-edition-c186c538dff3
9) Open your terminal and run "docker pull datascienceworkshops/data-science-at-the-command-line"

### Running the docker shell
In your linux environment, open the terminal and type "$ docker run --rm -it datascienceworkshops/data-science-at-the-command-line"
Test it by typing "cowsay "Let's go!""

I created the alias startdsdocker to start the docker shell