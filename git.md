# Using Git in a Terminal

----

## What is Git?

Before we dive into how to use git, let’s get a better understanding. Git is a distributed version control system that can be operated through a terminal. A version control system keeps records of changes that you make in a file over time, "_commits_". This allows you to be able to go through any commits made to a repository so that you can recall specific edits later if needed. Git allows you to pull your repository from online to your os and so much more when developing a website.

Since git allows us to save all files to a computer before uploading newly edited text to a site, you are able to make changes before hand on any errors or new ideas. This also allows you to work on projects while not having to be connected to the internet or a specific network. Although we are going to be working through a terminal, git is fairly easy to get the hang of!

----

# Developing a Site through Terminal with Git

![Image](https://www.google.com/url?sa=i&url=https%3A%2F%2Fcareerkarma.com%2Fblog%2Flinux-delete-directory%2F&psig=AOvVaw1FPca-E3_HLsCb5ktwNCyb&ust=1628184315811000&source=images&cd=vfe&ved=0CAsQjRxqFwoTCNDjx7jxl_ICFQAAAAAdAAAAABAD)

## Starting off


First things first, we need to make sure Git is downloaded on your computer. If you so happen to have Git on your computer, make sure it is up to date with the latest version available!

#### >[Mac OS](http://git-scm.com/download/mac)

#### >[Windows](http://git-scm.com/download/win)

#### >[Linux](http://git-scm.com/download/linux)

### Claiming your work

Now that we haves Git installed, we need to enter in your user information to mark all the changes you make especially when making commits. 

Type the following into Terminal or Command Line:

```

git config --global user.name "Your name"

git config --global user.email "example@email.com"

```

To make sure you entered everything correctly in settings, enter the following command:

```

git config --global user.name (should return Your name)

git config --global user.email (should return example@email.com)

```

*After completing this, you can run the git `config --list` to see of your changes were saved. Also, it would be best to connect what ever text editor that you are using so it can be opened from the terminal. Depending on the os and text editor, you can find out what git command to use online to tie it in with your terminal! 

### Getting Started with your Repository

Alright, since we have terminal all set up with git and linked to your text editor we need to get your repository up and running to make changes. There are two ways you can go from here to get your repository set up in terminal. We can either clone an existing repository from the web or we can import an existing file off your os into git.

#### Importing

Starting off, we will need to make sure we are in the right directory before importing to git. You can change your directory and then run the initiate command to create a new subdirectory.

```

$ cd yourfilename (cd = change directory)

 Then

$ git init

```

> ##### Now we need to make sure your changes are being tracked! To start tracking these files, perform an initial commit by typing the following:

```

$ git add *.c
$ git add LICENSE
$ git commit -m “any message here”

```



#### Cloning
If you are wanting to pull a repository off line then cloning is the way to go! It is simple as running the clone command with a repository’s URL! Before cloning the file make sure you are in the directory you are wanting to save it to. 

```

$ git clone https://yourrepositors.url

```

After running this command, you officially cloned the file and all of its contents. Git creates all of this in the working directory chosen as a .git file.


----




###### > More Git Commands:

Command| Action
-------|-------
git status| 

----

##### Want to learn more?
###### > [_The Growth Mindset_](https://austinnich.github.io/reading-notes)
###### > [_Markdown_](https://austinnich.github.io/reading-notes/markdown)
###### > [_Text Editors & Terminals_](https://austinnich.github.io/reading-notes/texteditors-terminals)
###### > [_What I Learned_](https://austinnich.github.io/reading-notes/whatilearned)

###### > [_Home_](https://austinnich.github.io/reading-notes/home)