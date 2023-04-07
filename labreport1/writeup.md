The beginning of the lab was to install Visual Studio Code. I had already installed Visual studio code,
but the way you would do it is by going to their website and pressing install. After you press install, go through all of the steps you are given to complete
the setup on your device, and get ready to make use of its terminal. You may download any languages to run on VSCODE later, but they are not necessary for this assignment. ![Image](VSC.png)

Next, you need to install git from the following link. https://gitforwindows.org/. Using the default settings should work just fine. If you want to check to make sure it is installed use the command git --version in the terminal. Open the git terminal in VSCODE through Command Pallette -> select default profile -> git bash. ![Image](git-img.jpeg)


Next is the hard part. First, go to the link https://sdacs.ucsd.edu/~icc/index.php and update your password.  REMEMBER THIS PASSWORD. After you have the password updated, enter ssh and your course specific username / email into the git terminal. Answer yes to the question you are asked and enter your password (it is working, it just does not show.) ![Image](ssh.png)

It may take awhile for your password to work, but when it does you should see something like this ![Image](finally.png)

Congratulations on completing the hard part, now to have fun experimenting with some commands! (try the following: /ncd ~
/cd
/ls -lat
/ls -a
/ls <directory> where <directory> is /home/linux/ieng6/cs15lsp23/cs15lsp23abc, where the abc is one of the other group members’ username
/cp /home/linux/ieng6/cs15lsp23/public/hello.txt ~/
/cat /home/linux/ieng6/cs15lsp23/public/hello.txt
) ![Image](commands.png)
