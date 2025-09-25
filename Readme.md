DevOps :-
It is basically the concept of the developer team and operations team working together so they can deliver,build or update software quicker.

CI (Continuous Integration) :-
It means that every time a developer writes a new piece of code and adds it to the main project, an automated system immediately takes all the code, builds it into a working application, and runs tests to make sure the new code hasn't broken anything.

CD (Continuous Delivery/Deployment) :-  
It means the software is released automatically, with no human needing to approve it. The moment the code passes all the automated tests, it goes live to your users.

Containerization :-
Resource isolation at the OS (rather than machine) level, usually (in UNIX-based systems) in user space. So basically it is not the os itself but acts  like one for example providing main features of os like file system, disk quota, CPU and memory, I/O rate, root privileges, and network access. It enables application to run in any environment.

Rollback:- 
So lets say if you want to update youre system with a software update and it causes a bug or a problem. This is where rollback concept comes in , it enables you to go to a previous state of your system where there was no error to begin with.

 Connecting Concepts to This Assignment :- 

- By writing automation in `script.sh`, I practiced DevOps principles of automation.  
- Using Git and GitHub demonstrates CI/CD readiness: commits and branches can be integrated and tested.  
- If I made a mistake, I could use Git to rollback to a previous commit.  
- Creating the `exam` project structure shows container-like isolation , everything is packaged together and reproducible.  

Assignment process :- 
So firstly i used mkdir exam command  to create a directory named exam in my home directory. Then use cd command to change the directory to exam in terminal ( cd exam ). I used nano Readme.md
command to create and edit the Readme.md file. After that, in the same directory , i used nano script.sh command to create a file name script.sh
