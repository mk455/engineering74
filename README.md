(1) Open up the terminal and check to see if git is available by running: git --version

(1a) Git is usually installed on Mac but if not, navigate to git.com and download.

(2) Once confirmed, type cd to navigate to a directory of your choice. This can either be the desktop or you can use the following commmand to create a new folder: mkdir "insert the name"

(3) Generate a key using the following command: ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

(4) This should display the following lines: Generating public/private rsa key pair. Enter a file in which to save the key (/Users/you/.ssh/id_rsa): Enter passphrase (empty for no passphrase): Enter same passphrase again:

(5) Press the enter key as the lines are displayed. It is a best practice to create a password.

(6) Type the ls command to confirm the key has been created. Two keys should be created, a private key, and a public key.

(7) Use the following command to view the public key: cat [key_name].pub

(8) Copy the public key.

(9) Using a web server, navigate to your GitHub Account. Go to setting and select "SSH and GPG keys".

(10) Click 'New SSH key" to create a new key. Give your key a name in the 'title' box. Paste the public key details in the "key" box.

(11) Save your key.

(12) Return to the terminal and navigate to the directory you created earlier(engineering74)

(13) Create a markdown and confirm it has been craeted using the following commands: touch README.md ls

(14) From your github account navigate to your repositories (click on your profile --> my repositories). Create a new repository

(15) Once created, follow instructions on screen.

(16) Return to terminal and edit the README file using the nano README.md command. Save changes using ctrl+x --> y --> enter.

(17) Commit changes to your repository via: git commit -m "Logical comment"

(18) Then add a branch using: git branch -M main

(19) Type the next command: git remote add origin [https://github.com/USERNAME/REPOSITORYNAME]--> this will change for new repositories.

(20) Upload the files using the final command: git push -u origin main

(21) Check your github repository has been updated.

(22) To make changes, edit this file and commit the changes again i.e follows steps 17, 19 and 20 again.


Priorities:
deadline, urgency, allocating time. "Fire alarm takes precedence"


motivation
discipline, force yourself to do more when unmotivated "When unmotivated do more than neccessary"
