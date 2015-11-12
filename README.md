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


##Remotee


###**1. Be available**

This is a no-brainer really, but when you're working remotely, make sure you're available and your team gets timely responses from you. This means you should make sure to have a good enough internet connection to allow for skyping and screensharing and have data coverage for your phone so you can receive email and chat messages.

###**2. Be flexible**

Even when working in a different time zone, you should try and aim for some overlap with your team. Ideally between 2-4 hours. However, be prepared to work outside of your normal schedule if something important comes up.

When moving to a new place be prepared to work less the first week in order to get settled in. Generally allow for a buffer. If working 40 hours a week, give yourself 45. When working 32 hours, aim for 37.

###**2. Be realistic**

When your team members rely on you and you can't communicate as much on a day-to-day basis, it's important to be realistic about the work you can get done. Especially if others depend on your work. If you're in a different country or visiting family, you may feel obliged to be more active outside of work instead of staying in late to get work done. When in doubt, it's always a good idea to work on something that isn't crucial to the current sprint.
