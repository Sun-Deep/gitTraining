## Git
- Git is a Version Control System that keeps track of all the changes to your project files, allowing you to work with your team on the same code while saving you a lot of confusion that tends to happen when multiple people are editing the same files. 
- Git stores every record of every change that you or someone else makes to the project, and this makes keeping track of your progress easy. 
- If you need to look at your old code, or if you need to see what or who modified it – the record is always there.


## Github
- GitHub acts as remote storage for your Git repositories provides a really neat and simple way for people to collaborate and contribute to development projects. 
- It’s a place where you can play and experiment. 
- It’s a place where you can find the most incredible open-source information, emerging technologies, features, and designs. It’s a place to learn and it’s a place to get involved. 

## Why github 

* Save Time: Git is lightning fast. And although we're talking about only a few seconds per command, it quickly adds up in your work day. Use your time for something more useful than waiting for your version control system to get back to you.

* Work Offline: What if you want to work while you're on the move? With a centralized VCS like Subversion or CVS, you're stranded if you're not connected to the central repository. With Git, almost everything is possible simply on your local machine: make a commit, browse your project's complete history, merge or create branches... Git let's you decide where and when you want to work.

* Undo Mistakes: People make mistakes. A good thing about Git is that there's a little "undo" command for almost every situation. Correct your last commit because you forgot to include that small change. Revert a whole commit because that feature isn't necessary, anymore. And when the going gets tough you can even restore disappeared commits with the Reflog - because, behind the scenes, Git rarely really deletes something. This is peace of mind.

* Don't Worry: Git gives you the confidence that you can't screw things up - and this is a great feeling. In Git, every clone of a project that one of your teammates might have on his local computer is a fully usable backup. Additionally, almost every action in Git only adds data (deleting is very rare). That means that losing data or breaking a repository beyond repair is really hard to do.

* Make Useful Commits: A commit is only really useful if it just contains related changes. Imagine having a commit that contains something from feature A, a little bit of feature B, and bugfix C. This is hard to understand for your teammates and can't be rolled back easily if some of the code is causing problems. Git helps you create granular commits with its unique "staging area" concept: you can determine exactly which changes shall be included in your next commits, even down to single lines. This is where version control starts to be useful.

* Work in Your Own Way: When working with Git you can use your very own workflow. One that feels good for you. You don’t have to be a code acrobat to qualify for using Git. Of course, you can connect with multiple remote repositories, rebase instead of merge, and work with submodules when you need it. But you can just as easily work with one central remote repository like in Subversion. All the other advantages remain – regardless of your workflow.

* Don’t Mix Things Up: Separation of concerns is paramount to keeping track of things. While you’re working on feature A, nothing (and no-one) else should be affected by your unfinished code. What if it turns out the feature isn’t necessary anymore? Or if, after 10 commits, you notice that you took a completely wrong approach? Branching is the answer for these problems. And while other version control systems also know branches, Git is the first one to make it work as it should: fast & easy.

## Some of Git and Github terminologies

> GitHub Glossary #1: What is Repository?
* The most fundamental element of GitHub, a repository is essentially a project’s folder, much like the kind of folder you would see in a Dropbox or Google Drive folder.  
* Repositories store every single project file, its documentation and its revision history of every document. 
* Repositories can also accept multiple private or public collaborators.

> GitHub Glossary #2: What is Commit?
* Commits are easily one of the most frequented activities by a developer using GitHub. 
* Simply put, a commit or revision is like ‘saving’ an updated file to its original folder and overwrites an older version. 
* It's like when you save a file, except with Git, every time you save it creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record of what changes were made when and by who. 
* Commits usually contain a commit message which is a brief description of what changes were made. 

> GitHub Glossary #3: What is Clone?
* Clones are literally clones (copies) of a repository that sit on the developer’s computer instead of a server elsewhere.
* Clones are great since you can download a code file to tinker around with offline or to be edited in a preferred code editor or integrated development environment.

> GitHub Glossary #4: What is Branch?
* A branch is a parallel version of a repository (ie; it literally branches out or away from the main repository, kind of like a temporary sub-folder).
* It is contained within the repository, but does not affect the primary or master branch allowing you to work freely without disrupting the "live" version.
The beauty about ‘branches’ is that you can merge it back into the master branch when you’re ready to publish your changes.

> GitHub Glossary #5: What is Fetch?
* Fetching refers to getting the latest changes from an online repository (like GitHub.com) without merging them in. Once these changes are fetched you can compare them to your local branches (the code residing on your local machine).

> GitHub Glossary #6: What is Fork
* According to help.github.com, a ‘fork’ is a personal copy of another user's repository that lives on your GitHub account.
Forks allow you to freely make changes to a project without affecting the original, enabling limitless opportunities for experimentation and learning from other people’s work. 
* A forked project also remains attached to the original, allowing you to submit a pull request to the original's author to update with your changes, ensuring you’re always working off a recent or up-to-date codebase.

> GitHub Glossary #7: What is Push?
* Pushing refers to sending your committed changes to a remote repository such as GitHub.com. For instance, if you change something locally, you'd want to then push those changes so that others may access them.

> GitHub Glossary #8: What is Issue?
* Issues unsurprisingly are exactly as they sound. Issues are suggested improvements, tasks or questions related to the repository.
* Issues can be created by anyone (for public repositories), and are moderated by repository collaborators. Each issue contains its own discussion forum, can be labeled and assigned to a user.

> GitHub Glossary #9: What is Blame?
* The role of the Blame feature on GitHub passes ‘blame’ on the version of the code file that resulted in an error occurring. As it states on GitHub:
* “The "blame" feature in Git describes the last modification to each line of a file, which generally displays the revision, author and time. This is helpful, for example, in tracking down when a feature was added, or which commit led to a particular bug.” – help.github.com 

> GitHub Glossary #10: What is Merge?
* Merging takes the changes from one branch (in the same repository or from a fork), and applies them into another.
* A merge can be done automatically via a Pull Request via the GitHub.com web interface if there are no conflicting changes, or can always be done via the command line. 
* By now you should be equipped with knowledge of Git and GitHub top terminologies and features of which you should hopefully start putting into practice. Of course, there are plenty of other rich features of GitHub especially, which we implore you to discover on your own.


## Let's get started with git and github

> Cloning project
```
git clone <repo_url>
```

> Initializing git
```
git init
```

> Working locally
 
> Adding changed files
 - Check changed files
 ```
git status
 ```

 then add files that you want to commit.
 
```
git add <file_name/folder_name>
 ```

> Commiting changes
```
git commit -m "<Commit_message>"
```

> Pushing chnages (master branch)
```
git push -u origin master
```

> Creating branch
```
git branch <branch_name>
```

> Checkout into branch
```
git checkout <branch_name>
```

> Working locally on branch


> Adding changed files
 ```
git status
 ```

```
git add <file_name/folder_name>
 ```

> Commiting changes
```
git commit -m "<Commit_message>"
```

> Pusing changes (new branch)
```
git push -u origin <branch_name>
```

> Creating pull request

> Review changes

> Merging into master (from pull request)

> Pulling changes (pull from master)
```
git pull 
```

> Merging one branch into another branch 

```
git checkout <branch_name>
git pull
git merge origin/<another-branch_name>

```

> View log 
```
git log
```
or
```
git log --oneline
```

