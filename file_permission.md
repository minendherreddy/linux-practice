sudo chown root:root file.txt -- will the change the owner and group of the file to root and the main usage of sudo is that it will take temporary position of administrator.
mkdir -p new-dir/sub-dir -- will create new-dir as parent directory and sub-dir as sub directory.
ls -l directory -- will list all the files and directories with additional details.(but will not print whats there in the sub directory).
sudo chmod 700 file.txt -- will change the mode of the file to -rwx------.
In this 700 ===> 7= read(4)+write(2)+execute(1);
                 0= nothing.
                 0= nothing.
sudo chown -R root:root directory. -- will the ownership of the directory to root(both owner and group).
chmod 755 directory -- will only change the mode of that directory not the contents in it.
chmod 700 directory -- will change the mode of the entire directory including its contents in it like files and subdirectories.
ls -ld directory -- will only give the details of the directory alone not its contents.
ls -l directory -- will give details of the entire directory including its contents like files and subdirectories.(but not the contents inside the sub directories).
ls -lR directory -- will list all the files and directories including the files inside the subdirectory.
chmod u+x file.txt -- will add execute permission to the user of that file.
chmod g+x file.txt -- will add execute permission to the group of the file.
chmod o+x file.txt -- will add execute permission to others.
chmod a+x file.txt -- will add execute permission to all the members of the file( owner,group,others).
+r -- add read permission.
+w -- add write permission.
-r -- remove read permission.
-w -- remove write permission.
chmod -R u+x directory -- will add execute permission to the all the files and sub-directories of the directory mentioned.
chmod u+x directory -- will only add execute permission to the directory itself.
