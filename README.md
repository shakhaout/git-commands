# gitlab-commands

1. Download git for your operating system from this link, git-scm.com/downloads

2. Install the git from the .exe file by selecting all the default settings.

3. Create a project in your gitlab account.

4. Check whether git is installed properly using below command,

		$ git --version

5. Config your username and email by following commands,
 
		$ git config --global user.name "Shakhaout Hossain"

		$ git config --global user.email "shakhaout.hossain@hiperdyne.com"

6. To check whether your credentials configured properly,

		$ git config --global --list

7. Create a folder in pc for all git project such as "./GitLab/"
      Create a subfolder for the project such as "./firstproject/"

9. Open Git bash inside the project folder i.e., ./firstproject/ that is created recently.

10. To initialize git use command,

		$ git init
		
   It will create a .git file.

11. Copy the source code to "./firstproject/" directory and run below command,

		$ git status
		
   It will show the Untracked files.

12. To add all files run

		 $ git add .

13. Run below command to check the added files

		$ git status

14. To commit the changes run

		$ git commit -m "message you want to add. Please add meaningful message."

15. To push the commit

		$ git push -u "url of the repogitory. copy from clone" master 
		
		(to commit other branches use specific other than master)
    Above command will ask for git credentials. Use gitlab usename and access token. Finally the commit will be visible in the repository.


