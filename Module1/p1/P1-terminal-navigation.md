#!/bin/bash
# P1: Project folder and terminal navigation
# Type these commands one by one in your terminal (this file replays them together).

pwd                                       # where am I?
mkdir web-portfolio                       # create the project folder
cd web-portfolio                          # move into it
mkdir css js images docs                  # create sub-folders
touch index.html about.html css/style.css js/main.js docs/notes.txt
ls                                        # list the contents
echo "<h1>Hello, Web!</h1>" > index.html  # write text into a file
cat index.html                            # print the file
cd css                                    # go down one level
pwd
cd ..                                     # go back up one level
cp docs/notes.txt docs/notes-backup.txt   # copy a file
mv about.html contact.html                # rename (move) a file
rm docs/notes-backup.txt                  # delete a file
find . -name "*.html"                     # search by name
ls -R                                     # recursive listing of everything
cd ~                                      # jump to the home directory
pwd#!/bin/bash
# P1: Project folder and terminal navigation
# Type these commands one by one in your terminal (this file replays them together).

pwd                                       # where am I?
mkdir web-portfolio                       # create the project folder
cd web-portfolio                          # move into it
mkdir css js images docs                  # create sub-folders
touch index.html about.html css/style.css js/main.js docs/notes.txt
ls                                        # list the contents
echo "<h1>Hello, Web!</h1>" > index.html  # write text into a file
cat index.html                            # print the file
cd css                                    # go down one level
pwd
cd ..                                     # go back up one level
cp docs/notes.txt docs/notes-backup.txt   # copy a file
mv about.html contact.html                # rename (move) a file
rm docs/notes-backup.txt                  # delete a file
find . -name "*.html"                     # search by name
ls -R                                     # recursive listing of everything
cd ~                                      # jump to the home directory
pwd
