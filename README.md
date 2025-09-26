Step 1: 
    We first make changes to a particular file, in this case, it was helloworld.c. We then need to use the "git add" comamnd to add
    all the changes to the commit. Then we commit the change to our local branch. It is important to note that it is the local branch, and not the cloud branch. We will do that in step 2.
Step 2:
    Now that we have pushed changes to the local branch, we can use the push command to push our entire branch to the origin (the cloud branch). That is all we need to do for this step.
Step 3:
    We then go to github.com, and we accept the pull request we just made for ourselves. We compare the request to see the proposed changes, and then we accept without adding any comments or changes.

Step 4:
    We now need to go back to our main branch, and pull the changes that we just did in github.com. We use git pull to pull from the cloud branch, and grab the changes to our local branch.
Step 5:
    We then want to merge our side barcnh hellowrold, into main. We switch to helloworld branch with checkout command, and then merge the branch back.
Step 6:
    The final thing that we need to do is push the merge that we just did. So we are in the branch we want to ush already. All we need to do is push the commit from helloworld to our cloud branch using git push. And we are done! Just pull the log up to see the changes.
