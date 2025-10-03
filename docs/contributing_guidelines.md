# Contributing

## Branching

All commands must be run inside your project terminal. For all your tasks, you will need to create a branch for your team and submit a pull request once you are done.

### Creating New Branch

**Option 1: Creating a branch on GitHub**

1. Click the branch button on the github page of our repo. It should be right underneath the repo name and say "master"
2. Type in the name of the branch you want to create.
3. Click **Create Branch: [branch name]**
4. Open up your project
5. Run `git pull` in the terminal to update your branches
6. Run `git checkout [branch name]` or `git switch [branch name]` to switch to the newly created branch
7. Double check that you are in the correct repository by running `git branch -a`
8. Make your changes and push as normal while working within your branch

**Option 2: Creating a branch locally**

1. `git branch [name]` to create a branch with name of [name].
2. `git checkout [name]` to switch to branch [name].
3. When you've finished making your changes locally, run `git push -u origin [name]` to create the remote branch and push to there.

### Developing in your branch

All of the code related to your issue should be contained to your branch only. Do not make changes to other people's branches.

A single branch should not last longer than 2 weeks and should have very self-contained, easy to identify changes.

### Making proper commits

A proper commit should focus on one small piece of functionality and describe what has changed.\
Only commit code that is working. Do not commit broken code.\
Commits should start with an imperative verb and describe the overall change.\
Example: "Fix calendar component not appearing on home page"\
For a resource on good commit messages, see here: [Guidelines for commit messages](https://gist.github.com/luismts/495d982e8c5b1a0ced4a57cf3d93cf60)\
When you are ready to commit, make sure you're on your designated branch by the following code:
`git status`\
And then commit your changes:

1. `git add *`
2. `git commit -m "commit message"`
3. `git push`

### Keeping your branch up to date

Occasionally, you may want to merge the contents of `stage` into your branch to keep it up to date. Follow these steps while remaining on your branch:

1. `git fetch origin` to fetch the latest remote changes from origin for all branches
2. `git merge origin` to merge the remote stage branch into your own local branch

Or, you can run `git pull origin` to do both at once.

## Pull Requests

Pull requests (PRs) represent a set of commits on a specific branch that are proposed to be merged into the `stage` branch.

PRs have the following lifecycle:

1. The PR is opened by the developer, who wants to merge their work from their branch into `stage`. The developer should request a review or let one of the project leads know.
2. The PR gets reviewed by a code reviewer such as a Tech Lead.
3. If changes need to be made, the developer continues to work on that branch and re-requests another review when they are ready.
4. If the changes are accepted, the branch commits will be merged into stage and the branch is now inactive.

### Making a Pull Request

1. Navigate to the [repository page](https://github.com/cssgunc/cancerlinc-web).
2. Click the **main** branch button and navigate to the branch you worked on.
3. Click the **Contribute** button
4. Click **Open Pull Request**
5. Click write a description of your changes
6. Click **Create pull request**

## Conclusion

By the end of this, you should be ready to begin writing code and contributing to the project via your branches!

Next: Refer to the [Resources](resource.md) page for a comprehensive list of helpful links.
