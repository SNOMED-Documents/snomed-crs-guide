# Removing CRS request from an SCA task

A regular request is to be able to remove one (or multiple) CRS requests from an SCA task where there are multiple CRS requests. Obviously, if you want to remove them all, then please just delete the SCA task and create a new one. Until the functionality is built in to the tools, this page provides a way to achieve this objective.

The instructions below should be followed with care and exactly in the order as documented, and **always check** in the feedback/review tab on the SCA task that no 'deleted' CRS tickets have bene left in the SCA task.

  1. In the SCA task in question, if you have saved or made changes to the CRS request(s) that you want to remove, **you must delete those additions or changes** using the '-' button. For example. if it is a new concept and you have saved it, but now want to remove it, load it into the edit panel and delete that concept.
  2. Go to the relevant SCA JIRA ticket by going to the following URL (replacing the task name at the end with the name of your SCA task) - <https://prod-workflow.ihtsdotools.org/browse/TESTINT2-3>.
  3. Click on the workflow button, and select 'Return to new status'.
  4. Go to the request in CRS that you want to remove, and click the 'unassign request' button.
  5. The request will be detached from the SCA task, but will remain in an 'Under Authoring' status. This is not an issue per se, but if you really want to return it to an accepted status, please go to the relevant ticket in JIRA (i.e. <https://prod-workflow.ihtsdotools.org/browse/CRT-95155> (change id in the URL) ) and click the workflow button and choose Accepted(2), and the request will return to an accepted status.
  6. Return to SCA, and you will see that the task is in a 'new' status, but your work will still be there. Open up the task, and although you will still see the 'removed' CRS request, this can be ignored and you can continue as previously.
  7. The removed concept will still show in the "review" tab, launch each into the review panel and delete them with the '-' button. Re-run classification when you go back to the "review" tab, the removed concepts should be gone and now show up as "blanks" to be reviewed like and other deletion from the task.
  8. Again, before promotion ensure that no 'leftover' changes from the removed CRS requests are present in the task.

