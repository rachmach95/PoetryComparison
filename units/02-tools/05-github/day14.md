# Day 14 – GitHub & Version Control

## Questions As You Prepare For Class
	
## Today's Outline

I want to talk about GitHub, today, which is a industrial-strength concurrent versioning system that we will be using for the next few weeks. Let's first talk about what GitHub is.

### Concurrent Versioning System

GitHub is a social networking site for hosting Git repositories. GitHub is a *concurrent versioning repository*.

**What does that mean?**

1. *concurrent*—Multiple users can work on the same file at once.
1. *versioning*—Git automatically tracks and versions changes to individual files
1. *repository*—With GitHub, files are saved in a central, online location

### What is it For?

Git allows you to store a central or "master" version of your (or your team's) work while keeping local "clones" that you can edit on your own time. GitHub hosts these repositories (for free) and gives it all a nice visual, online interface.

* Share code
* Fix or report bugs
* Store documentation alongside code
* Manage users working on the same files
* Automate communication among group members
* Generate and host static websites with GitHub pages

### Getting Started

1. Sign-up for an account at [GitHub.com](https://www.github.com).
	* You will need to enter a username (I'm *oncomouse* on here)
	* You will need to enter an email
	* You will need to create a password
	* **Note:** I cannot force you to use your real name in this class, as portions of this tutorial are public.
1. Wait for the verification email and follow the instructions
1. When asked, choose "Unlimited public repositories for free" and click "Continue"
1. If you want private repositories but don't feel like paying, you can get a free [Education Pack](http://education.github.com)
1. You will be asked to enter some personal info

### My First Repo

The [GitHub Hello World Guide](https://guides.github.com/activities/hello-world/) is a good place to start.

Spend the remainder of class (and tonight if you need to) working through this.

### For Friday (Or Now)

Now that you have learned how to create repositories and pull requests, you are reading for one last task: forking.

One of the main, powerful features of GitHub is that any repository can be "forked" creating a repository that you own instead of one that someone else owns. You can use this feature to submit bug fixes to others' code, for instance.

To fork a repository, vist the repo's main page (such as [this one for our course](https://github.com/oncomouse/engl460fall2017)) and, in the upper right corner, click the button that says "Fork". After a bit of work, this will create a repository that you own and the url will change from `https://github.com/oncomouse/engl460fall2017` to `https://github.com/<your-username>/engl460fall2017`.

Changes you make to this repository can be sent to my repo by a pull request.

I've added a sign-in sheet (`sign-in.md`) to the repo. Fork my repo, edit it by adding your first name, and then issuing a pull request to my repo with this edit.

#### Procedure

1. Visit [https://github.com/oncomouse/engl460fall2017](https://github.com/oncomouse/engl460fall2017) and click the "Fork" button in the upper right.
1. After it finishes, edit `sign-in.md` and add your first name or handle.
1. Save and commit the changes, as per normal.
1. Visit [https://github.com/oncomouse/engl460fall2017](https://github.com/oncomouse/engl460fall2017) again and click "New Pull Request", which is on the left, right about the list of files.
1. Click the link that reads "Compare Across Forks"
1. For the base branch, choose your repo (`<your-username>/master`) and for the head branch, choose `oncomouse/master`
1. Click "Create pull request" and fill out the forms. Once it is submitted, I will have a record that you have completed the assignment.
