# RBLX Advertising: A Brief Comparison between Campaign Objectives.
Starting off with some context and a little bit of background about me as a developer, I've recently released [my first proper project](https://www.roblox.com/games/118611429307255/cossies-guess-the-image) on Roblox about 3-ish months ago, but I've been making things on and off for about 4 or 5 years now. The project is a simple game - an image reveals itself, and players guess the image (hence the name...) and I've recently done multiple ad campaigns after iterating on the game. Now, I'm not claiming my game is perfect. It's far from it, and I'm still currently working on it.

However, I've noticed weird activity between the two current types of Ad Campaign that I've tested (Engagement & Plays - Earnings is very limited and I do not have access to it.)
Of course, I'm not expecting incredible results - but what seems to be the intent or engagement of the players between the Engagement Objective and Plays Objective is worlds apart, and I've seen [many other developers like myself come across this issue](https://devforum.roblox.com/t/sponsored-ads-botting/4824752).

## Engagement Objective - Intro & Description.
With the introduction of Roblox Kids + Select, "Highly Engaged Players" were created.
 
*(HEP for short. [This metric acts as a marker for players to get their game under review](https://en.help.roblox.com/hc/en-us/articles/203313890-How-to-Publish-Games-on-Roblox), along with the other non-simultaneous requirements e.g. ID Verification, a biometric face scan ran and hosted by the third party company [Persona](https://withpersona.com/), an active Plus membership etc.)* 

A goal of 500 (now 250) HEP is required to reach an audience of players younger than 16 ([with 73% of age-checked players being under 18](https://about.roblox.com/newsroom/2026/02/moving-beyond-self-reported-age)), so Roblox introduced the Engagement Objective, used to help reach that number. One thing to note is that what an HEP is has not yet, and probably will not be fully disclosed outside of (from what I can find) this quote within the Audience > Reach page of the Creator Dashboard. 

> "...indicators such as play history, account age, and platform expenditure to confirm that user interactions are authentic and do not originate from automated bots or fraudulent accounts."

Take this as you will!

Alternatively, you could pay a fairly eye-watering but refundable *100,000 Robux* to expedite this process. This isn't very plausible for any indie developer who doesn't already have startup capital (~1,000 USD to purchase, ~400 USD when converted via DevEx assuming non US-18+ exchange rate), so it's often that advertising is the go-to option instead.

## Engagement Objective - My Experiences
With the release of my project, I put about ~108$ across two campaigns, testing a mix of 8 thumbnails across both.
With Engagement Campaign 1, it launched as I published an update focusing around keeping players within game pre-5 minutes. A tutorial re-work, a "special" mode every third round, playtime rewards etc.
 
For this, my funnel cohort looked like this:

|Players Remaining|Step Name  | Churn
|--|--|--|
|400|Joined|0%
|219|First Guess| 45.25%
|153|Third Guess|30.14%
|98|First Pack Purchased|35.95%
|45|5 Mins Playtime|54.08%
|13|10 Mins Playtime|71.11%
|1| 20 Mins Playtime|92.31%

400 players in 5 days on a 60$ budget? Questionable, but [Roblox warns the campaign's CPP is likely to be higher due to the targeting of a subset of the audience that Plays targets](https://create.roblox.com/docs/production/promotion/ads-manager).

>"Expect a higher cost per play (CPP).  The highly engaged player audience is smaller than the Plays audience, which typically results in a higher CPP."

So clearly my game is at fault here. A 45% Churn from joining to guessing an image (maybe 10 seconds of gameplay?) is awful. 

Then Campaign 2 for Update 2. This was more of a polish update, focusing on appealing to the player more. Better notifications for streaks, more validation, another special round, focus on competition (thank you to the forum testers who gave it a shot & let me know about some of the issues!) and it resulted in a *much* better cohort.

|Players Remaining|Step Name  | Churn| Change vs C1 (pp)|
|--|--|--|--|
|329|Joined|0%|N/A
|255|First Guess| 22.49%|**-22.76**
|207|Third Guess|18.82%| **-11.32**
|136|First Pack Purchased|34.30%|-1.65
|64|5 Mins Playtime|52.94%| -1.14
|13|10 Mins Playtime|79.69%| +8.58
|2| 20 Mins Playtime|84.62%| -7.69

Substantial improvement - especially around the opening of the funnel! It also led to my first organic revenue source (4 Robux... I know, groundbreaking.)
However, with each upside, there's a down. While having an amazing funnel in comparison to prior, 329 players is not a very populated cohort, as I managed to pull an incredible 1 Home Recommendation Impression.

Across Campaign 1 and 2, I ended up with a grand total of 150 HEP - that's ~$0.72 per player, provided all HEP originate from traffic generated by the ads.

So, this is where we move from Engagement to...

## Plays Objective - Intro & Description
This has been the standard campaign type for a while, with Roblox describing it as:
> "[... reaches players who are most likely to start a session in your game.](https://create.roblox.com/docs/production/promotion/ads-manager)"

And it does deliver on the premise of getting people to start a session - but this can be confusing or misleading for people looking to get a good foothold.
From this objective, you will see a massive increase in traffic. But from this, a major difference arises about the player quality.

## Methodology of Comparison
Before hopping into the comparison, I just want to preface how I'm comparing for clarity's sake.
I'm using the cohort of Engagement Campaign **2** as a baseline, and then compared the funnel of:
Join -> First Guess -> Third Guess -> First Pack Purchase -> 5 Mins -> 10 Mins -> 20 Mins.
This funnel was used to track general player behaviour, with specifics being in-game observations (written about after comparisons.)

## Plays Objective - My Experiences
I did quite a few campaigns using the Plays Objective early into development & upon initial release, with a very similar outcome. The important campaign however, is the campaign I did directly after my second Engagement Campaign.

The most important thing to note is that I **did not update the game between campaigns.** I used a creative from the Engagement Campaign, same build version, but a smaller budget and ran over 2 days instead of 5 days. All of this started about 6-12 hours after the engagement campaign ended.

Here's the numbers:

|Players Remaining|Step Name  | Churn|
|--|--|--|
|579|Joined|0%|
|214|First Guess| 63.04%
|142|Third Guess|33.64%
|87|First Pack Purchased|38.73%
|58|5 Mins Playtime|33.33%
|14|10 Mins Playtime|75.86%
|2| 20 Mins Playtime|85.71%

A very... interesting result. An insane instant churn of ***63.04%*** before even guessing, and as mentioned before, takes about 4 seconds of walking forward.
## Direct Comparison - Engagement Campaign 2 vs Plays
And here we are - the meat and bones of this write-up. Please remember that the build hasn't changed & creatives had minimal changes compared to the Baseline .
Just to keep it short, I'll give the comparison table, with total conversion instead of churn.

|Step Name |Baseline (Engage. C2) |Plays |Change (pp) |
|--|--|--|--|
|Joined|100%|100%|N/A
|First Guess|77.51%|36.96%|**-40.55**
|Third Guess|62.92%|24.53%|**-38.39**
|First Pack Purchased|41.34%|15.03%|**-26.31**
|5 Mins|19.45%|10.02%|**-9.43**
|10 Mins|3.95%|2.42%|-1.53
|20 Mins|0.61%|0.35%|-0.26

So, here we are!
This is a *substantial* difference between the baseline and plays - around a 40pp difference on first and third guess, a 25pp change on first pack purchase.
The further down the step funnel you go, the less reliable the results, as there is a dwindling cohort size past 5 mins.
What is quite interesting, however, is that once players actually start interacting with the mechanics, they seem to have better and better metrics, aligning closer to the baseline.

## In-game Observations / Suspicious Traffic Behaviour
While this section affected both objectives, the main contributor (majority of behaviour) was witnessed within the Plays Objective, which may give some context to the difference between the objectives.

Most of what I'll call *Low-Intent Players* (LIPs) fell into one of four behaviours.
1. Standing completely still in spawn for between 30s and a few minutes, then instantly leaving.
2. Spawning, then walking around blindly into terrain / props around the map, then leaving.
3. Standing still for between 10 and 20s, then walking into the area where guessing automatically prompted, then leaving quickly after.
4. Similar to 3, but leave after a few minutes instead of quickly after.

And some LIPs exhibiting these behaviours also occasionally favourited the game - despite never interacting with the core mechanics.

[My original post](https://devforum.roblox.com/t/sponsored-ads-botting/4824752) on DevForums about this issue had quite a few other developers commenting on their experiences with similar results, highlighting  Behaviour 2 & comparable behaviour in top games.

Some things that the LIPs mentioned above had in common:
* All that I personally saw had basic / default clothing, sometimes with free accessories.
* Many display names following what looked like a formulaic pattern, an example being the standard AdjectiveNounNumber (BigElephant153, WetWater8375 etc...)
* The display name matching the username exactly.

To be clear, these behaviours do not prove anything along the lines of botting. For all we know, I was extremely, extremely unlucky to have really low intent players, or that metrics affected by prior campaigns may have tainted my record in Roblox's backend. As Mr. O. Osbourne once said, I Don't Know!

## Limitations
What should be noted is that this write-up does not prove that one objective is universally better or that traffic delivered by the Plays Objective is at all botted or anything alike, and should not be treated as anything other than evidence highlighting the behavioral differences I observed between traffic acquired by the two objectives. 

My experiences personally are that of a developer trying to make it from no prior success at all - this **will** change between people varying across success levels / ranges.

Of course, it also has to be said this isn't a perfect A/B test as campaigns were ran at separate times & under different budgets and durations (as I'm a broke uni student... cmon folks - not expecting Jandel to be writing this, are you?) but maintaining build & creatives keeps it as faithful as possible so that the comparison remains viable.

## Conclusion
Across these campaigns, the biggest pointer to take away (and hopefully help out another developer like me!) is that the raw traffic doesn't matter as much as what actually happens within your sessions.

The Engagement cohorts generated what seemed to be a stronger response to the game, mechanics etc.
The Plays cohort generated a lot more traffic, but they seemed to be much lower intent players.

I want to mention again that this does **not** prove that any of the players were bots, nor does it mean that the Plays objective is inherently a worse objective. The campaigns were not meant to be an experiment from the start, I wanted to share my findings once I discovered it. This means that the nature of the experiment is not perfect as mentioned in Limitations.

What I would be interested in seeing is why this happens - why is the traffic between Objectives so different in terms of behaviour, and whether this is expected, or if there's some sort of issue.

As the project is still a work in progress + I'm still testing with advertising, this is just a quick write-up as to what I've discovered as non-definitive results & in the future may act as a guide or some help to future developers in a similar situation to me!

Thanks for reading, and best of luck :)
