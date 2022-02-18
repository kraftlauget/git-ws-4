# Present your work with Git and Rebase

## Exercise 4 - Rebase and drop a commit

Scenario:

- Let's say the PR you created in the previous exercise was integrated into `main` branch.
- But...with a few modifications to the button styling.
- The rolling Rick feature branch you're working on has the "old" styling.
- Going forward you want the updated styling from `main` branch.

Instructions for exercise:

- Checkout branch `start`.
- Create a new branch `exercise`.
- Have a look at the commits in `solution` branch.
- Rebase `exercise` on `main` branch.
- During the rebase process, drop the commit with the old button styling.

Tips:

- [Rebase](https://git-scm.com/docs/rebase) the `exercise` branch.
- Use a GUI client such as [GitExtensions](http://gitextensions.github.io/) (Win), [Fork](https://git-fork.com/) (Mac + Win) or [GitKraken](https://www.gitkraken.com/) (Linux, Mac, Win) so that you don't have to figure out the git cli commands for doing the above.
- I've written a bit about dropping commits using GitExtensions on [my blog](https://blomholm.no/posts/how-i-git-it-basic-rebase/#drop-a-commit)

[Click here for next exercise](https://github.com/kraftlauget/git-ws-5)
