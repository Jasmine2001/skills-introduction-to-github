<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# Introduction to GitHub

_Get started using GitHub in less than an hour._

</header>

<!--
  <<< Author notes: Step 2 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->
## Step 1: Create a repository
## Step 2: Create a branch
Branching lets you have different versions of repository at one time.<br>
**What is a branch?**:


By default, your repository has one branch named ```main``` that is considered to be the definitive branch. You can create additional branches off of ```main``` in your repository.
![branching](https://github.com/user-attachments/assets/d299ecfd-1bc9-4c90-a953-83395623b46f)

**Createing a branch**


## Step 3: Make and commit changes


_You created a branch! :tada:_

Creating a branch allows you to edit your project without changing the `main` branch. Now that you have a branch, it’s time to create a file and make your first commit!

**What is a commit?**: A _[commit](https://docs.github.com/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits)_ is a set of changes to the files and folders in your project. A commit exists in a branch. For more information, see "[About commits](https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits)".

### :keyboard: Activity: Your first commit

The following steps will guide you through the process of committing a change on GitHub. A commit records changes in renaming, changing content within, creating a new file, and any other changes made to your project. For this exercise, committing a change requires first adding a new file to your new branch.

> [!NOTE]
> `.md` is a file extension that creates a Markdown file. You can learn more about Markdown by visiting "[Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)" in our docs or by taking the "[Communicating using Markdown](https://github.com/skills/communicate-using-markdown)" Skills course.

1. On the **< > Code** tab in the header menu of your repository, make sure you're on your new branch `my-first-branch`.

2. Select the **Add file** drop-down and click **Create new file**.

   ![create new file option](/images/create-new-file.png)

3. In the **Name your file...** field, enter `PROFILE.md`.

4. In the **Enter file contents here** area, copy the following content to your file:

   ```
   Welcome to my GitHub profile!
   ```

   ![profile.md file screenshot](/images/my-profile-file.png)

5. Click **Commit changes...** in the upper right corner above the contents box. For commits, you can enter a short commit message that describes what changes you made. This message helps others know what's included in your commit. GitHub offers a simple default message, but let's change it slightly for practice. First, enter `Add PROFILE.md` in the first text-entry field titled "Commit message".

   ![screenshot of adding a new file with a commit message](/images/commit-full-screen.png)

6. In this lesson, we'll ignore the other fields and click **Commit changes**.
7. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.

## Step 4. Open a pull request
Pull requests are the heart of collaboration on GitHub. When you open a pull request, you're proposing your changes and requesting that someone review and pull in your contribution and merge them into their branch. Pull requests show diffs, or differences, of the content from both branches. The changes, additions, and subtractions are shown in different colors.
## Step 5. Merge your pull request

## How to start a project found on GitHub!
### Step 1. Fork(on Github) and Clone(on Local) the project
```Bash 
git clone (clone using the web Url.)
```
### Step 2. Navigate into the project folder
```Bash
cd ...(file name)
```
> go deep dive into the folder
```Bash
cd "..."
```
> look into file 
### Step 3. Set up your Python environment
```Bash
conda create -n quant-trading python=3.10
conda activate quant-trading
```
> I prefer using conda
### Step 4. Install dependencies
- Check if there's a requirements.txt or environment.yml file. <br>
```Bash
pip install  -r requiremnet.txt
```
- If no such file exists, you can manually install common packages<br>
```Bash
pip install pandas numpy matplotlib yfinance ta-lib (download by yourself)
```
### Step 5. Explore the project structure
```Bash
dir
```
### Step 6. Run a sample script
```Bash
python main.py
```
## Adding locally hosted code to GitHub

```Bash
git init -b main
```
Add the files in your new local repository. This stages them for the first commit.
```
$ git add
```
Commit the files that you've staged in your local repository.
```
$ git commit -m "First commit"
```

## Adding a local repository to GitHub using Git
At the top of your repository on GitHub's Quick Setup page, click  to copy the remote repository URL.
![copy-remote-repository-url-quick-setup](https://github.com/user-attachments/assets/27686d4e-6448-4d95-ad1a-c11ea19afbed)

```
git remote add origin REMOTE-URL
```
- To push the changes in your local repository to GitHub, run the following command.
```
git push origin main
```






<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/introduction-to-github) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2024 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
