# Resume Documentation by Ty Bryant

## Purpose
The goal of this README is to act as a guide for creating, formatting and hosting a resume as a static web site using _Pelican_.
This guided requires no prior knowledge with the working of Git or static site generators.

The goals we want to achieve are:

✅Write your own resume using **Markdown**

✅Generate a static website using **Pelican**

✅Use Git for version control

✅ Deploy the website using **GitHub Paghes**

This document also implements the best practices for technical documentation, outlined by _Andrew Etter_.

## Prerequisites
Before you start creating your static site for your resume, you will need the following installed on your local machine:
1) **Python(3.6)**: Install by going to [python.org](https://www.python.org/downloads)
2) **Operating System**: Widnows 10 or 11, Linux, or macOS
3) **Pelican/Markdown**: Install both by typing on your command line/terminal
   ```
   pip install pelican markdown
   ```
4) **Git**: Install from git-scm.com
5) **Text Editor**: Visaul Studion Code, vim, Typora (this is preference-based)
6) **Forge Account**: Create an account on [GitHub](https://github.com)

Having knowledge already using Markdown would be great to have.

## 📝Instructions

### Step 1: Set up GitHub Repository

Once you have created your own GitHub account, there will be a plus sign in the top right page with a '+' sign. Click on that and you wil be given the option to create your own repository.
Then, give it a name(example: myResume).

Now that you have created your repository, we want to go to our terminal inside our text editor. We want to create a directory to clone our repository to our local machine. Start by running the following commands:
```
mkdir myresume
cd myresume
```
Then, we want to clone our repository into our new directory by running the following command:
```
git clone https://github.com/username/respoitoryname
```

To ensure our repository is connected, you can run the command:
```
git status
```
Or:
```
git remote -v
```
It will give you information indcicating you are inside the proper repository.

### Step 2: Set up Pelican (static site generator)

Our next step is to create our static site generator. We first want to start off by running the following command:
```
pelican quickstart
```




