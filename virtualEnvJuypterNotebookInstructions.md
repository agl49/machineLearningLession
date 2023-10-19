To make a notebook play nice with a virtual environment you set up in 
VS code. You have to do the following:


1. Create the virtual environment

2. make sure ipython and ipykernel are installed

3. Run ipython kernel install --user --name=kernel_name in the command line 
   with the env activated. Name Kernal_name to be the name of the virtual env
   you made.

4. Reload the vscode window and you should see it as an option when selecting 
   in the kenral select menu.

5. To check if it worked, run the following two commands in your notebook to 
   see if you are using the correct env:

```
!pip3 list
```
```
import sys
print(sys.prefix)
```

Here is the website we are learning from right now:
https://course.fast.ai/Lessons/lesson1.html
