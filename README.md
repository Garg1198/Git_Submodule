##Git Submodule project
This repository is just an example on how 'git submodule' command can be used to add external libraries to a cmake project 

  

The commands that one neeeds to run on the VS code terminal to clone the necessary external library is as follows: 

 	 -- git submodule add https://github.com/google/googletest external/googletest 

  

This will bring the external library to my project. 

  

Once there go to that folder in the VS Code terminal(using cd) and run the following command: 

 	-- git submodule update --init --recursive 

  

And when done just build the project. A successful build implies the folder has been added to the project correctly. 

Next tutorial we are going to use the unit test library to carry on some unit testing. 

 

******NOTE: One thing is very important that for the above git commands to work properly the repository must be git initialised or it must be available in git as a repository. On local projects the command will not work. To make it work temporarily one can open the VS Code terminal and type ‘git init’ **

 
