# Contribution guidelines
These should look familiar - it's the same as the [CONTRIBUTING.md in the `master-reference`](https://github.com/foundersandcoders/master-reference/blob/master/CONTRIBUTING.md).

## Before starting work

 1. Search this repo's [issues](https://github.com/jsms90/learn-git/issues) to see if an issue exists for the problem you are solving.
 2. If the issue does not exist, create it.
 3. Use "@jsms90" within the body of the issue, to let me know that you would like to take it on.
 4. Once you are sure of what you need to do and that it is needed, assign yourself to the issue.
 5. Clone, and create a new branch for your work.

## Multiline commit messages

You will want to space your commit messages over more than one line. You can do this in one of two ways:

1.

Commit with two separate `-m` flags:  
```md
git add -m "[my commit message]" -m "related #[issue number]"
```

2.

Commit without any `-m` flags, to bring up a text editor in which to write the commit message.

You may want to configure git to use your preferred text editor, if you do not like the default. ie. [Set atom to be default commit message editor](https://help.github.com/articles/associating-text-editors-with-git/#using-atom-as-your-editor).

The message should have the format

replace square braces
```md
short description under 50 chars.
[newline]
more detailed description (may be bullet points)
[newline]
related #[issue number]
```
or
```md
short description under 50 chars.
[newline]
related #[issue number]
```

It is important that you reference an issue in each commit.

## Pull Requests

Once you have finished your work, push up your branch and make a pull request. Make sure it has the following

  1. A good title
  2. Description, with detail of everything in the pull.
  3. Reference to the issue in description.
  4. An assignee, assign someone from the list at the top.

# Thank you!

P.S. please star this repo.
