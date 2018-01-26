﻿# Hello Git

## Farida Wantanyong

### id 5535512041

## 242-320

# SOFTWARE DEVE METHODOLOGIES 


"test branch"

## Setup
$ git config --global user.name "your name"

$ git config --global user.email "your email"

$ git config --list // แสดง config

## Create
$ git init // สร้าง .git และ repo เปล่า

$ git status // แสดงสถานะ

$ git echo "your message" >> {your file} // สร้างไฟล์

$ git add {your file}

$ git add . // เพิ่มทั้งหมด

$ git add '*.txt' // เพิ่มแฉพาะสกุลไฟล์

$ git commit -m "your message"

$ git log // แสดงการทำงาน

$ git log --oneline // แสดงการทำงานแบบย่อ

## Reset
$ git checkout {file name} // กู้คืนไฟล์

$ git reset {file name} // กู้คืนไฟล์ หลัง add

$ git reset --soft HEAD~1 // กู้คืนไฟล์ หลัง commit

??? git reset --soft "HEAD^"

??? git reset --soft {file name}

## Branch
$ git branch // ดู branch

$ git branch -a // ดู branch ทั้งหมด

$ git branch {branch name} // สร้าง branch

$ git checkout {branch name} // สลับ branch

$ git checkout -b {branch name} // สร้างและสลับ branch

$ git push origin {branch name} // อัพ branch ขึ้น server

$ git merge {branch name} // รวม bracnh กับ master *(ทำใน master)

$ git checkout {branch name} {file name} // ย้ายไฟล์จาก branch ต้นทาง **(สลับมาอยู่ใน branch ปลายทางก่อน)

$ git branch -d {branch name} // ลบ branch

$ git merge --no-ff {branch name} // รวมไฟล์จาก branch

$ echo "ข้อความ" >> ชื่อไฟล์

$ git add .

$ git commit -m "???"

$ git push origin {branch name}

$ git merge -- 

## Repo
$ git remote add origin {your repo url} // remote ไปยัง repo ที่สร้าง

$ git remote -v // ตรวจสอบการ remote

$ git push -u origin master // การส่งถึง github ครั้งแรก

## Other
$ git fetch // เปรียบเทียบ

$ git merge origin/master // อัพเดท


$git merge --no-ff {branch name}

$ git pull // การ fetch+merge

$ git clone {git url}

$ git remote add upstream {git url}

$ git fetch upstream

$ git merge upstream/master

$ git more {file name} // แสดงรายละเอียดไฟล์

$ git rm {file name} // ลบไฟล์

??? git stash

??? git stash pop

## Logout
$ git config --global --unset user.name

$ git config --global --unset user.email


## TAG
$ git tag {tag name}  // ส่วนมากตั้งชื่อเป็น vesrion

$ git status

$ git push --tags

$ git checkout {commit number}

$ git checkout {ชื่อ tag}   // การกลับมา tag เดิม

$ git log --oneline --decorate --graph

$ git tag -d {name tag} // การลบ tag

$ git push origin --delete {ชื่อ tag}


##check การแก้ไขไฟล์

$ git log --oneline

