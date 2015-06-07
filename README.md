## Testing TTNT

In this branch, code-to-test mapping is produced for a commit b50784.
And small change which makes tests fail is introduced in the HEAD of this branch.

To see how TTNT selects tests, run:

```
$ bundle install
$ ttnt b50784
```

This produces 12/13th of test cases under actionmailer/test directory.
I have not yet looked into the validity of this selection, so further experiments are needed there.
Any feedback will be welcomed, please [open an issue on Genki-S/ttnt](https://github.com/Genki-S/ttnt/issues/new).
