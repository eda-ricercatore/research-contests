#	Physical Design for Hardware Security



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

A set of layout benchmarks (based on GDSII/OASIS format) for the FEOL layers
	would be provided.

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

A set of layout benchmarks (based on GDSII/OASIS format) for the FEOL layers
	would be provided.

##	Problem 2

Develop a physical design tool that performs IC camouflaging to defend against
	untrusted end-users who may perform reverse engineering to obtain the
	semiconductor IP (of the IC design).

A reverse engineering flow will be used to guess the original design.
	Contestants are ranked based on the proportion of the IC being reverse
		engineered;
		we would use an equivalence checking tool to do this.
	The order of ranking is descending.


A set of layout benchmarks (based on GDSII/OASIS format) for the FEOL layers
	would be provided.



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
