## How to contribute to the wiki

This is easy - you only need to be a github user.

## contributing data to the repo

First of all, you need to set up git; github help has a pretty good [guide on how to do it](http://help.github.com/set-up-git-redirect). Then, get in touch so that we can give you access to the repo.

### initial setup: getting the data at your machine

You need to clone the repo on your local machine, by typing:

```git
    git clone
```

After a few minutes (depending on your internet connection), you have all the contents of the repo stored locally on the newly-created `ebola-crowdsource` folder. Note that this is _only_ for first-time setup; you don't need to do this every time you want to add/get data.

### adding data locally

whenever you want to add data, first of all you need to get the most recent version of the remote copy:

```git
    git pull
```

Now, add anything you'd like to add on your local copy by just copying files/creating folders, and issue

```git
    git add <whatever-new-file/folder>
```

you're ready to commit the changes:

```git
    git commit -m 'a message explaining briefly the changes introduced'
```

### pushing your changes to the remote side

you just need to type

```git
    git push origin master
```

We're trying to keep this as simple as possible (no branches, forks, whatever). However, if you're new to this kind of stuff all of this can be rather daunting. The other option is:

## ask for help!

If you have your data at some publicly available URL, and you are unable/confident to follow the steps above, we'll be happy to upload the data for you: just send an email.
