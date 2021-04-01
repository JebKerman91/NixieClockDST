# NixieClockDST
A modification of GreatScott's Nixietube sketch with different libraries and automatic DST detection.
 
Based on this project by GreatScott! https://www.instructables.com/Make-Your-Own-Retro-Nixie-Clock-With-an-RTC/
Changed RTC type to a DS3231 since it's FAR more precise - the DS1307 originally used accumulated an error of approx. 1 second/day.

Libraries used:
DS3232RTC by Jack Christensen - https://github.com/JChristensen/DS3232RTC
Timezone by Jack Christensen - https://github.com/JChristensen/Timezone
