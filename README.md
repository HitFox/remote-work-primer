#Remote Work Primer

This primer contains a collection of best practices to follow when one or more team members are working remotely. It's split between advice for the team and advice for the members working remotely.

##Team


###**1. Have sound ticket tracking software**

It's important that the team has a good overview of who's working on what. When working together in the office, you can quickly check with your co-workers but if some of the team is distributed, it becomes really important to have a good workflow and keeping things organized in a central place.

###**2. Use communication tools for chat and video chat**

Good communication is essential. More so when not being in the same physical space. Make sure the team uses agreed upon tools for messaging, video chat and screensharing.

###**3. Make extensive use of pull requests and code comments**

**Pull Requests**

Every feature should relate to a pull request and be small enough that it may ideally contain 1-3 commits and only touches 1-10 files. Commit messages should be clear and short. A good frame of mind is to think about how you would phrase a commit message if you wanted to contribute to a popular open source repo. You probably wouldn't write something like `WIP building js logic to add shareholder to a yet non created company` or `typo`.

In case of WIP commits, please use `git rebase -i` to clean up your own branch history before merging the pull request.

Keeping a reference to the related ticket in the PRs description will provide context for other team members to see why you're adding your code.

In addition to this, arrange to have a code review partner who is up-to-date on what you're working on so in case you can't meet a deadline, someone else can take over easily. However, keeping PRs small and focus should make it easy to have anyone take over.

**Code Comments**

This is equally important. Instead of using chat tools to talk about updates that need to happen to a PR, Github should be used. Extensively. The exchange will be visible to all team members and they will benefit from it.

Having small PRs will encourage people to take a look at them. Even if they're not working on the same feature, they will be able to comprehend what you aimed to do.
