# gitflow_sandbox
## Yout ~/.gitconfig
To start using gitflow effectivly, the following should be in your ~/.gitconfig

```

[branch "master"]
    remote = origin
    merge = refs/heads/master
[branch "develop"]
    remote = origin
    merge = refs/heads/develop
[gitflow "branch"]
    master = develop
    develop = master
[gitflow "prefix"]
    feature = feature/
    release = release/
    hotfix = hotfix/
    support = support/
    versiontag =

[push]
    default = simple
```
