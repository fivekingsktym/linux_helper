# linux Commands


pwd  #present working directory
ls #listing contents inside a directory 

lscpu # showing system details
lsb_release -a # showing linux version

cd # change directory
touch file_name.extension #creating a file in linux

mkdir folder_name # creating a folder in linux
# creating both folder and file inside the created folder
mkdir folder_name && touch file_name.extension
# example 
myfolder && touch myfolder/file.txt

# writing a line to a file 
echo "print("hello world")" > sample.py
# showing the contents from a file
cat sample.py

# elevate privileges and obtain a root or superuser access.
# By default, if you execute su without specifying a username, it will switch to the root user.
# <SuperUserDo> <Substitute User>
sudo su



# extracting .tar file to a directory
tar -xf <file_for_extraction.tar> -C <fullpath_or_folder_name>
# example
tar -xf php-crud-app.tar -C php-crud-app