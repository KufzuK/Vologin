to create ssh-key:

1.	type * ssh-keygen -t ed25519 -C "your@email.com" *

2.	Copy all the text from appeared file  .pub, this text is your key.


to add public key on your Github:


1.	Press "settings" on your Github and then choose "SSH and GPG keys". 

2. Then push the button "New SSH key" and paste the copied key into the special field.

3. Github may probably ask you to enter your password,and after that your ssh-key is added on your Github.


to clone the repository

1. copy the ssh link of your repository

2. type * git clone "paste the link here" * in terminal

