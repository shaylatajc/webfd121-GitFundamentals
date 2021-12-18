# git pull

Similar to a [git push](.Push.md), a `git pull` will interact with a remote repository only this time it will **Pull** that changes it does not have down to the local repository.
This means any commits made that are on the remote repository will be made to the local repository.
This can be done by adding the remote name and branch name:

```
git pull origin main
```

If there is any upstream connection established, you can use `git pull` without specifying a remote or branch.

## Resources

- [Git Pull Documentation](https://git-scm.com/docs/git-pull)

[Back to home](../README.md)