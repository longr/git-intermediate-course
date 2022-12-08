# git-intermediate-course

1. Create a new repository on GitHub (tick create ReadMe)
   1. Go to GitHub.com
   2. Click on the plus symbol in the top right
   1. Click **New Repository**.
   1. Fill in the details requested.
   1. Tick **Add a README file**.
   1. Click **Create Repository**
3. Clone the repository to your local machine
   1. Go to the repository you just created on GitHub. It should be called github.com/<username>/<repository_name>.
   1. Click on the green button labelled **Code**.
   1. Make sure **SSH** is selected and then click on the two overlapping squares to the right on the repository name (this will copy the repository details)
   1. Open a terminal on your machine.
   1. Clone the repository by typing: 
      ```
      git clone <pasted_text>
      ```
   1. This will clone the repository onto your local machine.
5. Create a new branch.
   1. Type:
      ```
      git checkout -b <branch_name>
      ```
   1. This will create a new branch.  Confirm this by typing:
      ```
      git branch
      ```
   1. This will list the available branches and place an asterix next to the current branch.
6. Edit the README file.
   1. Open your favourite editor and makes some changes to the README file.
   1. Commit the changes
      ```
      git add README.md
      git commit -m 'Editted the readme'
      ```
7. Push changes back.
   ```
   git push
   ```
8. Swap back to new branch
   1. On your machine change back to the main branch:
      ```
      git checkout main
      ```
9. Make some changes and commit
   1. Open your favourite editor and makes some changes to the README file.
   1. Commit the changes
      ```
      git add README.md
      git commit -m 'Editted the readme on main'
      ```  
11. Push to git hub
  
    ```
    git push
    ```
12. Start PR
    1. Go to your repository on GitHub.
    1. On the left under **<> Code** it should say **main** with a down arrow.
    1. Click on **main** and select your new branch.
    1. A little lower on the right it should say ** Contribute**, click on this
    1. Click on **Open pull request**.
    1. Fill in the required details (Title and Comment).
    1. Click **Create pull request**.

