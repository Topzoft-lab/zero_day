#Setting Up Your First Repository

Let's initialize our first repository and push it to a remote GitHub server!

##Navigate to your home directory

Use cd ~ to go to your home folder. This will be the starting point for our project

## Create a new directory called zero_day

Make a new folder for our project using:

```
mkdir zero_day
```

## Navigate into this directory

Enter the zero_day directory using:

```
cd zero_day
```

You should now be inside the zero_day folder.

## Initialize git and add a remote origin

Initialize an empty git repository:

```
git init
```

Add a remote origin pointing to a GitHub repository:

```
git remote add origin https://github.com/<your-username>/zero_day.git
```

Be sure to replace <your-username> with your actual GitHub username.

## Create a README.md file

Add a README file with a small markdown introduction to the project:

```
emacs README.md
```

Or use another text editor to create the file.

## Add README to git and make your first commit

Stage the README file and commit it:

```
git add README.md
git commit -m "My first commit"
```

## Push to the remote GitHub repository

Finally, push your first commit to GitHub:

```
git push -u origin main
```

Enter your username and password when prompted.

Great job setting up your first project with git and GitHub!

Let me know if you need me to clarify or expand on any part of the Markdown walkthrough.~