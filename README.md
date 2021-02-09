# Terminal Coursework

In this coursework we want to test what you've learnt in the previous coursework.

## Tasks

### 1) Find my script

In this repository you'll find `MyDocuments` - this is all the documents that I use on my laptop.

I need to find the `script.js` file that is a part of MyFirstWebsite however you are **not** allowed to use a GUI, you must use Command Line and the Terminal.

What commands would I need to change directory to the directory containing `script.js`? In the section below, write all the commands you used.

Hint: You should use `cd` and `ls`.

#### 1) Answer
Solution - 1
pwd
ls
cd MyDocuments
ls
cd MyProjects
ls
cd MyFirstWebsite
ls
cd scripts
ls

Solution - 2
cd MyDocuments/Projects/MyFirstWebsite/scripts

### 2) Find my Hotel Photo

Great work!

Next, I want to try and find the photo of my hotel from my holiday in July that I want to send to a friend.

**Note**: You should do this by moving from where you are after completing the previous task.

#### 2) Answer
Solution - 1
pwd
cd
ls
cd MyDocuments
ls
cd Photos
ls
cd HolidayJuly
ls
cd Hotel
ls

Solution - 2
cd
cd MyDocuments/Photos/HolidayJuly/Hotel

Solution - 3
pwd
cd ..
ls
cd ..
ls
cd ..
ls
cd Photos
ls
cd HolidayJuly
ls
cd Hotel
ls

Solution - 4
cd ../../../Photos/HolidayJuly/Hotel

### 3) Counting Script

Next, I want you to run the script in this directory

```
/MyDocuments/Scripts/
```

You can run the script by typing

```
./count_to_100.sh
```

when you're in the correct directory.

For this task, I want you to **stop** the counter when I have counted to 10.

#### 3) Answer

Copy the output of the script here

I have counted to 1
I have counted to 2
I have counted to 3
I have counted to 4
I have counted to 5
I have counted to 6
I have counted to 7
I have counted to 8
I have counted to 9
I have counted to 10

### 4) Quiz

In this directory you'll find a quick quiz for you to complete

```
/MyDocuments/Quiz
```

You should open the quiz in Visual Studio Code and complete it. You can do this either by opening this project in VSCode or by running the command

```sh
code QUIZ.md
```

when you're in the correct directory.
