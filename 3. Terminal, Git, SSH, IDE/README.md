# Using the Terminal

##MAC OS
Macs have an amazing terminal
```
cmd + spacebar
terminal
```

##Windows
Windows sucks

Download Git
```
https://github.com/git-for-windows/git/releases/download/v2.16.2.windows.1/Git-2.16.2-32-bit.exe
```

Follow these Steps in the Installation Wizard:
```
http://www.techoism.com/how-to-install-git-bash-on-windows/
```

#Using git for Version Control

## Installing git

```
https://gist.github.com/derhuerst/1b15ff4652a867391f03
```

## Signing Up to Github

```
https://github.com/join?source=header-home
```

## Cloning the Class Repository

Create a Folder in the Home Directory in Terminal
```
mkdir ~/projects
```

Change Directory to the New Projects Folder
```
cd ~/Projects
```

Clone the Course Repository
```
git clone https://github.com/bigdataconcordia/bigdatainfrastructure.git
```

Access the Public Repo from your Browser
```
https://github.com/bigdataconcordia/bigdatainfrastructure
```

## Accessing your Remote Instance (Server) with SSH

Create SSH folder in your Home Directory to Store the Key we Downloaded from AWS when we Created the EC2 (this folder may already exist)
```
mkdir ~/.ssh
```

Move the Key you Saved in the Home Directory (~) to the new ~/.ssh folder
```
mv ~/yourkeyname.pem ~/.ssh
```

Before Using the Key we Must Change its Permissions
```
sudo chmod 600 ~/.ssh/yourkeyname.pem   
```

Now we Use the Key to Access Our Server Securely
```
ssh -i ~/.ssh/yourkeyname.pem ubuntu@YOURSERVERIP
IP is visible at: https://console.aws.amazon.com/ec2/v2/home?region=us-east-1#Instances:sort=instanceState
```
