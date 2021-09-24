# A03
<!DOCTYPE html>

## Step-by-step tutorial on setting up git/webstorm/github: ##

### Download these softwares: ###
<br>
Webstorm https://www.jetbrains.com/community/education/#students
<br>
**Git** https://git-scm.com/downloads

### Setup up the account: ###
<br>
**Github** https://github.com/join 

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

## Glossary: ##

- **Branch**:  sets of code in a box, titled in different names; there can be more than one branch 
- **Clone**: to make a copy; starts of the same - cannot do anything to pool without a clone
- **Commit**: to take the objects and put them in a box
- **Fetch**: downloading objects from a different repository
- **GIT**: stores code history and tracks files in a local. 
- **Github**: a platform for using Git
- **Merge**: to join development histories together and integrate them into one branch
- **Merge Conflict:** an error that occurs when it’s unable to solve commits
- **Push:** to ship off the codes 
- **Pull:** it’s a request that tells others about the changes pushed; essential during collaborations 
- **Remote:** version of the project pushed to git; being stored somewhere else other than the local
- **Repository:** a project through git terms or a designated folder in local or remote

### References: ###

- Gienow, Michelle. “Working with Branches in Git and Github.” The New Stack, 18 May 2018. 
  
  URL: https://thenewstack.io/dont-mess-with-the-master-working-with-branches-in-git-and-github/#:~:text=:A%20branch%20is%20essentially%20is,into%2C%20and%20is%20called%20master 

- “Git Merge.” Bit Bucket. No date. 

  URL: https://www.atlassian.com/git/tutorials/using-branches/git-merge#:~:text=Merging%20is%20Git's%20way%20of,merge%20into%20the%20current%20branch 

- Jetbrains. “Set up a Git repository.” 14 September 2021. 

  URL: https://www.jetbrains.com/help/webstorm/set-up-a-git-repository.html#ignore-files  

- Jetbrains. “Manage projects hosted on GitHub.” 08 March 2021. 

  URL: https://www.jetbrains.com/help/webstorm/manage-projects-hosted-on-github.html

- Hendela, Arthur H. “Introduction to Github and Webstorm.” NJIT. Powerpoint presentation.
