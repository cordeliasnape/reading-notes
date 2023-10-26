Today we learned some Git and HTML basics. I have been enjoying learning these basics so far because I have been feeling confident in my ability. As someone who has been an 'educator' (blegh) for a while, I was feeling apprehensive about going back into education myself.

###### Well, I suppose there is always time to become unconfident, ey?

# Intro to Git

### First, what's a Version Control Software?

Version Control Software (VCS) is a system that allows you to revisit previous versions of a file or project. You can view, track and compare previous modifications made to the file. Git is one of the most popular (if not, _the_ most popular) VCS.

### What is cloning in Git?

‘Cloning’ a Git is creating a copy of an existing Git (including all versions of the file), and make it accessible via a new directory.

First, you must open your 'terminal', which could be Ubuntu or another application depending on your OS.

In order to clone a Git, you can use:

> git clone (link to your GitHub SSH)

But, without the brackets.

### What is the command to track and stage files?

To track one file, you can do the following:

> git add name

To track all files in a repository, ensure an $ is at the beginning of the command and type:

> $ git add \*

To check if a file is staged, type:

> git status

To stage a file, type:

> git add .`

### What is the command to take a snapshot of your changed files?

To commit a snapshot of all modifications to tracked files in the directory, type:

> git commit -a

If you want to _screenshot_ your work, then zoom out and hit:

> command + shift + 3

### Finally, what is the command to send your changed pages over to github?

I have been following this order religiously. Remember, A-C-P (add, commit, push):

> git status

This is to double check all of the changes aren't committed. The files should come up red if they aren't added.

> git add .

This is to add those changes. If you repeat the `git status` command, the files should now be green.

> git commit -m "(your message here")

This is how you commit those changes. The message in the quotation marks should read as a simple but precise reason for your change.

And, finally:

> git push

### And now your git is added to the cloud and, therefore, reflects on GitHub!

Here are my much less detailed notes about [HTML](https://cordeliasnape.github.io/reading-notes/class-04) answering some of the questions from the reading.
