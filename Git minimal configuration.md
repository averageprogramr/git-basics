Git minimal configuration

open git terminal from the desktop

To check configuration setting in the gib type the below command
$ git config --global --list

setting up username in the git [type the below command press enter]
$ git config --global user.name "username"

Settup up email address in the git [type the below command and press enter]
$ git config --global user.email "useremail"

To output the entire contents of the file in git use [cat command]
$cat ~/.gitconfig
[user]
        name = "username"
        email = "useremail"

[.] dot files are semihidden, so they don't get accidently edited or deleted

