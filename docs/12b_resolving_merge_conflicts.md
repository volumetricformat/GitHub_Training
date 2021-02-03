### Resolving a Merge Conflict

Let's try to create a merge conflict, and fix it together. You and a partner will each create separate branches, create a file with the same name, and then try to merge. The first will merge cleanly, the second will have a merge conflict. Work together to resolve the merge conflict.

1. Under your repository name, click  Pull requests.
1. In the "Pull Requests" list, click the pull request with a merge conflict that you'd like to resolve.
1. Near the bottom of your pull request, click **Resolve conflicts**.
>Tip: If the **Resolve conflicts** button is deactivated, your pull request's merge conflict is too complex to resolve on GitHub. You must resolve the merge conflict using an alternative Git client, or by using Git on the command line. 
4. Decide if you want to keep only your branch's changes, keep only the other branch's changes, or make a brand new change, which may incorporate changes from both branches. Delete the conflict markers <<<<<<<, =======, >>>>>>> and make the changes you want in the final merge.
5. If you have more than one merge conflict in your file, scroll down to the next set of conflict markers and repeat steps four and five to resolve your merge conflict.
6. Once you've resolved all the conflicts in the file, click **Mark as resolved**.
7. If you have more than one file with a conflict, select the next file you want to edit on the left side of the page under "conflicting files" and repeat steps four through seven until you've resolved all of your pull request's merge conflicts.
8. Once you've resolved all your merge conflicts, click **Commit Merge **. This merges the entire base branch into your head branch.
9. If prompted, review the branch that you are committing to.

If you choose to create a new branch, enter a name for the branch.

If the head branch of your pull request is protected you must create a new branch. You won't get the option to update the protected branch.

Click **Create branch and update my pull request** or **understand, continue updating BRANCH.** The button text corresponds to the action you are performing.

10. To merge your pull request, click **Merge pull request.** For more information about other pull request merge options, see "Merging a pull request."
