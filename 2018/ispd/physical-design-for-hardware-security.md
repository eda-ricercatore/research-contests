#	Physical Design for Hardware Security



Some fabless IC/VLSI design companies use split manufacturing as a defense
	against untrusted foundries in the semiconductor manufacturing industry.
	This defense mechanism protects the intellectual property against the
		following attack scenarios.

Attack scenarios:
+ Reverse engineering
+ Chip recycling
+ Overproduction


##	Problem 1

Given the bottom/lower layers of the layout for an integrated circuit (for
	the front-end-of-line, FEOL, semiconductor manufacturing process), or
	VLSI system, design attacks that can determine the top layers of the layout.
	These top-layers are manufactured by back-end-of-line (BEOL) semiconductor
		manufacturing process.

We rank contestants based on the weighted combination of the following: time
	taken in order to guess the top layers for the BEOL process (30%, rank in
	ascending order), and percentage of correctly guessed connections in the
	top layers (70%, rank in descending order).


###	Problem 1a

Given the bottom/lower layers of the layout for an integrated circuit (for
	the front-end-of-line, FEOL, semiconductor manufacturing process), or
	VLSI system, extract the logic-level netlist of the FEOL layers of the
	layout and design attacks that can determine the connections of the
	logic-level netlist (i.e., implicitly determine the BEOL layers).

We rank contestants based on the weighted combination of the following: time
	taken in order to guess the connections of the logic-level netlist (30%,
	rank in ascending order), and percentage of correctly guessed connections
	in the logic-level netlist - in comparison to the logic-level netlist of
	the original IC design (70%, rank in descending order).



##	Problem 2

IC design teams use digital locking to mitigate against reverse engineering and
	overproduction of ICs.
	Develop attack methods that can unlock ICs with such digital locks.

Suggested attack methods that contestants can try include:
+ Brute-force attack
+ ATPG/SAT attack, automatic test pattern generation and
	boolean/propositional satisfiability.
+ SMT attack, using solvers for satisfiability modulo theories (SMT).
+ Smart guess attack
+ Optimization-based attack

We use a weighted linear combination of the rankings of contestants to
	determine the winning team.

Metrics for determining the ranking of contestants, and their weightage:
+ Security level (number of bits, rank in descending order), 20%
+ Evaluation time per key (in seconds, rank in ascending order), 30%
+ Operation style (tier 1 solutions are ranked ahead of lower tier solutions),
	10%:
	- Hours per day (tier 1)
	- Non-stop (tier 2)
+ Unblocking time (tier 1 solutions are ranked ahead of lower tier solutions),
	10%:
	- Can't find the correct key (tier 1)
	- Days (tier 3)
	- Weeks (tier 2)
+ Percentage of area overhead (area with overhead / original area, rank in
	ascending order), 10%.
+ Percentage of power overhead (power usage with overhead / original power
	usage, rank in ascending order), 10%.
+ Percentage of energy overhead (energy usage with overhead / original energy
		usage, rank in ascending order), 10%.




##	Problem 2








#	References

Citations/References that use the LaTeX/BibTeX notation are taken from my BibTeX database (set of BibTeX entries).

Additional references not found in the reference list shall be indicated below (TO BE UPDATED).



#	Author Information


The MIT License (MIT)

Copyright (c) <2016> Zhiyang Ong

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Email address: echo "cukj -wb- 23wU4X5M589 TROJANS cqkH wiuz2y 0f Mw Stanford" | awk '{ sub("23wU4X5M589","F.d_c_b. ") sub("Stanford","d0mA1n"); print $5, $2, $8; for (i=1; i<=1; i++) print "6\b"; print $9, $7, $6 }' | sed y/kqcbuHwM62z/gnotrzadqmC/ | tr 'q' ' ' | tr -d [:cntrl:] | tr -d 'ir' | tr y "\n"		Don't compromise my computing accounts. You have been warned.
