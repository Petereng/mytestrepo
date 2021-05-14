# mytestrepo
Lesson 3 recap
# remember the sequence
## git config --global user.name "petereng"
## git config --global user.email "petereng@bigpond.net.au"

# git clone https://github.com/Petereng/mytestrepo.git

# Daddio@livingroom MINGW64 ~/mytestrepo (main)
# $ cd ..

# Daddio@livingroom MINGW64 ~
# $ pwd
# /c/Users/Daddio

# Daddio@livingroom MINGW64 ~
# $ cd mytestrepo

# Daddio@livingroom MINGW64 ~/mytestrepo (main)
# $ git status
# On branch main
# Your branch is up to date with 'origin/main'.

# nothing to commit, working tree clean

# Daddio@livingroom MINGW64 ~/mytestrepo (main)
# $ mkdir data

# Daddio@livingroom MINGW64 ~/mytestrepo (main)
# $ ls
# README.md  data/

# Daddio@livingroom MINGW64 ~/mytestrepo (main)
# $ mkdir references code

# Daddio@livingroom MINGW64 ~/mytestrepo (main)
# $ ls
# README.md  code/  data/  references/

# addio@livingroom MINGW64 ~/mytestrepo (main)
# $ cd code

# Daddio@livingroom MINGW64 ~/mytestrepo/code (main)
# $ touch .gitkeep

# Daddio@livingroom MINGW64 ~/mytestrepo/code (main)
# $ cd ..
# cd
# Daddio@livingroom MINGW64 ~/mytestrepo (main)
# $ cd data

# addio@livingroom MINGW64 ~/mytestrepo/data (main)
# $ touch .gitkeep

# Daddio@livingroom MINGW64 ~/mytestrepo/data (main)
# $ cd ..

# Daddio@livingroom MINGW64 ~/mytestrepo (main)
# $ cd references

# Daddio@livingroom MINGW64 ~/mytestrepo/references (main)
# $ touch .gitkeep

# Daddio@livingroom MINGW64 ~/mytestrepo/references (main)
# $ cd ..

# Daddio@livingroom MINGW64 ~/mytestrepo (main)
# $ ls
# README.md  code/  data/  references/

# Daddio@livingroom MINGW64 ~/mytestrepo (main)
# $ pwd
# /c/Users/Daddio/mytestrepo

# Daddio@livingroom MINGW64 ~/mytestrepo (main)
# $ cd references

# Daddio@livingroom MINGW64 ~/mytestrepo/references (main)
# $ touch info.txt

# Daddio@livingroom MINGW64 ~/mytestrepo/references (main)
# $ ls
# info.txt

# Daddio@livingroom MINGW64 ~/mytestrepo/references (main)
# $ cd ..

# Daddio@livingroom MINGW64 ~/mytestrepo (main)
# $ git status
# On branch main
# Your branch is up to date with 'origin/main'.

# Untracked files:
#   (use "git add <file>..." to include in what will be committed)
#         code/
#         data/
#         references/

# nothing added to commit but untracked files present (use "git add" to track)

# Daddio@livingroom MINGW64 ~/mytestrepo (main)
# $ git add .

# Daddio@livingroom MINGW64 ~/mytestrepo (main)
# $ git status
# On branch main
# Your branch is up to date with 'origin/main'.

# Changes to be committed:
#   (use "git restore --staged <file>..." to unstage)
#         new file:   code/.gitkeep
#         new file:   data/.gitkeep
#         new file:   references/.gitkeep
#         new file:   references/info.txt

# Daddio@livingroom MINGW64 ~/mytestrepo (main)
# $ git commit -m 'Added folders into repo and text file'
# Author identity unknown

# *** Please tell me who you are.

# Run
# 
#   git config --global user.email "you@example.com"
#   git config --global user.name "Your Name"

# to set your account's default identity.
# Omit --global to set the identity only in this repository.

# fatal: unable to auto-detect email address (got 'Daddio@livingroom.(none)')

# Daddio@livingroom MINGW64 ~/mytestrepo (main)
# git config --global user.name "Petereng"

# Daddio@livingroom MINGW64 ~/mytestrepo (main)
# git config --global user.email "Petereng@bigpond.net.au"

# Daddio@livingroom MINGW64 ~/mytestrepo (main)
# $ git commit -m 'Added folders into repo and text file'
# [main b4ad85f] Added folders into repo and text file
#  4 files changed, 0 insertions(+), 0 deletions(-)
#  create mode 100644 code/.gitkeep
#  create mode 100644 data/.gitkeep
#  create mode 100644 references/.gitkeep
#  create mode 100644 references/info.txt

# Daddio@livingroom MINGW64 ~/mytestrepo (main)
# $ git status
# On branch main
# Your branch is ahead of 'origin/main' by 1 commit.
#   (use "git push" to publish your local commits)

# nothing to commit, working tree clean

# Daddio@livingroom MINGW64 ~/mytestrepo (main)
# $ git push
# Enumerating objects: 6, done.
# Counting objects: 100% (6/6), done.
# Delta compression using up to 8 threads
# Compressing objects: 100% (3/3), done.
# Writing objects: 100% (5/5), 438 bytes | 146.00 KiB/s, done.
# Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
# To https://github.com/Petereng/mytestrepo.git
#    17dbb77..b4ad85f  main -> main

# Daddio@livingroom MINGW64 ~/mytestrepo (main)
# $ ls
# README.md  code/  data/  references/

# Daddio@livingroom MINGW64 ~/mytestrepo (main)
# $ code readme.md

# Opened readme.md in VSCode app
# Added a descirption of the steps above into the readme file
# Saved the readme.md file in VSCode
# 
