# nyxgeek-rules
Custom rules for Hashcat

USAGE NOTES
------------------------------------
Simply point hashcat at the rules by using the --rules option. For example:

    --rules=/home/path/nyxgeek-rules/hashcat-rules/nyxgeek-i1.rule




INDEX OF RULES
-------------------------------------
**makeaddress_3digits.rule** - Makes address from words (e.g., birch -> 123birchstreet, 123birchst, etc)

**makeaddress_4digits.rule** - Makes address from words (e.g., birch -> 1234birchstreet, 1234birchst, etc)

**nyxgeek-i1.rule** - Re-creation of i1 rule from JtR - inserts chars at each positions 1-9 +/- capitalization

**nyxgeek-i2.rule** - Re-creation of i2 rule from JtR - inserts chars at two positions 1-9 +/- capitalization

**nyxgeek-o1.rule** - Re-creation of i1 rule from JtR - overwrites char at each positions 1-9 +/- capitalization

**nyxgeek-o2.rule** - Re-creation of i1 rule from JtR - overwrites chars at two positions 1-9 +/- capitalization

**nyxgeek-i1o1.rule** - Inserts a char and then overwrites a char at each position (combined) +/- capitalization

**nyxgeek-o1i1.rule** - Overwrites a char position and then inserts a char position (combined) +/- capitalization

**nyxgeek-emails.rule** - Creates email addresses from username lists, using popular email providers

**nyxgeek-weird1.rule** - Some random patterns, experimental


