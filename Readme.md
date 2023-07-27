# Terminal Wizard

For this task, you have to play the role of Harry Potter, as a participant of the Terminal Wizard Cup. Your task is to find the Championship Cup, which is hidden deep inside a maze. Along the way, you'd find some secret codes which you have to save in a separate text file. You need to collect all the codes, which, in turn, will help you to complete the task successfully.  

> Note: All the parts of this task should be strictly implemented using Ubuntu terminal commands only. You should push your work to your "amfoss-tasks" repository after every challenge you complete, i.e. after every part of the secret-code you find.  


## 1. Enter the maze 

To begin, Clone this GitHub repository to your device using  
```git clone https://github.com/KshitijThareja/TerminalWizard.git```  

Also create a new directory in the same repository named "codes".  
The complete code is divided into 4 different parts, which you'll be finding as the task progresses.  

> Note: Run the python spell files that you'll be finding to get the secret code associated with that spell and copy the specific python spell files to the "codes" folder. Also create a new text file, named "Part_x.txt", 'x' refers to the part number, in the same directory and enter the secret code you received into that file.  

You can start now. Best of luck!  

## 2. First challenge

As you were navigating the maze, you came across a blast-ended-skrewt. To fight it, you need to use the right spell, which will be found in the directory '0x', where x is the first perfect number. The spell is stored in the file "Spell_0y", where y is the number you get by differentiating (x^2-7x) w.r.t 'x'.  
Now navigate to the file in spellbook which has the same name as the spell you discovered earlier and execute it to find the secret code.

## 3. Second Challenge

As you were finding your way after defeating the skrewt, you encountered a giant-spider. The spell that you need to fight it is stored in the file "Spell_0x" of the folder "0y", where xy is the atomic number of the earliest element used for making semiconductors.  
Navigate to the file in spellbook which has the same name as the spell you discovered earlier and execute it to find the secret code.  

> The files containing the next two parts of the password are present on different branches 😱. Don't worry we’ll help you with this one 😊. Run the command `git branch -a` to see all the local and remote branches of the repository. You can use `git checkout <branch_name>` in the terminal to switch to the new branch.

## 4. Third challenge
For this task, you'd have to switch to a branch, which is named after the subject taught by Professor Lupin at Hogwarts.
On your ways ahead, you encounter a Sphinx. For the Sphinx to allow you to pass safely, you'll have to solve a riddle given by it. The riddle is:  

<mark style="background-color: grey">In Hogwarts' realm of magic and might,  
A shape-shifting enigma takes flight.  
In shadows deep, it finds its place,  
Unveiling fears that you embrace.</mark> 

<mark style="background-color: grey">From your darkest thoughts it springs,  
Taking forms of frightful things.  
With laughter or terror, it delights,  
Revealing what your mind ignites.</mark>   

(Hint: it's a shape-shifting creature)  
Search what spell will you use to fight this creature from the web. Execute the python file named after that spell from the spellbook to get the secret code.  

But wait! This spell file is present in another branch. You need to copy it to the spellbook of the main branch. For this, you can execute the following command from the main branch by "cd'ing" into the required folder:  
``` git checkout <remote branch> 'Relative path of file to be copied from other branch' ```   
After this, you will be able to see the required file in your main branch.  

## 5. Fourth challenge

After the Sphinx cleared your way, you were able to reach find the Cup. But wait!!!  
The cup turned out to be a portkey and you find yourself teleported to a graveyard. It was Lord Voldemort's plan, the evil who was thought to be dead until now, to bring you here so that he can finish you off as you are his prime enemy. You need to fight him of and get the news of Voldemort's resurrection to Dumbledore. While fighting him, one of your spell's initiated a phenomenon that will help you to escape.  
The hint to find the spell is given in the commit log of the repository. Find the correct spell and save the wizarding world from this evil. 
(Hint: You'll be asked to navigate to other branch (again...). So for copying the required file to main branch, follow the instructions from the previous challenge.)  

## 6. The End
Finally, all the parts of the complete code are in one place. Now we just need to combine them to get the secret code and store it in a new file called finalcode.txt. Navigate to the 'codes' folder and concatenate all the contents of the file into a text file called finalcode.txt. After concatenating delete all the files except finalcode.txt.  

Congrats🎉, you've found the code. But what does this code mean?    The secret is....it is encoded in base64. To decode it, use:  
``` echo <base64 encoded string> | base64 --decode ```  
You'll know what to do with that code once you decode it to a readable format. Go ahead and decode it 👍
