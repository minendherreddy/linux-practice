touch file.txt- will create that file
cat file.txt - will open that file
cat > minnu.txt - will create and open the file and ask the user to write something in the file after completing pressing ctrl+d will exit that.
cat -n file.txt - will print the contents of the file along with the line numbers.
head file.txt- will print the first ten lines of the file.
head -n1 file.txt - will print the first line of the file along with the number.
-n2 => will print first two lines ,-n3 => first three lines along with the number of the line.
etc etc....
tail file.txt - will print the last ten lines of the file.
tail -n1 file.txt - will print the last line of the file.
-n2 - last two lines, -n3 -- last three lines of the file. etc etc.....
head -c1 file.txt - will print only one character(one byte-8 bits) from the file from the starting.
-c2 = two characters, -c3= three characters etc etc.....
tail -c1 file.txt - will print only one character from the file from the last.
-c2= two characters from the last, -c3= three characters from the last.
etc etc....
diff file1.txt file2.txt -- will compare the two files and if there is any change in any line will print those.
example: 
      1c1
      <this is file1
      -------------------
      >this is file2

"<" -- this indicates the contents from the file1
">" -- this indicates the contents from the file2

