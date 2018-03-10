# Node.js

## Install Node.js on OS

Windows
```
https://nodejs.org/en/download/
```

MacOS
```
brew install node
```

Ubuntu
```
sudo apt-get update
sudo apt-get install nodejs
sudo apt-get install npm
sudo ln -s /usr/bin/nodejs /usr/local/bin/node
```

## Create Remote Repository

```
https://github.com/new
name: nodejs-twitter
```

## Clone Remote Repository to Local Computer

```
cd ~/projects
git clone https://github.com/{username}/{project-name}
```
Note: What is in between {} means your personal username and project-name (nodejs-twitter) makes this url

## Open Repository Project in IDE (Atom)

```
File > Add Project Folder
```

## Create Test Script

```
Right Click Project > New File
Name: test.js
```

## Write Script

In your new test.js file copy paste or type:
```
//output text to the Terminal
console.log("Hi")
```

## Commit Change to Project to Remote repository

```
cd ~/projects/nodejs-twitter
```

## Add All New Files for Git to Track

```
git add .
```

## Commit the Changes to Tracked Files to be Stored in Remote Git Repository with a Descriptive Message

```
git commit -m "added test file to remote repo"
```

## Push the Commited Changes to the Remote Repository

```
git push
```
