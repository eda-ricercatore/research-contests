#	Hardware Security Problem for "CAD Contest at ICCAD"

Some fabless IC/VLSI design companies use split manufacturing as a defense
	against untrusted foundries in the semiconductor manufacturing industry.
	This defense mechanism protects the intellectual property against the
		following attack scenarios.

Attack scenarios:
+ Reverse engineering
+ Chip recycling
+ Overproduction
+ IC piracy
+ counterfeiting
+ hardware trojans


##	Suggested topics

+ Logic encryption
+ Logic masking


##	Logic Locking Problem

IC design teams use logic locking to mitigate against reverse engineering and
	overproduction of ICs. In addition, lock-and-key mechanisms can protect
	against scan-based side-channel attacks carried out during manufacturing
	test and in-field test.
	Develop attack methods that can unlock ICs with such digital locks.

Threat Model: locked netlist.

Attack method: propagate sensitive individual key bits to primary outputs.

Sensitization attacks: SAT attack, SMT attack, signal probability skew attack.


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




#	References

Citations/References that use the LaTeX/BibTeX notation are taken from my BibTeX database (set of BibTeX entries).

Additional references not found in the reference list shall be indicated below (TO BE UPDATED).



#	Author Information


The MIT License (MIT)

Copyright (c) <2018> Zhiyang Ong

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Email address: echo "cukj -wb- 23wU4X5M589 TROJANS cqkH wiuz2y 0f Mw Stanford" | awk '{ sub("23wU4X5M589","F.d_c_b. ") sub("Stanford","d0mA1n"); print $5, $2, $8; for (i=1; i<=1; i++) print "6\b"; print $9, $7, $6 }' | sed y/kqcbuHwM62z/gnotrzadqmC/ | tr 'q' ' ' | tr -d [:cntrl:] | tr -d 'ir' | tr y "\n"		Don't compromise my computing accounts. You have been warned.
