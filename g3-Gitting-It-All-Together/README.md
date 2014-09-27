# Todo

* [ ] value
* [ ] commands
* [ ] screencaps
* [ ] gifs


# Feature-Branch Workflow


Suppose you finally got working code and don't want to mess it up.
Instead of changing that, make a copy of it and work on the copy.

Make a copy of the main branch (master), name it after your new feature.
In our example we are giving our website "telekinesis".


gif of `git branch` `git branch telekinesis` `git checkout telekinesis`

### check your current branches (should come up with a unique name)

gif of above

```sh
git branch
```

the * shows you are in the master branch.

### make a new branch named after your feature


gif of creating new branch and git branch
```sh
git branch <feature-name>
```
type `git branch` again and note you have another branch :smile:

but the * is still next to `master`, how to move to our new branch?

```sh
git branch
```

### switch to new branch ("check it out")

So now "check out" what's going on in that branch, which is the way to switch to a new branch.

gif of changing branches via git checkout, and git branch

```sh
git checkout <feature-name>
```

### now mess around and add a new file 

```sh
echo "ur superpower" > superpower.txt
```

```sh
git add superpower.txt
git commit -m "gained a new superpower, yay!"
```
note this feature is not yet in the main copy (a.k.a. the master "branch").

### Let's pretend we made lots of awesome code and that it works, and now we want to bring that back to the main copy.

bringing the feature to the main copy (aka master branch):

return to the master branch
```sh
git checkout master
```
check you are in master branch:

```sh
git branch
```

merge the feature into the master branch (see gif for example):

gif of merging the superpower

```sh
git merge <new-feature>
```

now the new feature is in your master branch :smiley:

### Now that you've added the feature, scrap the old branch


```sh
git branch -d <that-feature>
```

now type:

```sh
git branch
```

your previous branch has been deleted.

### feel free to sync the main copy with your server.

```sh
git push origin master
```

## Conclusion

Now you can 
