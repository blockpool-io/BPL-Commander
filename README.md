# BPL-Commander

An easy to use bash script for managing a Blockpool Node

## Getting Started

### DO NOT RUN BPL COMMANDER AS ROOT 

#### Create a user

1. Use the adduser command to add a new user to your system. Be sure to replace username with the user that you want to create.

	`adduser username`


2. Set and confirm the new user's password at the prompt. A strong password is highly recommended!


3. Follow the prompts to set the new user's information. It is fine to accept the defaults to leave all of this information blank.


4. Use the usermod command to add the user to the sudo group.

	`usermod -aG sudo username`
	
	Again replacing username with the name used in step #1


5. Switch to the new user

	`su - username`

#### Get BPL-Commander

##### Via Git:

1. Clone the repo

	`git clone https://github.com/blockpool-io/BPL-Commander.git`

2. Move to the folder

	`cd BPL-Commander`

3. Make the script executable

	`chmod +x BPLcommander.sh`

4. Start BPLcommander

	`./BPLcommander.sh`

Follow the on screen directions from here on out.

#### Via wget

1. Get the script

	`wget https://raw.githubusercontent.com/blockpool-io/BPL-Commander/master/BPLcommander.sh `

	This will place BPLcommander.sh in the root of your Home folder (or your current dir if not Home)

2. Make the script executable

	`chmod +x BPLcommander.sh`

3. Start BPLcommander

	`./BPLcommander.sh`



Follow the on screen directions from here on out.

