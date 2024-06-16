# Madden Trainer for Madden 24

Madden Trainer is a tool that simulates players having football practice and going through physical workouts during the week to stay in shape.  The tool updates player's attributes - depending on how well they practice and do their workouts (if they participate). This gives your franchise a more realistic, dynamic feel - as players will change every week in a more dynamic way than the default game does!

## How To Use

1. After running the tool, Load your franchise by selecting your franchise file (usually in the '\Users\\<username>\Documents\Madden NFL 24\saves' folder). NOTE: You **MUST** always use this franchise file whenever loading your franchise into the tool every week - i.e. be sure and use the same franchise file when using the tool, or your progressions will not get saved.  Don't rely on autosave files, unless you used that autosave file at the beginning to initialize the franchise in the tool.
   
2. Initialize your franchise (one-time step).  This generates data locally for your franchise to keep track of player potentials and progression.
   
3. Once every week (preseason and regular season), run the "Simulate Training" function. Only run this function once per week. **IMPORTANT! DO NOT EVER RUN THIS WHILE MADDEN 24 IS RUNNING WITH THAT FRANCHISE LOADED - OR UPGRADES WILL NOT BE SAVED!**
   NOTE: You may choose to run this at the END of every week so that overall ratings shown in the ppa will match in-game, since the game doesn't re-calculate overall until you advance to the next week.
   
4. After this is ran, you can view the results of the weekly training on the 'Training Results' section of the app.  You can view the training results for each 'iteration'.  A new iteration is created every time weekly training is ran.
   
5. Once training is ran at least twice, you can start viewing the 'Overall Progress' part of the app, which allows you to view the progress of your players, from an overall rating perspective.  NOTE: While the individual ratings for each player will get updated real-time, the overall ratings will not get re-calculated by the game until you advance to the next week - so that report will always be 1 week behind, and will not be meaningful until training is ran a second time.
   
6. Progress is tracked on a yearly basis.  Once a new year starts in your franchise, the previous year data will not be shown in the app (for now).

## How does the tool work?

The tool essentially assigns 2 new attributes to each player - a "Work Ethic" rating (A-F), and a "Potential" rating (A-F).

The app simulates players having football practice and going through physical workouts during the week to stay in shape.  The tool updates player's attributes - depending on how well they practice and do their workouts (if they participate). Sometimes players will not participate in workouts or practice due to injury.  Players with a good work ethic will have good workouts and practices, which would make them reach their potential.  If players have a poor work ethic, they are more likely to have poor workouts and/or poor practices, and can even suffer attribute losses.  Players whom are injured can miss workouts and/or practices, which also can degrade attributes. 

Practices are important for players to maintain and improve their football skills.  Players can improve their football skills all the way to their potential until they are 31 years old.  Players who practice bad can decline their football skills at any age.  Players with a good work ethic are more likely to practice hard and successfully.

Physical workouts are important for players to improve and maintain their physical abilities, such as speed, strength, and agility.  Physical attributes are harder to improve, and players can only improve their physical attributes until they reach 26.  Just like practices, players with a good work ethic are more likely to succeed at improving their body through workouts.

## How does the existing XP system affect this new way of progressing?

It doesn't - XP is not used in this progression system. To avoid conflicting with the progressions from the tool, the tool will wipe out any XP for all players when training for the week is executed.

## How far can a player progress?

Every player is assigned a potential rating, which is heavily determined by their development trait; but, just because a player is normal development, doesn't mean they cant boom - and just because a player has X-Factor development, doesn't mean they cant peter out, especially if they have a poor work ethic.  Based on this potential rating, a player is assigned potentials to their attributes - their age is also a factor in this.  When a player has their development trait upgraded, the app will show this - and get a boost to their potential.

## How often do I run the tool?

Once, at the start of each preseason and regular season week. Progression is done WEEKLY.

## What does the tool tell me?

The tool currently has 3 screens/reports:

1. Weekly training results.  This shows each player, and the results of their physical workouts and practice during the week, along with any changes to any attributes as a result of training.  Physical training results can show one of (DNP, Lethargic, OK, or Good).  Practice Results can be one of (DNP, Bad, OK, Good, Excellent, or ELITE).  

2. Overall progress.  This shows how a player's overall rating has changed over time.  Note that the overalls shown on this report will be 1 week behind, since the game needs to re-calculate the overall when you move to the following week.

3. Player training history. When you click a player's name in the weekly training results, you can see how successfully the player has trained in prior weeks. This can help you determine if a player is able to progress, and if he is motivated to progress.

## My player had an excellent practice, but none of his attributes changed. Why not?

This could be a couple of reasons. If he is over 31 years old, he cannot make any more gains. If he is not over 31 years old, he may have already met his potential in the attributes that he was rewarded for that practice.

## How do injuries affect progression?

Players with significant injuries will be more likely to miss workouts and practices, thus causing them to degrade a little bit until they can start working out and practicing again.  The longer they will be out due to injury, the more likely they will miss workouts and/or practice.

## How do the development traits factor in?

The higher a player's development trait, the more likely they will have higher potential - but it isn't guaranteed.  When a player's development trait is upgraded, the app will show that with a special icon, and that player will be rewarded with bonus potential.

## What about XP gained in-game?

XP is not used, and is cleared from every player automatically when you run training for the week in the tool - this is so that the progression in-game doesn't interfere with the progression from the tool.
