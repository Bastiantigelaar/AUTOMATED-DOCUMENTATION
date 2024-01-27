# AUTOMATED-DOCUMENTATION
## what is done 
The idea of this repo is to create a simple system that can generate pdf files based on the software of a github wiki. 
The pdf will be converted using pandoc and eisvogel templates, i also added some changes which i prefered.
The conversing is already working, and is looking quite good.

## goals 
The goal is automated this annoying procces with github events/actions, so whenever a commit is made there will be a new pdf be generated. 
Right now this is also automated but the problem is that a python is always running in the background, and is all the time converting and checking, which is not very effiecent on the long run. 
The goal is also to update the code blocks, whenever the software changes with a new push event.
