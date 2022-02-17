# git remote

when working with git, a **remote** is any git repository that is not on the machine you're working on. the counterpart to this is **local**, or the machine that is being developed on.

take github for example: while git is the technology that allows you to create local repostiories, github is the site that will host your remote repositories. once stored remotely, you can bring that repository back down or share it with others. 

**note:** while the repositories (local and remote) are related and track the same project, they can have different states if changes are not shared between the two. 

## adding a remote

a remote can be added with the `git remote add` command, followed by the name and location of the remote.

the name is a local names, meaning it's your label and does not impact the actual remote whatsoever.

```
git remote add origin
https://github.com/ElevenfiftyAcademy/gitFundamentals.git

```

### Removing a remote
 
a remote can be removed with the `git remote remove` command, followed by the name of the remote.

```
git remote remove origin
```

## Resources

- [Git remote documentation](https://git-scm.com/docs/git-remote)

---

[back to home](../README.md)