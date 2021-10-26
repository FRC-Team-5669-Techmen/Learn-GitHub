# Learning GitHub
Hello, and welcome to GitHub. GitHub is a platform for version control and collaboration. What you are currently looking at is a File in a Repository

Now, how do you get started with GitHub?

First, you should start off by creating an account at http://github.com/. Make sure that you do NOT use a school-affiliated account, as it will delete your GitHub account when you graduate.

Once you have created an account, please send the username to @dazon#0757 on Discord

Once you have created an account, download and install GitHub Desktop at https://desktop.github.com/. Follow the instructions with logging in to your GitHub account.

## How do I use GitHub?

To learn how to use GitHub, we need to go through the basics of a repository first. A repository is a home for all of your code. It is used to organize a single project and can store folders, files, images, videos, data sets - anything you could possibly need. Any file that you push here is stored forever on fancy & expensive servers. These repositories keep all versions of your code and mark every change that occurs, also known as a Diff. 


### Repositories & Cloning
To get started with using repositories, you can start on the one you currently are on. Click the `Code` button on the top of this repository. Once clicked, it should look like this: https://i.ibb.co/LNp08fv/Clone.png 

Click on the `Open with GitHub Desktop` button.

![GitHub Desktop](https://i.ibb.co/nQ0Crjd/Open-with-Git-Hub-Desktop.png)
  
If GitHub Desktop is set up properly, it should automatically open.

![Cloning](https://i.ibb.co/PZg73bs/Git-Hub-Desktop-Clone.png)

Click the blue Clone button on the bottom. This will download all of the files to your computer. Once finished, click on the `Repository` Button at the top, and select `Show in Explorer`. This will show all of the downloaded files, including this one.


### Creating files & Committing
Next, create a folder, with its title being your GitHub username. Inside this folder, create a file titled `[YOUR-USERNAME].txt`

Open this TXT file, and type `Hello, I am a member of the Mechanical/Design team`. Make sure you type that string exactly.

Now, reopen GitHub Desktop. You should see your changes displayed on the left bar. If you do not see this, try again. 

Next, on the bottom, in the `summary` field, fill it in with `Added [YOUR-USERNAME]’s folder`. 


### Branches
Once you do that, go to the top, where you see `Current Branch MAIN`. Click on this button.

In the window that shows, click on `New Branch`. Enter your Username for the name. Create the branch when done. Now, what is a branch? A branch is a codebase that is separate from the main branch. This allows the changes you make to be completely separate from the main codebase, and is very useful for testing different features, or subsystems, in isolation. Through things called Push and Pull requests, you can bring, or pull, in code from other branches or push your code to other branches.

Back to the left bar, click `Commit to [YOUR-USERNAME]`. Once you have committed, click on `PUBLISH BRANCH` or `PUSH BRANCH`. This will push your changes to GitHub. Now, what is a commit? A commit is a change to your code. Whatever you change in your code, including deleting, creating, or modifying files, is logged in a commit. When you push a commit, the changes in that commit are stored for all eternity. 


### Viewing Changes in Commits
Next, click on the Repository button on the top of GitHub Desktop. Click `View on GitHub`. This will open a browser window with the repository. On the top, near where you clicked on `Code`, click on the `main` branch button. You should see a list of all of the branches in this repository. Click on the one you created with your username. You will see a different repository, with the folder you created. Open this folder, and open the TXT file inside of it. Oh no! Thats not correct! You arent in the Mechanical/Design team! You’re on the Software/Electrical team! We must change that. 

Open the folder where your TXT file is stored. Open it, and change its contents to `Hello, I am a member of the Software/Electrical team`

Once you do this, Open GitHub desktop again. In the commit summary field, enter `Updated team info for [YOUR-USERNAME]`. Commit this change, and press `Push to origin` on the top.

Open the repository in a browser again, and go to your branch. You should see next to the file you created a dialogue saying `Updated team info for [YOUR-USERNAME]`, with a time period next to it. 


### Pull Requests & Code Review
Now that that’s fixed, let’s bring our changes to the `Main` branch.

To get started, click on the `Pull Requests` button on the top. 

![Pull Requests](https://i.ibb.co/D1r6LvG/Pull-Requests.png)

Click `New Pull Request`. A page should appear that looks like this. 

![Comparing Changes](https://i.ibb.co/1by3kWZ/Compare-changes.png)

On the top, change the second branch to the branch with your username. It should look like this when done correctly. 

![Changing Branches](https://i.ibb.co/bPMQgVY/Correct-branch.png)

Click `Create Pull Request`.

A window like this should display.  

![Creating Pull Requests](https://i.ibb.co/fYrKdkR/Create-Pull-Request.png)

On the right, under `Reviewers`, click the settings icon. Assign `FakeDazon` to review request.

Once completed, click `Create Pull Request`.

It should look like this.  

![Finished Pull Request](https://i.ibb.co/wSkRZF9/finished-pull-request.png)

Once I review the request, the `Merge Pull Request` button should be available to click. Once reviewed, click the button to merge your branch into the main branch.


## Fin
Congratulations! You now know how to use the basic functions of GitHub!
