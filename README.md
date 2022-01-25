# Index
- [Getting Started with GitHub](#getting-started-with-github)
- [Documentation with Markdown](#documentation-with-markdown)
- [Installation of CentOS 7 or 8](#installation-of-centos-7-or-8)
# Getting Started with GitHub

## **1. Creating Your GiHub Account**
Creating your own GitHub Account is similar to creating acoounts on most social media websites we see today. You can join GIHub by using the following [link](https://github.com/join).


## **2. Creating a New Repository & adding README.md**
Now we have to create a repository where all the documentation of all your work will be done. The detailed guidelines in creating a repository and adding the **README.md** file are given in the [link](https://help.github.com/articles/create-a-repo/).

```Note: While creating the repository for the program's purpose make sure you name the repository in "<Your Name>_STP" format and it must be a private repository with "Synopsys University Program - MEC" as the collaborator.```

## **3. Cloning to a local repository**
Now we have to clone the repository to our local machine. The detailed guidelines in cloning a repository are given in the [link](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository).
## **4. Saving your work and pushing it to the remote repository**
Now we have to save our work and push it to the remote repository. This is done using the ```git add``` , ```git commit``` and ```git push``` commands. All of which are explained in the git cheatsheet given in the following [link](https://education.github.com/git-cheat-sheet-education.pdf).


```Note: All the basic commands required to work with git is given in the cheatsheet and the link to the same is given below.``` [Link to the cheatsheet](https://education.github.com/git-cheat-sheet-education.pdf)

<br>

# Documentation with Markdown

## What is Markdown?
Markdown is a lightweight markup language that is easy to read and write. It is a plain text format that is used to create HTML and XML documents. GitHub and all other git plaform has great Mardown rendering systems that can be utilized for documentation. Here also we'll be using markdown for the documentation your progress in the course.

## Working with Markdown
---

Markdown is easy to learn and understand and is really close to HTML. Here instead of tags we use alternative syntax for font adjustments. The syntax rules are for using markdown can be easily learnt using any of the following links:

- [Link 1](https://guides.github.com/features/mastering-markdown/)
- [Link 2](https://www.markdownguide.org/basic-syntax/#html)

Once cloned to your local repository you can document in markdown using any of your favourite editor. Incase, you are using Visual Studio Code as your editor then you might find a extension named **"Markdown All in One"** to be handy. This extension will simultaniously render out the markdown in a tab as and when you type as shown in the picture below. 

![Markdown Screenshot](assets/images/markdown-sc.png)

# Installation of CentOS 7 or 8
CentOS is Red Hat Enterprise Linux (RHEL) based linux distribution which is the preffered OS for this training program.

## Installation Guide
### Dual Boot
-For systems with **RAM <= 4GB** Dual Booting is preferred

-Dual booting is a bit of a tedious procedure and should be done with caution.

-[CentOS 8 ISO Image for Dual Boot](http://centos.mirror.snu.edu.in/centos/8.5.2111/isos/x86_64/CentOS-8.5.2111-x86_64-dvd1.iso)
Following is the Centos 8 ISO Download file.

-Please refer to youtube tutorials/blogs on the same before dual booting.

**NB:**
-Ensure that you allot a minimum of 80GB space for CentOS while partitioning.

-Also select GNOME Desktop in the software selection part of installation.

---

### As Virtual Machine

-For systems with **RAM >=8 GB** ,the preferred method is to use CentOS 7/8 on Virtual Box as a virtual machine.

-Please refer this video for installing CentOS 8 on Virtual Box
[Video](https://drive.google.com/file/d/15JicnQ1KCNRqsKHVXz3NNeKctcVznMzK/view?usp=sharing)

While installing,make sure to select "Workstation" in software selection area which is not shown in the video

![Installation](assets/images/Installation.png)![Workstation](assets/images/Workstation.jpeg)



-**Key Points:**
1. Allot memory size(RAM) in virtual box based on your system spec and the host OS.
eg. For Windows users with 8GB RAM you may allot upto 4GB.
Note that bare minimum of 2 GB is recommended for smooth performance.

2. Recommended size for Virtual Hard Disk is 60 GB
