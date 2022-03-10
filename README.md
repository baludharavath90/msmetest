# msmetest

Pre-Requisites Steps:

Generate SSH Keys in Local Machine using below commands:

 >ssh-keygen -t rsa -C "dharavathbalu90@gmail.com" -b 4096

Once Key is generated, find the keys in Local Machine .ssh directory, as provided in the output of above command
Copy the id_rsa key and paste it into github settings>>SSHKeys>> New Keys

Validate SSH Keys is added to github

Run below commands to configure username and user email to git:
	>git config --global user.name "BALU"
 
	>git config --global user.email "dharavathbalu90@gmail.com"


Clone the Github >> Repository to Local Machine
	>Copy the Repository SSH git Clone link 
	>Open Gitbash cmd 
	>create folder in any drive 
	>go to directory/folder
	>Run command: git clone SSH git Clone link 
		> Example: git clone git@github.com:baludharavath90/msmetest.git
