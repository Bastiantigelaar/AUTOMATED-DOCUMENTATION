# AUTOMATED-DOCUMENTATION
This project is for fun and can be used by everyone.
## what is done 
The idea of this repo is to create a simple system that can generate pdf files based on the software of a github wiki. 
The pdf will be converted using pandoc and eisvogel templates, i also added some changes which i prefered.
The conversing is already working, and is looking quite good. for this repo i have set the goal to automated this based on github events, i saw that there is some software already availabe that can do this. However i want to push it a little bit more, thats why i set the following goals for this project. 


## goals 
The goal is to automated the markdown to pdf procces with github events/actions, so whenever a commit is made there will be a new pdf be generated. 
Right now i have this already automated and working, but the problem is that a python script is always running in the background, and is all the time converting and checking markdown files, which is not very effiecent on the long run.
The goal is also to update the code blocks, whenever the software changes with a new push event, this is something that i am currently working on. 
I try to make this for python script and later on i will add support for other languages. 


