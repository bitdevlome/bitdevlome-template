## Contributing

### How to contriute

#### If you don't have git on your machine, [install it](https://docs.github.com/en/get-started/quickstart/set-up-git)

##### Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

#### Clone the repository

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```bash
git clone "url you just copied"
```

where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

For example:

```bash
git clone https://github.com/yourusername/LearningHub.git
```

where `yourusername` is your GitHub username. Here you're copying the contents of the LearningHub repository on GitHub to your computer.

#### Create a branch

Change to the repository directory on your computer (if you are not already there):

```bash
cd repository folder
```

Now create a branch using the `git switch` command:

```bash
git switch -c your-new-branch-name
```

For example:

```bash
git switch -c add-custom-branch
```

#### Make necessary changes and commit those changes

If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```bash
git add _your file_ or git add . #for multiple files
```

Now commit those changes using the `git commit` command:

```bash
git commit -m "your relevant message that shows the change you have done"
```

#### Push changes to GitHub

Push your changes using the command `git push`:

```bash
git push -u origin your-branch-name
```

replacing `your-branch-name` with the name of the branch you created earlier.

#### Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.
Now submit the pull request.

Soon I'll be merging all your changes into the main branch of this project. You will get a notification email once the changes have been merged.

### Where to go from here?

Congrats! You just completed the standard _fork -> clone -> edit -> pull request_ workflow that you'll often encounter as a contributor!

Celebrate your contribution and share it with your friends and followers on Twitter and tag the team.
