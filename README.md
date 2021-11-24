# DSLE-083021 - Phase 5 Warm Up Prompts!

Small notebooks to practice Python and SQL problems during our optional Phase 5 Warm Ups!

Please fork this notebook to work through it! Then you can either use the 'Fetch Upstream' button on your fork to collect new changes as I add new notebooks, or add this original repository as a new remote (not origin) on your local.

-----

## How to Connect to This Repository

### Option 1: Collect Changes Remotely

1. FORK this repository, creating a copy on your own GitHub account

2. Then clone your fork down to your local computer
```
git clone https://github.com/[YOURUSERNAME]/DSLE-083021-Phase-5-Warm-Ups.git
```

3. You can work on the warm up quesitons now! Remember to push your changes to your forked version of the repo (to save your local changes to your online version):
```
git add [filename]
git commit -m 'message here'
git push
```
#### Whenever you want to get updated notebooks:

1. Go to your fork, and click the Fetch Upstream button

![screenshot to show where the fetch upsteam button appears on a forked repo](images/fork-fetch-upstream.png)

2. Pull down from your remote

```
git pull origin main
```

Now you have the new notebooks on your local!

### Option 2: Using a Second Remote Connection to Collect Changes Locally

1. FORK this repository, creating a copy on your own GitHub account

2. Then clone your fork down to your local computer
```
git clone https://github.com/[YOURUSERNAME]/DSLE-083021-Phase-5-Warm-Ups.git
```

3. Add the `/flatiron-school/` version as the `upstream` (to pull future changes)
```
git remote add upstream https://github.com/flatiron-school/DSLE-083021-Phase-5-Warm-Ups.git
```

4. You can make changes to the notebooks now! Remember to push your changes to your forked version of the repo (to save your local changes to your online version):
```
git add [filename]
git commit -m 'message here'
git push
```

#### Whenever you want to get updated notebooks:

1. Grab the changes from the upstream repo
```
git fetch upstream
```

2. Merge new changes onto your local repo
```
git merge upstream/main -m "meaningful message about what you're updating"
```

Now you have the new notebooks on your local!
