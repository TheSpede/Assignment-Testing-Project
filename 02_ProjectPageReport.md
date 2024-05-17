
## Summary (Summarize the bug encountered concisely)
When logging in to gitlab and creating a new project, where it should read "create blank project", it reads "create black project". There is a typo. 


## Steps to reproduce     
Go to gitlab. On the gitlab login page, enter your login information. After signing in, click on "new project" on the top right. It will now show 4 options. Now, one of the titles should read "create blank project", but it reads "create black project". 
   

## What is the current bug behavior?
The bug is a typo. Spelling mistake in the code. 
     

## What is the expected correct behavior?
The bug reads "create black project". It should read "create blank project".

     
## Relevant logs and/or screenshots
![alt text](image.png)
      

## Possible fixes
Have to find the line of code from source code and fix the typo. 


## Whom do you report/ Assign To/ Tags
 /label ~bug ~reproduced ~needs-investigation 
      /cc @project-manager 
      /assign @qa-tester


## Priority
The bug priority is minor, as it doesnt effect the functionality of the site, but should be fixed as soon as possible. 
      
