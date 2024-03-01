What is README.md?
README.md is a documentation file often found at the root of a project's directory in version control systems like Git. The .md extension indicates that the file is written in Markdown, a lightweight markup language designed for easy readability and formatting. A README.md file typically includes important information about the project, such as:

An introduction to the project and its purpose
Instructions for installing and using the project
Information on how to contribute to the project
License information
Contact information for the maintainers or contributors
The README.md file serves as the first point of information for anyone encountering your project, providing a guide on how to use or contribute to it.


Git and Github
--> What is a version control system ---> Types of version control system ---> Benefits of using a version control system

Distributed ---> git Centralized Version Control system ---> github , svn Local ---> git

--> What is git : ---> What is github

Git installation ( Package Managament )
used ---> package managers CLI or Web based GUI ubuntu sudo apt-get or apt install git redhat sudo yum install git MacOs brew install git Windows choco install git

Configure Local Environment ( your personal computer )
Working directory ----> by initializing git  git init 
Name and email ----> git config --global user.name <name>
               -----> git config --global user.email <email address>

               Repository Authentication ---> On github ---> profile ---> settings ----> developers settings ---> Personal access token
                                         push to github 
                                                                   ---> We configured our repository to be able to push without passing the repository url all the time
                                                                                                  command :  git remote add "alias" repository url 
                                                                                                                                 verify :   git remote -v 
