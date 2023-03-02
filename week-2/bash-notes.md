# Start of the assignment 
ls- la # to list all directories and files
cd benjamin-dzanovic-devops-mentoriship #to access working dir
git branch week-2-bandit-labs # to create a new branch for week 2
git checkout week-2-bandit-labs # to switch from main branch to newly created branch
mkdir week-2 # to create week-2 directory
cd week -2 # to go inside week-2 directory
touch bash-notes.md # to create new file
ls -la # to list all files inside week -2 dir (to check if recent file was created)
code - to run vsc
# read instruction from Overthewire for LVL 0 to LVL 1
ssh bandit0@bandit.labs.overthewire.org -p 2220 # used ssh command  to connect to bandit0
entered password from the istructions for level 0 than successfully connected
pwd # we are using pwd to check in which directory we are currently at
cd .. # to go back one step to recent directory 
ls -la # to list all directories and files
find /home -name readme # to find all readme files in home directory
cd bandit0 # to go inside bandit0 directory
ls -la # to list all dir and files
cat readme # to list all data inside readme file
logout # to log out from bandit0
ssh bandit1@bandit.labs.overthewire.org -p 2220 # used ssh command  to connect to bandit1 using obtained password from readme file
# We are on LVL 1 to LVL 2
ls -la # contains file "-"
cat - # I got stuck in terminal and used CTRL + Z
cat < - # to list data inside "-" file
logout
ssh bandit2@bandit.labs.overthewire.org -p 2220
# We are now on LVL 2 to LVL 3
find /home -name "spaces in this filename"
ls -la
cat "spaces in this filename"
aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG
logout
ssh bandit3@bandit.labs.overthewire.org -p 2220 
# We are now on LVL 3 to LVL 4
ls -la 
cd inhere
cat .hidden
2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe
logout
ssh bandit4@bandit.labs.overthewire.org -p 2220 
# We are now on LVL 4 to LVL 5
ls -la 
cd inhere 
cat < -file00 -> went through all files and found password in file07
lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR
logout
ssh bandit5@bandit.labs.overthewire.org -p 2220 
# We are now on LVL 5 to 6
ls -la 
cd inhere 
ls -la
find -size 1033c # to find all files with size 1033c
cd inhere/maybehere/
cat .file2 
P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU
logout
ssh bandit6@bandit.labs.overthewire.org -p 2220 
# We are now on LVL 6 to LVL 7
find ./ home -user bandit7 -group bandit6 -size 33c # found the all files with predetrmined conditions
cd var/lib/dpkg/info/ # only file with permissions to read
cat bandit7.password
z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S
logout
ssh bandit7@bandit.labs.overthewire.org -p 2220
# We are now on LVL 7 to LVL 8
ls -la
cat data.txt | grep -n "millionth"
TESKZC0XvTetK0S9xNwm25STk5iWrBvP
logout
ssh bandit8@bandit.labs.overthewire.org -p 2220
# We are now on LVL 8 to LVL 9
cat -n data.txt # to list all data with the lines 
cat data.txt | sort | uniq -u # this is used to list all uniq lines inside data.txt
cat data.txt | grep -n "EN632PlfYiZbn3PhVK3XOGSlNInNE00t" # I wanted to see in which line is value stored
logout
ssh bandit9@bandit.labs.overthewire.org -p 2220 
# We are now on LVL 9 to LVL 10
cat data.txt | grep "==*" # binary file matches
cat data.txt | grep -a "==*" # we got the result
G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s
logout
ssh bandit10@bandit.labs.overthewire.org -p 2220
# We are now on LVL 10 to LVL 11
ls -la
cat data.txt # tried to use this result it doesnt work so google it
cat data.txt | base64 -d
6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM
logout
ssh bandit11@bandit.labs.overthewire.org -p 2220