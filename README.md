# FLEX github link

https://github.com/westes/flex

# Dependencies for FLEX

sudo apt install bash gcc m4 autoconf automake autopoint bison libtool make gettext help2man tar gzip lzip texinfo indent sed

# Github set-up (in case you're having problems with github in the laboratory)

For each CS 155 laboratory session, you are expected to submit your codes on github Classroom. However, you need to have an existing github account and ssh key.

If you do not have an existing github account (? not possible at this stage), make one (https://github.com). Afterwards, set-up your local machine’s ssh key, using instructions shown in this link:

https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account

Next, set-up the github email and username of your local machine by doing the following in a terminal:

1. git config--global user.email "your github email" 
2. git config--global user.name "your github username"

Your laboratory computer will then have a local ssh key that will be used to authenticate your submissions to the github classroom. This ssh key will be used throughout the semester, so it is important that you use the same computer all throughout the semester.

Each laboratory exercise involves the following broad steps: 

1. Copying the starter exercise files provided by github classroom to a local folder using the command git clone
2. Writing the required .lex flex files
3. Submitting your .lex solution files to github classroom using the git add . followed by git commit-m "submission description", and finally git push
