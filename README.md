# so2calc
###	Fun project: "stack of 2s" dc operator sequence calculator, in native dc

Exhaustively determines the shortest and "simplest" sequence of given dc operators that yields the desired integer when performed on a theoretically bottomless stack of 2s.

In concrete dc terms, so2calc finds the shortest and "simplest" string "<ops>" such that "<sufficient amount of 2s> <ops> p" prints the desired integer.

This corresponds to finding the "simplest" expression with no numbers other than 2 in inline/normal notation, for example -10=2-(2+2+2)*2 (based on result from so2calc)

May take an extremely long time for awkward/hard-to-reach numbers because each character of output corresponds to 13x more effort.
	
#### dc is a reverse-polish calculator and one of the oldest Unix utilities. It has powerful features including arbitrary precision and bases, the ability to store code in registers and conditional execution thereof. Yes, that means it's Turing-complete. That's why I decided to try coding in it, and it's definitely something special compared to most modern languages.
	
### so2calc — Version with whitespace and comments. Try to understand how it works if you know dc's commands!
### so2calc-min — Minimized/"compiled"? version without unnecessary whitespace, comments and text prompts. Only 357 bytes!
