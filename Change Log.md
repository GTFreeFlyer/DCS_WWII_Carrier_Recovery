(Most recent items on top)  
-------------------------------------------------------------------------------------  
GTFreeFlyer's WWII Carrier Recovery Script for DCS World, created March 2026  
-------------------------------------------------------------------------------------  
v2.0
Changes by GTFreeFlyer, TBD
  * LSO feature (new):
  * Added LSO Lt. Leroy Flamingo. He will appear automatically as you come around from base to final. Make sure you study LSO signals. He will give guidance on left/right and up/down alignment, as well as remind you if your gear, flaps or hook are not down, and will give you a mandatory cut or waveoff signal at the end.  
     
  * Carrier auto-wind alignment feature:  
  * Carrier will ignore your existence if wings are folded on the deck. This means that when you spawn in with no one else around, the carrier will not turn into the wind until you spread your wings. Also, after returning from a sortie, the carrier will head back to fleet position after everyone is on deck with their wings folded.
  * Small crosswind over deck was blowing to port instead of starboard. Fixed.
    
  * Grading feature:  
  * Relaxed penalites on one of the segments slightly.
  * Added 10 point penalty if you ignore the mandatory waveoff signal from the LSO and land anyway. You are not graded for anything else related to the LSO. He's there to help you, not hurt you.
  * Previoulsy, when holding altitude or speed, small fluctuations are natural and you would be penalized any time these values would change in the direction opposite of the final target. This update adds a small filter for tiny movements to reduce the total penalty accumulation.
  * Converting back and forth from magnetic headings to true headings was adding instead of subtracting the declination, resulting in a small mismatch of values used for scoring. Fixed.

  * All documentation updated at <https://github.com/GTFreeFlyer/DCS_WWII_Carrier_Recovery>

-------------------------------------------------------------------------------------  
v1.2  
Changes by GTFreeFlyer, April 18, 2026
  * Added functionality to return the carrier groups back to their original fleet position.
  * Added new global setting, NotificationSound, in case you have a different .ogg other than notification.ogg that you'd prefer to use. See readme.  
  * BRC now contains leading zeroes for headings < 100
-------------------------------------------------------------------------------------  
v1.1  
Changes by GTFreeFlyer, April 16, 2026  
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
