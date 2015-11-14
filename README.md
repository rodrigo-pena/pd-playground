# pd-playground
Hosts small audio synthesis projects implemented in [puredata](https://puredata.info)

## Steinberg Neon
An exercise in substractive synthesis, it's an implementation in the pd language of the classical VST Neon, by Steinberg.

###Usage
1. *myNeonKey~.pd* contains an interactive panel mimicking the Steinberg Neon's original panel. To play some notes, press your computer's keyboard keys (refer to the schematic on the patch's bottom left for the key-note mapping). Rebember to turn up the volume on the output~ box!
2. *myNeonMIDI~.pd* is the same as *myNeonKey~.pd*, but the notes are determined by the MIDI input port.

## Resynthesis
An exercise in additive synthesis. The patches allow us to read an audio snippet, perform a Fourier analysis of it, and resynthesize it from its Fourier components and respective envelopes. 

###Usage
1. *myResynth~.pd* is the main patch in this folder. Press "load sound file" to choose an audio snippet to load (*Hint:* try the ones in audio/!). You can hear the loaded snippet by pressing the bang next to "Play original sound file". To perform Fourier analysis on the signal, press the bang next to "Analyse!". Finally, press the bang next to "Resynthesize!" to (surprise, surprise...) resynthesize the loaded audio.

## Physical modelling
An exercise in the physical modelling of a string. 

###Usage
1. *main~.pd* is the main patch in this folder. The colored slides allow several properties of the string to be changed, such as length, linear density, the attack positio, etc. To the right side of the patch, a 3-way orange selector allows you to choose between a plucked, a bowed, or a struck string. You can also change the boundary conditions of the vibration (brigde and nut termination buttons). Press "Hit the string!" to hear what you've just created!.