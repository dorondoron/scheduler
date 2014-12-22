Scheduler
=========

The sample file availability.csv is included and many people can be added.
The weekdays as columns always come first followed by the positions, the
penultimate column is the ammount of days someone can work and the last row
is a work in progress. This might change later but it's how it is for now.

The output file is named weekly_schedule.csv and will automatically overwrite
any existing values so be sure to save a file you like.

Running the program more than once will result in different schedules even when
the same values are given. This is due to the randomization of row order.
This was included for two reasons, the first was to avoid favoritism on a 
week to week basis and the second was the fact that the program will encounter
some data errors from time to time, so rerunning the program will produce
new results which might not contain errors.

The values one and zero are used as true and false values, please be sure
to keep the standard. It's pretty easy to follow based on the example.
This may change in the future.
