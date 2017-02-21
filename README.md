# Learn git

This workshop has been made for students of [Founders and Coders](www.founderandcoders.com), and therefore assumes that you have:
 + created a one-page website before (as part of the [prerequisites](www.founderandcoders.com/apply))
 + completed lesson 1 of [Udacity's Git and GitHub course](https://www.udacity.com/course/how-to-use-git-and-github--ud775) (as part of the [precourse material](https://github.com/foundersandcoders/master-reference/tree/master/coursebook/precourse))
 + created issues on each other's websites (as part of [this accessibilty workshop](https://github.com/jsms90/web-accessibility/blob/master/putting-yourself-in-someone-elses-shoes.md#exercises) on [day 1](https://github.com/foundersandcoders/master-reference/tree/master/coursebook/week-1) of the course)

 **All contributions to this workshop are very welcome!** If you have any suggestions for improvements, please raise an issue, and then follow the [contributing guidelines](./CONTRIBUTING.md) before making a pull request.

## Getting ready to work
Your workshops are designed for collaborative learning, so grab a partner and use one computer.

1. Now your pair should find another pair and all 4 of you should choose one person's one-page website from the [prerequisites](www.foundersandcoders.com/apply) to work on. Make sure the author of the website that you choose is someone who is happy for you to be committing changes.

2. Each pair should pick a different issue. Try working on the issues that were raised in yesterday's [accessibility workshop](https://github.com/jsms90/web-accessibility/blob/master/putting-yourself-in-someone-elses-shoes.md#exercises).

3. When you start working on issues, you should always **"assign" yourself**. Assigning yourself let's other collaborators know what you're doing, so they don't also decide to work on that issue. It stops you from duplicating work :+1:  
![Click on "assign" in GitHub](./images/assign.png)  
If you can't assign yourself, that's because you're not a member of the organisation that the repo is sitting in, and you haven't been added as a collaborator by the creator of the repo. So repo owners, you'll want to add your team as "collaborators" by going to Settings -> Collaborators, and entering their github handles.

4. Now post a comment in the issue, referencing the handle of the website's author. Let them know that you're going to work on this issue.  
(In an open source project, it is a good idea to wait for the go ahead from them before you begin working.)  
In this case, you are a collaborator, and can assume that the author is happy for you to do work. So assigning yourself is all the indication that you need to give.

Note: adding people as collaborators will not be necessary when you work on repos that are in the foundersandcoders or FAC10 organisation, as you are already members, and therefore automatically added with relevant access to new repos.

## Start working

Remembering to use one computer per pair, you can now start working on the issue.

Note: Since the creator of the repo has allowed you "collaborator" rights, you don't need to fork this repository first.

1. Go ahead and **clone the repo**, so you can work on it locally.

2. Remember, you will automatically be on the `master` branch. So the first thing you want to do is **create a new branch**, with an appropriate name for the work you are about to do, and then move to this branch.

3. Just before you can start `git add`, `git commit`, `git push`-ing, let's **look at the [CONTRIBUTING.md](./CONTRIBUTING.md) file in this workshop repo**.  
It is a good idea to use multi-line commits (e.g. two `-m` flags), with the second line being a reference to the issue that you are working on.

4. Ok, now you're ready to start working. Remember to keep your commits granular, and push often, so that your branch on GitHub is as up-to-date as possible.

5. When you have finished making changes, and you think the issue is finished, you'll want to submit a pull request for the other pair to take a look at.  
Write a useful message in the body of the PR, which explains the work that you have done clearly and concisely. If your PR gets merged, you don't want to have to go and manually close the issue, so reference the relevant issue by using a keyword that does this for you: `fixes #<number of issue>`.  
Make sure that you assign the other pair to the PR.

So, you're done with that issue and that branch now. While you wait for the other pair to review your PR and merge it, you'll want to start working on another issue.

**Make sure you checkout the `master` branch again!** If you just checkout a new branch, straight from this one, you will be creating a branch off the one you made for the previous issue :scream:

If there isn't another issue, use the [accessibility tools](https://github.com/jsms90/web-accessibility/blob/master/tools-that-can-help.md) to find a new issue and raise it - try something other than th dev tools, to see what else is out there.

Now that you have an issue to work on:

1. Make sure you have assigned yourself

2. Make sure you are on the `master` branch! [Do you remember the command?](https://github.com/jsms90/learn-git-basics)

3. Checkout a new branch - make sure the name is appropriately descriptive.

4. Repeat as before.

After you pair has completed a couple of PRs, you might want to review the open PRs from your other team.
