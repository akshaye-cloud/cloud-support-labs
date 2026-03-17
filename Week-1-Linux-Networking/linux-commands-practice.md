# Linux Commands Practice

This document contains the Linux commands practiced during Week 1.

---

## Navigation Commands

pwd -> Show current directory

ls -> List files

ls -l -> List files with details

ls -a -> List hidden files

cd folder-name -> Change directory

---

## File and Directory Commands

mkdir test-folder -> Create directory 

touch file.txt -> Create file 

cp file.txt newfile.txt -> Copy file

mv file.txt renamed.txt -> Move or rename file

rm file.txt -> Delete file

rm -r folder-name -> Delete folder with contents

---

## File Viewing Commands

cat file.txt -> View file content

less file.txt -> View file page by page

head file.txt -> View first lines

tail file.txt -> View last lines

---

## Permissions

chmod 755 script.sh -> Change permissions

chown user file.txt -> Change owner

Permission meaning
r = read
w = write
x = execute

---

## Service Management

sudo systemctl start nginx -> Start service

sudo systemctl stop nginx -> Stop service

sudo systemctl status nginx -> Check service status

sudo systemctl restart nginx -> Restart service
