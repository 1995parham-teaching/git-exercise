# Amend

```shell
git checkout amend
```
## Tasks
**Amending public commits (those which are pushed to the remote repository) can be catastrophic. Avoid it in real-life use cases.**

- There is a typo in thsi text, fix it without adding a **new commit**.
- In some point back in history, an incorrect sentence was added to `file.txt`. amend the incorrect commit to fix it. 
  - hint: you must use `git rebase --interactive` for this. 