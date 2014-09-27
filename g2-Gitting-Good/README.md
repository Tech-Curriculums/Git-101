2nd Dan of Git.

* [  ] value write up 
* [  ] command list
* [  ] pics of each step
* [  ] gifs of each step


## Value and what you will be able to do.

Sometimes you want to initialize your own project -- instead of using github as a starting point.

### If you don't have a project, feel free to make a folder and cd into it (otherwise just cd into it)

screen-cap of mkdir stage -> gif
```sh
mkdir <name-of-project>
cd <name-of-project>
```

### start git in that folder

screen cap of git init -> gif

```sh
git init
```


### The first thing I usually do is to create a readme file (assumes vim)

sceencap -> gif of creating saving a readme

```sh
vim README.md
```


### Add files one by one (or `git add *` to just add everything)

```sh
git add *
```

### commit them into the history

```sh
git commit -m "initial commit"
```

## Congrats you're done with the cycle (you only have to do `git init` once)

# Syncing with a server

### If you want to further sync your work with a server, get the url (should end with a `.git`)

screencap -> gif of grabbing the url from github, pasting it into the following command

```sh
git remote add origin <url-here>
```

### from now on `origin` is the nickname of that url, and you can now push with:


```sh
git push origin master
```

You can see that `origin` is just a shorthand name for the the url.  You learned 2nd level of git.
To gain the belt you will need to understand what "master" means -- which is in our 3rd level, where you will
learn how to use git professionally (quick right?).


#End level 2
