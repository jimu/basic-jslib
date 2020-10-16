# basic-jslib
A step by step walkthrough adding a new jslib plugin to a Unity project

## steps
1. Create an empty repo using the github web interface  
  
Here you can the .gitingore template provided by github. It is added to the root directory and there is no risk of accidently adding it to a subdirectory which can happen when adding it to an existing repo  
  
You also get a chance to verify the actual repo name. If you ever want to publish your project as a nodejs, you'll want an all lowercase repo name. Spaces are converted to '-' and they are fine.  
  
So in this case, I am using the github web interface to create a repo named "basic-jslib". Github added the dash for me. I don't know if "Basic jslib" without the dash is used anywhere in the repo  
 
In my notes, I record that my new project is named:

   basic-jslib

2. Create a Unity project with the repo name and exit

    Unity Hub > New Project > basic-jslib

I click save and exit

3. Command line from my "projects" directory

     git clone https://github.com/jimu/basic-jslib.git temp
     
  robocopy temp basic-jslib.git /s /move
	cd basic-jslib
	git add .
	git commit -m "Add empty unity project"
	git push
