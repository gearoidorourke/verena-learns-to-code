# verena-learns-to-code

Some simple steps to build & deploy a website with Middleman. Ready? Let's go.

*Note:* "$" is a convention that indicates a terminal command. But you don't need the "$"  to run the command. For example to find out wtf is happening with git, type "git status" *not* "$ git status".

## Git & repo setup
- [ ] Set up git: https://help.github.com/articles/set-up-git/
- [ ] Open your terminal of choice
- [ ] create folder “code”
- [ ] in terminal: $ cd /Users/Verena/Documents/code
- [ ] $ git clone git@github.com:orourkedesign/verena-learns-to-code.git
- [ ] $ cd /Users/Verena/Documents/code/verena-learns-to-code


### Useful git commands

#### git status
== WTF is happening

#### pwd
== Where am I

#### git checkout [branch name]
== Moves you to the branch you specify

#### git add -A
== Adds all your changed/deleted/new files, ready for a commit

#### git commit -m "Your commit message here"
== Commits your changes

#### git pull origin [branch name]
== Get the latest changes from Github

#### git push origin [brand name]
== Sends the latest changes to Github

#### git reflog
== Show history of your commits

#### ls
== lists everything in the folder

## Middleman setup
(Assuming we're still in ../code/verena-learns-to-code/)
- [ ] Read about Middleman https://middlemanapp.com/
- [ ] $ gem install middleman
- [ ] $ cd .. (takes up one level to /code)
- [ ] $ middleman init verena-learns-to-code (tells Middleman to do some cool shit with our repo)
- [ ] $ cd verena-learns-to-code
- [ ] $ middleman (starts the server)
- [ ] Open your browser and go to http://localhost:4567/
- [ ] Open Sublime text and open our repo to see your site structure

# !! ALERT !! WE NOW HAVE A WEBSITE !!

Time to hack...
