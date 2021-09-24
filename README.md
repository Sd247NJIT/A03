# A03
<!DOCTYPE html>

## Step-by-step tutorial on setting up git/webstorm/github: ##

### Download these softwares: ###
<br>
Webstorm - https://www.jetbrains.com/community/education/#students
<br>
**Git** - https://git-scm.com/downloads

### Setup up the account: ###
<br>
**Github** - https://github.com/join 

### To connect Github & webstorm: ###
- Open Webstorm
  - Go to system preferences → select version control → **Git**
  
  - On top, go on _Path to Git Executable_ and make sure the path is entered to git.exe (it should already be auto-detected on your local file)
  
  - Go down to:
    <br>
         - _Update Method_ and select **Merge** to avoid **merge conflicts**
    <br>
         - _Explicitly check for incoming **commits** on **remotes**_ and select Auto, click OK

### Creating and Importing the **Repository**: ###

- Open **Github**
  - On the top right corner, click the “+” sign and select “New **Repository**”
  
  - Include **Repository** name
  
  - Make it public
  
  - Select, Add a README file
  
  - Click _Create **Repository**_.

### Creating Repository on webstorm: ###

- Open webstorm
  - Open a new project and choose VCS from main menu
  
  - Create new **repository** 
  
  - Give it a title 
  
  - Click ok.

### Importing a new repository: ###
  - On webstorm, go on the **Git** tab
  
      - Scroll down to **Git** and click **Clone**
 
      - Enter the URL of the **repository** within version control (Note: make sure you are logged into **Github**)

### To make a new project: ###

- Open Webstorm

  - File → New → scroll to HTML file and click it

### How to push from webstorm to github: ###

- Open a new repository

  - Write branches or fetch from a different repo to the current HTML file
 
  - Before pushing, write in the _commit message_ then click _commit & push_ and the objects should be synced to **Github**! (Note: commit messages are helpful, especially during collaborations and pull requests on someone else’s repository.)
