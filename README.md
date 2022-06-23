# git-intermediate-course

1. Created a new repository on GitHub (tick create ReadMe)
   - Go to GitHub.com
   - Click on the plus symbol in the top right
   - Click **New Repository**.
   - Fill in the details requested.
   - Tick **Add a README file**.
   - Click **Create Repository**
3. Cloned the repository to your local machine
   - Go to the repository you just created on GitHub. It should be called github.com/<username>/<repository_name>.
   - Click on the green button labelled **Code**.
   - Make sure **SSH** is selected and then click on the two overlapping squares to the right on the repository name (this will copy the repository details)
   - Open a terminal on your machine.
   - Clone the repository by typing: 
  
   ```
   git clone <pasted_text>
   ```
   - This will clone the repository onto your local machine.
5. Create a new branch.
   - Type:
  
   ```
   git checkout -b <branch_name>
   ```
   - This will create a new branch.  Confirm this by typing:
   ```
   git branch
   ```
   - This will list the available branches and place an asterix next to the current branch.
6. Edit the README file.
   - Open your favourite editor and makes some changes to the README file.
   - Commit the changes
   ```
   git add README.md
   git commit -m 'Editted the readme'
   ```
  
7. Push changes back.
   ```
   git push
   ```
8. Swap back to new branch
   - On your machine change back to the main branch:
   ```
   git checkout main
   ```
9. Make some changes and commit
   - Open your favourite editor and makes some changes to the README file.
   - Commit the changes
   ```
   git add README.md
   git commit -m 'Editted the readme on main'
   ```  
11. Push to git hub
  
   ```
   git push
   ```
12. Start PR
    - Go to your repository on GitHub.
    - On the left under **<> Code** it should say **main** with a down arrow.
    - Click on **main** and select your new branch.
    - A little lower on the right it should say ** Contribute**, click on this
    - Click on **Open pull request**.
    - Fill in the required details (Title and Comment).
    - Click **Create pull request**.

