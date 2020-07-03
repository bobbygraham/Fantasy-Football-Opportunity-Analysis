# Fantasy-Football-Opportunity-Analysis
This program seeks to assess relative performance of NFL teams against each position group.

This program is for personal use only. It is written to run in Jupyter Notebooks.

It uses a modified version of the strength of schedule function used in college football.

https://en.wikipedia.org/wiki/Strength_of_schedule

This function takes as inputs Opponent-Record and Oppenent-Opponent-Record.  My methodology is that:

****************************************
Opponent-Record is replaced with Opponent-Points-Scored (Average)

Opponent-Opponent-Record is replaced with Opponent-Opponent-Points-Scored (Composite Average)

Strength of Schedule is replaced with Expected Points (i.e. how many points are expected for average performance)
****************************************

Thus, the equation is rewritten as:

Expected = (2*OpPointsScored + OpOpPointsScored)/3

The program requires a csv file with the NFL schedule to run. I have attached the schedule for the 2019 season.

This was written for the 2019 season. I have not tested for future NFL seasons.
