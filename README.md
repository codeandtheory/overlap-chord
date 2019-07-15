# overlap-chord
using D3.js to visualize bidirectional audience overlap (based on SG Hall's trade example)

Each of the outlets is represented by an arc with a set of chords. The chords that match the arc color represent the sites the outlet has a high overlap percentage with; the chords that go into the arc but do not match its color represent competitors who have higher overlap percentage with the outlet than the outlet has with them.

The size of each site’s arc corresponds to the number of competitors it overlaps with and for, along with the percentage of those overlaps. Some sites will have smaller arcs because many of the sites in their top ten fall outside the competitive set, while others will have larger ones because many of their top ten are within the competitive set. Put another way, the size of the arc measures how distinct the outlet’s audience is with respect to the competitive set and the diversity of colors measures the outlet’s strength within the competitive set. 
