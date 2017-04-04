# alpha/chaos

collection all kinds chaos code here

for review by others

## kill historic file

- push error file
- usage filter-branch


```
༄  git filter-branch --tree-filter "rm -f chaos/debuguself-ascii-mapping.png" HEAD
Rewrite 85d721d84fef36737090e0fec9cfe6840eef17d4 (1/8) (0 seconds passed, remaining 0 prediRewrite 101f431738f5f54bfbacecdc3b942238363e7d93 (2/8) (0 seconds passed, remaining 0 prediRewrite c63b05a65fdb3ccda7d93959cfcc231cbe20cd93 (3/8) (0 seconds passed, remaining 0 prediRewrite 3b7dbfe987cc4eecbf52dd1cd98b7028b2e4e80f (4/8) (0 seconds passed, remaining 0 prediRewrite be809f150d857574a1560f3dd702eb336279db09 (5/8) (0 seconds passed, remaining 0 prediRewrite 8135bea164c08cfa09e78bd9b70f9fd0801bcaf1 (6/8) (0 seconds passed, remaining 0 prediRewrite 50b6054f5d07f1d9fd3626db7ef4564042c7e8b4 (7/8) (0 seconds passed, remaining 0 prediRewrite 3833c44fd9d0478ba2512d07f44ebcdc3bce6be3 (8/8) (0 seconds passed, remaining 0 predicted)
Ref 'refs/heads/master' was rewritten

༄  git pu --force
Counting objects: 5, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 576 bytes | 0 bytes/s, done.
Total 5 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local objects.
To github.com:zoom-quiet/alpha.git
 + 3833c44...5e93c96 master -> master (forced update)

 ༄  git ll -12
* 5e93c96 - (HEAD -> master, origin/master, origin/HEAD) log(img) action step 1
|       Zoom.Quiet 27 minutes ago
* fa58149 - debug(img) push error file
|       Zoom.Quiet 28 minutes ago
* 8135bea - init. dir for chaos showing
|       Zoom.Quiet 11 months ago
* be809f1 - init. dir for crawler
|       Zoom.Quiet 11 months ago
* 3b7dbfe - appended cralwer sub dir
|       Zoom.Quiet 11 months ago
* c63b05a - appended cralwer sub dir
|       Zoom.Quiet 11 months ago
* 101f431 - init. dir for bigdata learnning
|       Zoom.Quiet 11 months ago
* 85d721d - Initial commit
        Zoom.Quiet 11 months ago

```

