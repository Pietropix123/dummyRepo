# dummyRepo


## Some changes made with second commit

### Some other text to make a third commit in the history

Suppose that in this fork now I make this commit
Then a second commit

---
At this point the PR is open, but then I receive some comments requiring this commit.


---
After the squash and force push, the history of the repo has been completely rewritten. The number of commits is now two (rather than 3).
Therefore, this method can be used to clear out large number of commits.

The comments in the PR are still there and referencing to the branch at detached state, so one can anyway trace back what happened.

---
Now I have rebased local main on basis of the origin/main one. If all worked fine, this commit in main should be `git push origin` correctly and go in the PR too
