# git merge

- git merge <branch name>
- fix conflict
- git add .
- git commit -m ""
- git push

- Preserves history by keeping all individual commits and branch relationships intact.
- Can lead to a complex and messy commit graph, making the history difficult to read and follow.
- Easy traceability allows developers to quickly pinpoint the origin of changes using the merge commit.
- Introduces redundant merge commits that only exist to connect history, adding no functional code value.

# git rebase

- Current change là của nhánh main
- Incoming change là của nhánh con

- git rebase main
- fix conflict
- git add .
- git rebase --continue
- :wq
