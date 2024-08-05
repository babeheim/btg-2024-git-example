
BTG2 2024 Leipzig
Let's Git!

Bret A. Beheim
babeheim.com
github.com/babeheim










git - program for local version control of repositories

websites for remote repository management:
github.com
gitlab.com
vcs.eva.mpg.de (our institute gitlab)

GUI wrappers for git:
git kraken
github desktop
gitlens plugin for VS 







ctrl + `- opens terminal in VS code


Specific challenge: a colleague asks you to help make their materials ready for publication

project repo:
link: https://share.eva.mpg.de/index.php/s/gRRHDB6jGSHTytd
password: btg+082024 (SHARE ONLY DURING YOUR SESSION)







bash shell navigation:
cd <path/to/folder>
ls
ls -al 
pwd





What's good / bad about the project repo currently?

- unclear sequence of execution?
- under-developed README documentation
- _new _final very confusion
- redudant-seeming copies of each file
- commented-out lines of code and messy notes










Strategy: compact the repo down by liberally deleting and renaming, but version-control each and every move so we can rewind things if we need to.

Git commands:

`git init` - initialize a repo
`git status` - basic command to check the repo's status
`git add <name>` - add specific files to the *stage* (in prep for committing them)
`git reset <name>` - takes a file off the stage
`git commit` - adds the stage to the permanent history of the project 





Important initial configurations:

```bash
git config --global user.name "Bret Beheim"
git config --global user.email "bret_beheim@eva.mpg.de"
git config --global core.autocrlf input # for mac/linux
git config --global core.autocrlf true # for windows
git config --global core.editor "nano -w"
```
