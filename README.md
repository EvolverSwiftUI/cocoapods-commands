# cocoapods-commands

<br><br>

To install cocoapods in global level
====> sudo gem install cocoapods
<br><br>

To install cocoapods in global level at specific version
====> sudo gem install cocoapods -v 1.10.2
<br><br>

To uninstall cocoapods in global level
====> sudo gem uninstall cocoapods
<br><br>

To check the version of cocoapods installed the current machine or macbook
====> pod --version
<br><br>

Question:
To get back to down version of cocoapods the required steps is as below
<br><br>

Step 1 - uninstall cocoapods using the command ====> sudo gem uninstall cocoapods
<br><br>

Step 2 - make sure the pod directory is removed in the machine using the command ====> pod --version ===> it will give response like folder is not found
<br><br>

Step 3 - so now install the down version by using the command ====> sudo gem install cocoapods -v 1.10.2
<br><br>

Step 4 - now check the version of cocoa pods with the command ====> pod --version
<br><br>

<br>
get swift version ===> swift --version
<br>
get ruby version ====> ruby -v
<br>
get pod version ===> pod --version
<br>
add fastlane file ===> fastlane init
<br>
add .gitignore file ===> touch .gitignore
<br>
add pod file ===> pod init
<br>

<br> Shell Script Basics

<br>
to get list of contents ===> ls
<br>
to get additional or more details of contents ===> ls -l -h
<br>
date ==> displays ssystem date and time 
<br>
whoami ===> displays who is logged as current user
<br>
--help ===> displays list of options to the given command
<br>
man ====> displays user manual for given command
<br>
clear ===> clears the shell
<br>
history ===> shows last five hundreads of commanmds
<br>
exit ====> ends the shell
<br>
<br>
<br>
Shell Script using on Files and Folders
<br>
<br>
touch <placeholder for file name> ===> creates an empty file
<br>
Eg: <br>
touch Sample.txt  
<br>  
cat Sample.txt ===> reads the content from that file
<br>
echo "Hello, World!" ===> used to print something on console window.  
<br>
write content into the file using ">" symbol ===> echo "Hello, World!" > Sample.txt
<br>
  mv Sample.txt Test.txt ===> it will used to rename file from source to destination.
  <br>
  cp src_file dest_file ===> cp Test.txt fun_text.txt ===> it copies content from source file to destination file.
  <br>
  rm Test.txt ===> removes file from that folder or directory
  <br>
  ls -a ===> get all files along with hidden files or folders also
  <br>
  . ===> single dot ===> represents the current directory
  .. ===> double dot ===> represents the parent directory
 <br>
  <br>
  <br>
  Working with Directories
  <br>
  <br>
  mkdir tutorials ===> like empty file on touch command, it will also creates an empty directory
  <br>
  pwd ===> gives the current working directory name
  <br>
  cd ./tutorial ===> used to change the current working directory 
  <br> ===> . means current directory and /tutorial means go to inside of tutorial directory of current directory
  <br>
  cd .. ===> change directory to parent directory from current directory
  <br>
  <br>
  File Paths:
  <br>
  1. Absolute Path ===> path from root folder to current file or folder
  <br>
  2. Relative Path ====> path from current directory to other file or folder
  <br>
  <br>
  <br>
  cd ~ ===> used to move to your home directory
  <br>
  cd  ===> also used to move to your home directory
  <br>
  cd / ===> used to move to root directory, but not your home directory. remember this point
  <br>
  difference between root directory and home directory?
  <br>
  home directory ===> created for every logged in used inside root directory
  <br>
  root directory ===> root directory is common for every logged in uses, by default it is same as "/"
  <br>
  mv src_folder dest_folder ===> rename directory
  <br>
  mv src_file dest_folder ===> used to move file to folder
  <br>
  cp src_file dest_folder ====> used to copy src file to destination folder
  <br>
  cp -r src_folder dest_folder ====> used to create a copy of folder
  <br>
  rm -r directory_name ===> removes the directory or folder
  <br>
  
  <br>
  nano filename ===> it opens file in command line interface
  <br>
  cnrl + O and enter ===> it shows how many lines writteen on that file
  <br>
  cntl + X ===> closes the file and returns to terminal window
  <br>
  
  <br>
  <br>
  Filtering and Output Redirection
  <br>
  <br>
  
  head -2 sentence.txt ===> by default it returns first 10 lines of file, but here we mention 2 so it written first 2 lines of file.
  <br>
  tail -3 sentence.txt ===> by default it returns last 10 lines of file, but here we mention 3 so it written last 3 lines of file. 
  <br>
  grep
  <br>
  wc sentence.txt ===> returns number of lines, numbeer of words, number of characters in that file.
  <br>
  
  <br>
  Pipiing ===> "|"
  <br>
  <br>
  by using piping(|) we can execute multiple commands.
  <br>
  cat sentence.txt | head -2  ====> here cat command reads all content and head command now take as input and returns output as first 2 lines.
  <br>
  
  
  
  
  
