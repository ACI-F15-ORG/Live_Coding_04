## Live Coding

### Due Date : December 17 (during finals)

### Goals:

1. Learn an IDE
2. Live Code
3. Turning In

#### 1. Learn an IDE

Pick a live coding environments to learn and use. It can be a text based (like Supercollider) or patching based (like Pure Data) IDE. You can decide to perform solo or as a group. Practice!

#### 2. Live Code

Perform a Live Coding set. 

#### 3. Turning In
First is to make your own repository of your project and sync it to github. 

Then, Clone this assignment directory to your computer. From within the folder of the clone, use the terminal. 

Make a branch, replace _your-branch-name_ with something unique, rcsid, etc.

```bash
git branch your-branch-name
```
Checkout _your-branch-name_ so that we're working in that branch.

```bash
git checkout your-branch-name
```

Replace _remote-url_ with something like _https://github.com/shawnlawson/shawnmodule.git_ and _linked-folder-name_ with your name _shawnlawson_

```bash
git submodule add remote-url linked-folder-name
```

Then you'll need to add and commit.

```bash
git commit -a -m 'adding submodule'
```

You'll need to push your branch to the remote.

```bash
git push origin your-branch-name
```
You may run up against a GIT 2.0 error. 
http://stackoverflow.com/questions/13148066/warning-push-default-is-unset-its-implicit-value-is-changing-in-git-2-0

Do the simple solution

```bash
git config --global push.default simple
```
From the github web interface for this assignment's repository you'll create a new pull request.

Base will be master, compare will be _your-branch-name_

Create the request. You shouldn't accept your own pull request. Someone else, me or another person, should review the request to make sure none of the other files in the repository were modified before accepting. Sort of like a checks and balances system. 

__Warning__ you can only push if you're a member of our organization. And, do not delete anything from the repository before pushing.

