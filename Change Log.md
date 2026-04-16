(Most recent items on top)
-------------------------------------------------------------------------------------  
GTFreeFlyer's WWII Carrier Recovery Script for DCS World, created March 2026
-------------------------------------------------------------------------------------  
v1.1
Changes by GTFreeFlyer, Date TBD
   * Added function to automatically turn carrier group into the wind when a plane is within 10 miles, under 2,500 feet. See readme on how this works
   * Added two new globals that allow you to exclude a specific carrier unit or carrier group. See readme on how to set this up
   * Removed summary line mentioning you can also find the summary in the log (it will still show up in the log)
   * Removed "On centerline" from score summary. It will only let you know when you are off centerline
   * Added carrier name and altimeter setting to summary's conditions
   * Score summary sometimes incorrectly shows that base turn started too early - FIXED
   * Bank angle penalty was too harsh. It was based on the delta from the target value, but now is based on how far you were from the nearest tolerance limit.  Example: Target was 30 +/- 15 deg, and a recorded average of 14.9 deg would yield a 7.55 penalty (1 point deduction for each 2 deg delta from target).  Now, since it's only 0.1 deg outside of range, then penalty will be 0.1 (now 1 point deduction for each 1 deg outside tolerance). From testing, typical deductions were from bank angles in the range of 11-15 deg, so based on that range, max penalty will be 4 points instead of 9.55.
-------------------------------------------------------------------------------------  
v1.0  
Changes by GTFreeFlyer, April 9, 2026
   * Initial release
