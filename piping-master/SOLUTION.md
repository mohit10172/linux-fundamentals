#TASK 1

- Step 1:   `ls /etc`
- Step 2:   `ls /run`
- Step 3:   `ls /etc 1> file1.txt`
- Step 4:   `ls /run 1> file2.txt`

#TASK 2

- Pipeline:   `cat file1.txt file2.txt | tee unsorted.txt | sort -r > reversed.txt`

