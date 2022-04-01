#Initial commands for git
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:rodrigodN7/ccna.git
git push -u origin main

#If git an error when push, configure the ssh key
ssh-keygen -t ed25519 -C "my@mail.com"

#copy the plain text and the .pub to the /.ssh folder