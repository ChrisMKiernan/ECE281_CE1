# Chris Kiernan CE1 Repo

## Truth Table

A | B | C | F | B_Not | D | E
--- | --- | --- | --- | --- | --- | ---
0 | 0 | 0 | 0 | 1 | 0 | 0
0 | 0 | 1 | 0 | 1 | 0 | 0
0 | 1 | 0 | 0 | 0 | 0 | 0
0 | 1 | 1 | 1 | 0 | 0 | 1
1 | 0 | 0 | 1 | 1 | 1 | 0
1 | 0 | 1 | 1 | 1 | 1 | 0
1 | 1 | 0 | 0 | 0 | 0 | 0
1 | 1 | 1 | 1 | 0 | 0 | 1

## Testbench Waveform
![alt text](http://i.imgur.com/JDpJ9wN.png "Testbench Waveform")

## Analysis
This waveform maches perfectly with the truth table created above, where the F function only outputs "one" when the following values are true: A'BC + AB'C' + AB'C + ABC
