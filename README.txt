This file is a refactor of pgulley’s pure data patches

rules:
maintain standard “name~” scheme for pure audio patches
patches with “name_unit” are for fader-chaining.
	They have two inputs and two outputs- the first is for audio and the second is for
	control signals. 
	When they are stacked on top of each other, they will be assigned adjacent fader 	values. 
We’ve got:
	Bob_unit
		BobMoog resonant filter
	Verb_unit
		Simple Reverb
	Chorus_unit
		simple sinusoidal chorus 
	Distort_unit
		Distortion using tank and hippos filters




“name_patch” are full, end-to-end patches. Should be able to open and go without any fiddling. 

So far- 
	Bob_patch
	Verb_patch
	Chorus_patch
	Distort_patch

Still to transfer:
	Sigmund tracker
	pitchshift_polyfon



