# git push

when you have a [remote](./remote.md) set up you'll need to begin to move [commits](./commit.md) to the remote. this can be done with the command `git push`.

you cna attach a name and branch name to your command to specify where you're pushing to. 

```
git push origin main
```
> This command will push the **main** branch to the remote called **origin.** This means any commits that are in your local will be **pushed** to the remote

## Upstream tracking

instad of including the name of the remote and the branch you're on every time, you can set local branches to track an upstream branch. This mean syou can tell the branch to push to its assigned upstram remote branch by using the command `git push`

```
git push -u origin main
```

afte this command is used, you can just use `git push` and it will function the same way

## Resources

- [git push documentation](https://git-scm.com/docs/git-push)


---

[back to home](../README.md)
