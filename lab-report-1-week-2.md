# Lab Report 1

## How to log onto a course specific account on ieng6

1. Installing VScode
* Go to the [Visual Studio code website](https://code.visualstudio.com/) and install the appropriate version for your OS.
* Upon opening VScode, you should see a page that looks like this: 
![Vscode opening page](https://github.com/virsinghh/cse15l-lab-reports/blob/main/VScode%20opening.png?raw=true)

2. Remotely connecting
* First, look up your course-specific account at this [Link](https://sdacs.ucsd.edu/~icc/index.php)
* Next, open up a terminal in VScode and enter this command: $ ssh cs15lsp22zz@ieng6.ucsd.edu
* Remember to replace the "zz" in the command with your course-specific account letters.
* Type yes for the next message that pops up and press enter. Then, enter your password when prompted.
* Once you do this, you should be able to see the following interaction:

3. Trying some commands
* Try running various basic commands like pwd, ls, mkdir etc.
* Ensure that you try running these on both your machine and remotely on ieng6 after connecting via ssh.
* Here is a sample of what the commands should look like: 

4. Moving files with scp
* Create a sample file on your computer to move using scp
* Then, in your terminal, select the directory where you saved the file and run the following command: scp <filename> cs15lsp22zz@ieng6.ucsd.edu:~/
* Enter your password when prompted to do so
* Next, log onto ieng6 again using ssh and use ls. You should be able to see the file you created on your machine.
* run it using javac java.

