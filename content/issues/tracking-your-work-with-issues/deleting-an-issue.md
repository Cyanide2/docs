---
title: Deleting an issue
intro: People with admin permissions in a repository can permanently delete an issue from a repository.
redirect_from:
  - /github/managing-your-work-on-github/managing-your-work-with-issues-and-pull-requests/deleting-an-issue
  - /articles/deleting-an-issue
  - /github/managing-your-work-on-github/deleting-an-issue
  - /issues/tracking-your-work-with-issues/creating-issues/deleting-an-issue
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - Pull requests
---
The ability to delete issues depends on whether the repository is owned by your personal account or an organization:
- You can only delete issues in a repository owned by your personal account.
- You cannot delete issues in a repository owned by an organization or another personal account, even if you are a collaborator there.

To delete an issue in a repository owned by an organization, an organization owner must enable deleting an issue for the organization's repositories, and you must have admin or owner permissions in the repository. For more information, see "[Allowing people to delete issues in your organization](/articles/allowing-people-to-delete-issues-in-your-organization)" and "[Repository roles for an organization](/organizations/managing-access-to-your-organizations-repositories/repository-roles-for-an-organization)."

Collaborators do not receive a notification when you delete an issue. When visiting the URL of a deleted issue, collaborators will see a message stating that the issue is deleted. People with admin or owner permissions in the repository will additionally see the username of the person who deleted the issue and when it was deleted.

1. Navigate to the issue you want to delete.
2. On the right side bar, under "Notifications", click **Delete issue**.
!["Delete issue" text highlighted on bottom of the issue page's right side bar](/assets/images/help/issues/delete-issue.png)
4. To confirm deletion, click **Delete this issue**.

## Further reading

- "[Linking a pull request to an issue](/github/managing-your-work-on-github/linking-a-pull-request-to-an-issue)"
