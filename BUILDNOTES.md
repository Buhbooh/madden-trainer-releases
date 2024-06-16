# Madden Trainer for Madden 24 Build Notes

## Build 0.1.0 (RELEASE CANDIDATE)
Additions:
1. Player overall changes are now shown realtime!  Note that the game will not show the overall rating update until after the week is advanced.
2. Player Overall and Archetype are now shown on player detail modal. (You wont see Archetype until you run training at least once after this update.)
3. Add confirmation when executing reverting of ratings.

Bug Fixes:
1. Fixed issue with teams not getting initialized correctly in certain circumstances.
2. Fixed issue with incorrect team nicknames being imported.
3. QBs should not have generic 'ThrowAccuracy' attribute available to be improved, as it is not used.

Changes:
1. Team dropdowns now show city name AND nickname. (You will need to run the 'Update Teams' function for this to work properly).
2. Modified the font used in the app.
3. On the training report, injured players are now shown in RED (instead of a dedicated icon column), to save room.
   
## Build 0.0.6 (RELEASE CANDIDATE)
Bug Fixes:
1. Fixed issue of not being able to view training report on older franchises.
   
## Build 0.0.5 (RELEASE CANDIDATE)

Additions:
1. A confirmation dialog is now shown if training is ran when an iteration has already been created for the current week.

Changes:
1. Players with an 'Excellent' or 'Elite' practice result now have a chance to get a boost to potential ratings.  This isn't guaranteed, and the potential gains are processed before the actual gains. These gains are shown in a gold background on the report, and the potential ratings are not shown (just what was gained and how much).
2. On the training report, gains of more than 1 point are now shown in blue.


## Build 0.0.4 (RELEASE CANDIDATE)

Additions:
1. Added an administrative function that allows you to revert all attribute gains for the current YEAR. Note that this only works for the current year - once you advance to the next year in your franchise, you cannot revert the rating from previous years.

Changes:
1. Various cosemtic changes
2. Modified the way injuries impact ratings changes.  Injury impacts are now dependent on age, and rating hits are no longer guaranteed on sever injuries. This should lessen the impact of season-long injuries.

## Build 0.0.3 (RELEASE CANDIDATE)

Additions:
1. You can now click on a player in the trainer report and see their training history from prior weeks!

Bug Fixes:
1. Minor issues with scaling and sizing on training report.

## Build 0.0.2 (BETA)

Additions:
1. Added simple sorting support to important columns on Training Report.
2. Make sorted column sticky when selecting different team/iteration on both reports.
3. App Window is now resizable.

Changes:
1. Default app size is now closer to 16:9 ratio.
2. Rookies now show 'R' for Years Pro, instead of 0.

Bug Fixes:
1. Fixed issue where sorting was broken on some columns on Overall Report.

