# reflections

## lesson 1 and 2

### reflection (6)

How did viewing a diff between two versions of a file help you see the bug that was introduced?

> knowing what was good and using that as a templete to find the difference helps speed up finding mistakes... mainly good for typos and small changes

### reflection (8)

How could having easy access to the entire history of a file make you a more efficient programmer in the long term?

> allows you to see the different approaches taken and easily go back when something doens't work or easily try something new, because you can easily go back

### reflection (15)

What do you think are the pros and cons of manually choosing when to create a commit, like you do in Git, vs having versions automatically saved, like Google Docs does?

> with manual commit you can add meaning to the chunks you commit, but it means you're in control and have to use it wisely

### reflection (18)

Why do you think some version control systems, like Git, allow saving multiple files in one commit, while others, like Google Docs, treat each file separately?

> for document writing mostly the dependencies are on one, but with code the functions or logic can be split over multiple and still part of the same feature or bug fix

### reflection (22)

How can you use the commands git log and git diff to view the history of files?

> git log will show you all the changes with there id and commit messages
> these than can be used with git diff to find the deference between hopefully meaningfull commits

### reflection (26)

How might using version control make you more confident to make changes that could break something?

> with the checkout function it is much easier to go back to a previous version than starting in older file or files... its much harder with multiple files involved

### reflection (31)

Now that you have your workspace set up, what do you want to try using Git for?

> try using it for documention version control and some programming or some try with building using ansiblegit init

## lesson 3

### reflection (4)

What happens when you initialize a repository? Why do you need to do it?

> will start a new repository

> but still need to add files to it with : git file ...

> maybe if a create a new file like this it will not be needed

> nop, also needs to be added first with : git file ...

### reflection (7)

How is the staging area different from the working directory and the repository? What value do you think it offers?

> it allows you to bundle multiple files with a commit, useful for logical grouping

> working directory is everything else what you don't want to commit (yet) so also allows you to selectively select what you want to have committed

### reflection (12)

How can you use the staging area to make sure you have one commit per logical change?

> by adding all the changes (files) needed for that fix or logical commit ... in the staging area and from there do a commit

### reflection (15)

What are some situations when branches would be helpful in keeping your history organized? How would branches help?

> branches can help with keeping a main working version and something for experimenting... like new features or different languages... etc

### reflection (20)

How do the diagrams help you visualize the branch structure?

> it makes it a lot easier to see who belongs to whom and who can be reached by whom...
> and if its reconnected with master or still separated
