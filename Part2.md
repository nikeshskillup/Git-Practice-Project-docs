# Academic Community Collaboration Platform - Part 2

## Lab Tasks

1. **1. Fetch the repo having your updates in Part 1:**
   Clone the repo to which you pushed your project folder & file in Part 1   
   ```
   https://github.com/<YourUsername>/Centralized-repository_for_collaboration"
   ```

2. **Create a new branch and Switch**

   Open terminal and navigate to the "Centralized-repository_for_collaboration" folder. 
   ```
   cd Centralized-repository_for_collaboration/
   ```

   Create a New Branch for Local Updates
   ```
   git checkout -b my-local-updates
   ```
   <img src="./images/new-branch-switch.png" /> <br> <br>

   > NOTE:  The `-b` flag  is used to create a new branch and switch to it. If the branch is already present, we can swtich to it without using the flag (For example: `git checkout my-local-updates`).

   Verify that you are on the new branch by running the `git branch` command.

   <img src="./images/new-branch-confirmation.png" /> <br> <br>


3. **Create HTML File:**
   Create a file named `Shipping_Calculator.html` in the project folder  (eg - `shipping_calculator-John_Doe-CS-S01-5`) with code:
   ```
   <!DOCTYPE HTML>
   <html>
   <head>
   </head>
   <body>
   <!-- This HTML file is a part of my Shipping Calculator Project -->
   </body>
   </html>
   ```


4. **Add, commit & push your changes to the local branch**

   ```
   git add .
   ```

   ```
   git commit -m "Adding Shipping_Calculator.html file"
   ```

   Push the changes to `my-local-updates`

   ```
   git push --set-upstream origin my-local-updates
   ```
   <img src="./images/pushed_to_branch-02.png" /> <br>

   **In this command:**

   - `--set-upstream` : This option sets up a tracking relationship between the local branch [`my-local-updates`] , and the remote branch [`main` or `master`] on the remote repository. In future, when you run git push or git pull, Git will know to push or pull changes to or from `my-local-updates`.

   - `origin`: This is the name of the remote repository.

   - `my-local-updates`: This is the new branch to which you are pushing the changes.

   <br>

#### In your Github repository:

5. **Raise Pull request to merge it to MAIN/MASTER branch of Your forked repo**

   <img src="./images/raise-pull-req.png" /> <br> <br>

   Add a comment (`Final Project Submission to Centralized repository for collaboration`) & Click on `Create pull request`.

   <img src="./images/create-pull-request.png" /> <br>

   After clicking `Create pull request`, you'll see this interface. It means you have successfully submitted your project to your college's 'Centralized Repository for Collaboration' repo. Since you don't have the right to merge, you can only raise a pull request. Now it depends on your college whether to accept it or decline.

   <img src="./images/merge-pull-request.png" /> <br>


#### In Your lab Environment

6. **Add, push & merge your 2nd file to the repo**





9. Click on `Confirm merge`.

<img src="./images/confirm-merge-request.png" /> <br>

10. The request once merged successfully can be seen as shown in the below screenshot:

<img src="./images/merge--successful.png" /> <br>

11. You can delete `my-project` by clicking on `Delete branch`, since it is no longer required.

<img src="./images/delete_branch-02.png" /> <br>




=================
<summary> <b> Click here to see the process when you are pushing from a branch on your Github account to a branch on another Github account. </b> </summary>

-  Click on `compare across forks`

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0131EN-SkillsNetwork/labs/project/images/compare-across-forks-01.png" /> <br>

- You will get a page similar to this:

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0131EN-SkillsNetwork/labs/project/images/compare-across-forks-02.png" /> <br>

The `head repository` and the `compare` fields pertain to the repository URL and branch respectively on your Github account.

The `base repository` and the `base` fields pertain to the repository URL and branch respectively of the Github account where you wish to raise a pull request.

- Select the corresponding fields from the dropdown to create the pull request.

