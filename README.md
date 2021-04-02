# LOGOLIB.LGO

Library of common routines for Atari LOGO -

SAVE.CLEAN :FILENAME - Saves content of workspace EXCEPT for LOGOLIB routines for a clean save of your program.

SETITEM :INDEX :LIST :VALUE - Sets the value of a list at index position in list, if index > COUNT :list, puts item at end.

ITEM :INDEX :LIST - outputs the index item of list

DIFF :A :B - outputs difference of a and b (aka subtraction for those who don't like infix notation)

MAP :TEMPLATE :LIST - Map procedure of FMS Logo for Atari Logo - applies template to every item in list

REDUCE :TEMPLATE :LIST - Reduce procedure of FMS Logo for Atari Logo - reduce list to single element using template

FILTER :TEMPLATE :LIST - Filter procedure of FMS Logo for Atari Logo - Use template to filter the contents of a list

;  - Allows comments in Atari LOGO

All other procedures (FILTER.ONE, QUOTED, LISTED) are helper procedures for above library procedures.
