# git remote

When working with git, a **remote** is any git repository that is NOT on your machine.The counterpart to this is **local**, or the machine you're working on.
Take Github for example, While git is the technology that allows you to create a local repository, Github is the site that will host your remote repositories. Once stored remotely you can bring that repository back down or share it with others.
**Note**: While the repositories (local and remote) are related and track the same project, they can have different states if changes are not shared between the two.

### Adding a remote

A remote can be added it the `git remote add` command, followed by the name and location of the remote.

The name is the local name, meaning it's a label and has no impack on the actual remote whatsoever.

```
git remote add origin https://github.com/ElevenfiftyAcademy/GitFundamentals.git
```
### Removing a remote
A remote can be removed with the `git remote remove` command, followed by the name of the remote.

```
git remote remove origin
```

## Resources

- [Git Remote Documentation](https://git.scm.com/docs/git-remote)

---

[Back to home](../README.md)
