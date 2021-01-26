# Git Introduction

![git logo](https://miro.medium.com/max/800/1*Jl2VDHVzFBDdXggRprziUg.png)
Photo by [medium.com](https://miro.medium.com/max/800/1*Jl2VDHVzFBDdXggRprziUg.png)
---

If you want to get started on learning about Git technology let me start by telling you that it will take like 30 min minimumThere are many customers for Git.
The technology is all the equal no matter the client.

## Let’s get started! You are going to love this.

1. What is Version Control?

> Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later. So ideally, we can place any file in the computer on version control.

A Version Control System (VCS) allows you to revert files back to a previous state, revert the entire project back to a previous state, review changes made over time, see who last modified something that might be causing a problem, who introduced an issue and when, and more. Using a VCS also means that if you screw things up or lose files, you can generally recover easily.

Git also helps you synchronise code between multiple people. So imagine you and your friend are collaborating on a project. You both are working on the same project files. Now Git takes those changes you and your friend made independently and merges them to a single “Master” repository. So by using Git you can ensure you both are working on the most recent version of the repository. So you don’t have to worry about mailing your files to each other and working with a ridiculous number of copies of the original file. And collaborating long distance becomes as easy as HTML ?.

## History of Git

Git traces its roots to the open source software project Linux kernel. Developers of this project began using a DVCS called BitKeeper in 2002. In 2005, many of these developers stopped using this DVCS due to tension between the Linux kernel community and the company behind BitKeeper’s and the eventual revocation of the DVCS’ gratis status. Subsequently, Linus Torvalds, the chief architect of the Linux kernel, began creating Git. With the intention of creating a DVCS with a workflow design similar to that of BitKeeper, which was also fast, Git allowed for non-linear development via multiple branches, could support large projects, possessed strong mechanisms preventing corruption, and had a simple design. Since its inception in 2005, Git has become one of the most utilized Version Control Systems in the world.

## Practical introduction by example

We're going to walk you through an example. The things we show you here will teach you all you need toknow to collaborate on your team project using Git.

Importing

To import an existing project or directory into Git, follow these steps using the Terminal or Command Line:

    Switch to the target project’s directory

    Example:

    <pre><code>$ cd test (cd = change directory)</code></pre>

    Use the git init command

    <pre><code>$ git init</code></pre>
    

    Note: At this stage, you have created a new subdirectory named .git that has the repository files. Tracking has not commenced.
    To start tracking these repository files, perform an initial commit by typing the following:

    <pre><code>$ git add *.c</code></pre>

    <pre><code>$ git add LICENSE</code></pre>

    <pre><code>$ git commit -m “any message here”</code></pre>

Now, your files are tracked and there’s an initial commit. We will discuss the particular commands in detail soon.
Cloning

You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL:

<pre><code> $ git clone https://github.com/test </code></pre>

By cloning the file, you have copied all versions of all files for a project. This command leads to the creation of a directory called “test,” with an initialized .git directory inside it, which has copies of all versions of all files for the specified project. The command also automatically checks out — or retrieves for editing — a copy of the newest version of the project.

To clone a repository into a directory with another name of your choosing, use the following command format:

<pre><code> $ git clone https://github.com/test mydirectory</code></pre>

The command above makes a copy of the target repository in a directory named “mydirectory.”

Saving Changes

All files in a checked out (or working) copy of a project file are either in a tracked or untracked state.

Tracked

Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot.

Untracked

Untracked files were not in the last snapshot and do not currently reside in the staging area.

*After cloning a repository, files have tracked status and are unmodified because they have been checked out but not edited.
The Life Cycle of File Status

1. After you edit a file, Git flags it as modified because of changes made after the previous commit.
2. You stage the modified file.
3. Then, you commit staged changes.

This is only a brief you can check the whole thing from [Udemy](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#1)
