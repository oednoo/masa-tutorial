masa-tutorial
=============

This is a tutorial repo, You must be able to follow this tutorial before I can give you access to the real repo. Also,
if you are ever not sure on something, you can use this repo to test your commands. I don not care if you mess this repo up.


Please do the following to to this repo. After you have set up a GitHub account and have git on your computer.

You can sign up for an account here
https://github.com

Follow this tutorial to set up git on your computer https://help.github.com/articles/set-up-gi

If you have any questions, ask me

1. Fork Me - Clone this repo on to your machine so that you have the files locally on your machine

2. Add your name to the file named "passed.txt" by simply editing that file.

3. Add a new file named "<your name>.txt"

4. Add that new file to the repo using the command "git add <your name>.txt"

5. Commit your changes by issuing the following command "git commit -a"

6. A text editor should pop up asking for a commit message. Please write breifly what you did. If you are using unix,
the text editor will probably be a text editor called nano. Instructions on how to save the file you should be at the bottom of the terminal.

7. Before your "push" your changes using "git push" make sure you pull to update your files. As a general rule you
always pull before you push. To do so use "git pull". If you get merge conflicts, it will tell you what files they are
in.

8. To fix merge conflicts, open the file with the merge conflicts and look for this
<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<. Around there you should see the different changes that you made versus changes
made by others. For example if someone is following this tutorial at the same time you are, and you both add your name
to "passed.txt". Then that other person finishes the tutorial before you and pulls then pushes. Then you pull and git
will notice you both made a change to the same file and the same line and complain. To fix this, edit the file to how it
should look. (Including removing any <<<<<<<<, ===============, or >>>>>>>>>>>>>>>>). Then commit your changes. "git
commit -a" The messages for this commit is usually something like "Fixing merge conflict"

9. If you had merge conflicts, go back to step 7.

10. Now do "git push". If you are really unlucky and someone else pushed inbetween your last pull and this push then you
will have to go back to step 7 and the push will fail, otherwise congrats, you are done. I will add you to the real masa
repo.

Other Tutorials:
http://try.github.io/


Quick Reference Guide for GIT:
http://jonas.nitro.dk/git/quick-reference.html

GIT is really powerfuli and confusing, feel free to ask a lot of questions. 
