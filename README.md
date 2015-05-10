# Good Game Auto Blocker

Please see http://blog.randi.io/good-game-auto-blocker/ for a complete version of the README as pertains to the previous version of ggautoblocker.

### history

A major problem with social media is the lack of flexible filtering controls. Twitter has a block mechanism, but a user has to initiate contact in order to be blocked. For most forms of harassment, this is an effective way of moderating conversations. Unfortunately, as more social campaigns use Twitter as their basis for communications, this approach becomes less effective. While it’s suitable for use against a single harasser, it’s useless against a large number of accounts targeting a single user. These tweets needed to be stopped before they land in the user’s notifications.

### how it works

Good Game Auto Blocker compares the follower lists for a given set of Twitter accounts. If anyone is found to be following more than one of these accounts, they are added to a list and blocked.

Most discussions of ggautoblocker are referencing the GamerGate-specific block list. The GamerGate block list filters the majority of Twitter interactions by GamerGate supporters. This list is maintained and shared by the author, Randi Harper, as well as a number of volunteers. OAPI does not maintain that block list. 

The previous version of ggautoblocker can be found at [freebsdgirl/ggautoblocker](http://github.com/freebsdgirl/ggautoblocker/), but a complete rewrite is underway.
