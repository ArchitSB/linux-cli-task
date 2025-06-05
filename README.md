# Linux CLI Task Report

## Task 1: Create and Rename Files

**Commands Used:**
```bash
mkdir test_dir
cd test_dir
touch example.txt
mv example.txt renamed_example.txt


cat /etc/passwd > cat_output.txt
head -n 5 /etc/passwd > head_output.txt
tail -n 5 /etc/passwd > tail_output.txt


grep "root" /etc/passwd > grep_output.txt


sudo nala install zip unzip -y
zip -r test_dir.zip test_dir
unzip test_dir.zip -d unzipped_dir


wget https://www.learningcontainer.com/wp-content/uploads/2020/04/sample-text-file.txt


touch secure.txt
chmod 444 secure.txt


export MY_VAR="Hello, Linux!"
echo $MY_VAR > env_var_output.txt


mkdir screenshots


![All Tasks Screenshot](screenshots/tasks.png)