### Prakash Parasuram Java1 GitHub Exercise 8/24/2019
Create a repo on GitHub that contains a markdown file that answers these questions:
* How do you see the files changed within each commit from git log?
     *- within each commit we see in sequence of new to old, Date and time of commit, Author and email, and commit hash indicating where the HEAD is.
* How do you see the contents of what changed within each file from the git log?
     *- *git diff \<old\> \<new\> will show difference between old and new with anything added to new with \+ and anything removed with \-, \<old\> and \<new\> are replaced with the hash of the commit or keyword HEAD which refers to the latest (most recent) commit
* What does HEAD refer to in the context of git? (Not to be confused with the "HEAD<<<<" one observes within merge conflict)
     *- *HEAD is a reference to the last commit in the currently check-out branch. You can think of the HEAD as the "current branch". When you switch branches with git checkout, the HEAD revision changes to point to the tip of the new branch. You can see what HEAD points to by doing: cat .git/HEAD.

