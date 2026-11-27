## Your routine every time you work

1. **Open GitHub Desktop** and check the top-left says the right repository and the top-middle says the right branch (usually `main`).
2. **Pull first.** Click **Fetch origin** at the top. If it changes to **Pull origin**, click it. This brings in anything your teammates added.
3. **Create your own branch.** Click **Current Branch** at the top, then **New Branch**. Name it with your first name plus the date and time, like `ana-20261127-0951` (name, then YYYYMMDD, then HHMM, no spaces or colons), so no two branch names are ever the same. Click **Create Branch**. Do this at the start of every work session, right after you pull.
4. **Work as usual** in RStudio (or Word, PowerPoint, etc.). Save your files normally.
5. **Return to GitHub Desktop.** In the **Changes** tab (left side), tick the files you want to share.
6. **Commit.** Type a short summary at the bottom left (e.g. "Clean missing values in customer data") and click **Commit to your branch**. A commit is a saved snapshot, only on your Mac so far.
7. **Push.** Click **Publish branch** at the top (after your first publish it says Push origin). Now your branch is on GitHub for everyone.
8. **Merge into main.** When your piece is finished, open the **Branch** menu, choose **Create Pull Request**, and merge it on github.com. Then pull `main` before your next session.
9. **Clean up.** Only after your pull request is merged: click **Current Branch**, switch to `main`, and pull. Then open the **Branch** menu, choose **Delete**, and confirm. If it offers to delete the branch on GitHub too, say yes. Your work is safe in `main`.
