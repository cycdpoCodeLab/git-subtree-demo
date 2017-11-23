# git-subtree-demo

```shell
# add subtree and pull master branch into dist dir.
$ git subtree add --prefix=dist origin master

# modified content in dist dir. And commit it.
$ git commit -m "Initial dist subtree commit"

# push subtree to origin subtree-branch
$ git subtree push --prefix=dist origin <subtree-branch-name>
```

