
# jt2

My personal fork of [st](https://st.suckless.org/) (suckless terminal).

`st` source is at [https://git.suckless.org/st/](https://git.suckless.org/st/)


```
$ git branch -vv

* main     db397ce [origin/main] Merge branch 'suckless'
  suckless e5e9598 [suckless/master] fix buffer overflow when handling long composed input
```

```
$ cat .git/config

[core]
  repositoryformatversion = 0
  filemode = true
  bare = false
  logallrefupdates = true
[remote "suckless"]
  url = git://git.suckless.org/st
  fetch = +refs/heads/*:refs/remotes/suckless/*
[branch "suckless"]
  remote = suckless
  merge = refs/heads/master
[remote "origin"]
  url = git@github.com:jmettraux/jt2.git
  fetch = +refs/heads/*:refs/remotes/origin/*
[branch "main"]
  remote = origin
  merge = refs/heads/main
```


## License

MIT/X Consortium License

See [LICENSE](LICENSE).

