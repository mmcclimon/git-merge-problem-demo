# Test repo

This is a repository meant to test a potentially buggy behavior in git.

To reproduce the behavior, run:

```
$ git merge branch1 branch2 branch3
Fast-forwarding to: branch1
Trying simple merge with branch2
Simple merge did not work, trying automatic merge.
Trying simple merge with branch3
error: Entry 'dir2/file.txt' not uptodate. Cannot merge.
Merge with strategy octopus failed.
```

