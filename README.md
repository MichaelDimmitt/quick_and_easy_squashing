## Quick and easy squashing

## Open two terminal windows:

1) `git log --name-only;`

2) `git rebase -i <SHA>~;`

## Additional notes:
1) remembering your sha can save you from a bad rebase. 💯

If you screw up badly: 
```bash
git checkout SHA;
git checkout -b you-recovered-the-branch
```

2) git status is your friend.
3) create new branches to protect your code.
