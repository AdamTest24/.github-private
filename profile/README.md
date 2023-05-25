## LearnToDiscover

### Creating a new cohort

1. Make sure you are logged in to the **L2D-admin** account
2. [Create a new organization](https://github.com/account/organizations/new?plan=free) for the cohort
3. Fill out the [Issue Form](https://github.com/LearnToDiscover/create-new-cohort/issues/new/choose) in the `LearnToDiscover/create-new-cohort`  repository with all the relevant information for the new cohort
4. Submit the issue, this should launch a [GitHub Actions workflow](https://github.com/LearnToDiscover/create-new-cohort/actions) with the name that you used as the title in the Issue Form. Check whether the workflow has launched and wait until it ha completed (should only take a couple of seconds)
5. Go to the organization you created in **step 2**, if everything went well, all the requested repositories should be there and [member invitations](https://docs.github.com/en/organizations/managing-membership-in-your-organization/canceling-or-editing-an-invitation-to-join-your-organization) should have been sent out
6. [Enable organization-level Discussions](https://docs.github.com/en/organizations/managing-organization-settings/enabling-or-disabling-github-discussions-for-an-organization) for the new cohort organization and choose the **Discussions** repo to host these
7. Go to the forked lesson (sandpaper) repositories, and, so that the lessons are deployed automatically: go to the `Actions` tab of the repository and click on the green button

8. Set up the [GitHub Classroom](https://classroom.github.com/classrooms/new) using the organization you created in **step 2**
