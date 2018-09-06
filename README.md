# firstGuide
My tutorial to get to use git for example practice

## How to fork this repo?

Fork this repository by clicking on the fork button on the top of this page. This will create a copy of this repository in your account.

## Clone the repository

Now clone this repo to your machine. Go to your GitHub account, click on the clone button and then click the *copy to clipboard* icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```
where "url you just copied" (without the quote marks) is the url to this repository(your fork of this project).

Now this would have by now created a copy of this on your local machine.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd firstGuide
```
Now create a branch using the `git checkout` command:
```
git checkout -b <add-your-new-branch-name>
```

## Make necessary changes and commit those changes

Make whatever changes to any of the files and update in the log for a record across the users. Not actually required you'll discover this.
Consider maybe adding your name to this as a first exercise if you don't get an idea for what changes to make...


If you go to the project directory and execute the command `git status`, you'll see there are changes. 


Add those changes to the branch you just created using the `git add` command:

```
git add <file-names>
```
This kinda keeps a check on whether you want those changes to get reflected onto your branch. Let's take a scenario you wanted to experimentally try a feature and decided no and wanted to dump it this kinda keeps a buffer for stuff like that.



Now commit those changes using the `git commit` command:
```
git commit -m "<your message here as to what changes have you committed for what changes for a reference"
```
This now makes your files ready for upload in scenarios you aren't in a condition to connect to the internet. It is in such a a state that on internet access running the below commands would sync this up on your GitHub check below...


## Push changes to GitHub

Push your changes using the command `git push`:
```
git push origin <add-your-branch-name>
```
replacing `<add-your-branch-name>` with the name of the branch you created earlier.


### Ketan Karnakota
