# pd-playground
Hosts small audio synthesis projects implemented in [puredata](https://puredata.info)

## Steinberg Neon
An exercise in substractive synthesis, it's an implementation in the pd language of the classical VST Neon, by Steinberg.

###Usage
1. *myNeonKey~.pd* contains an interactive panel mimicking the Steinberg Neon's original panel. To play some notes, press your computer's keyboard keys (refer to the schematic on the patch's bottom left for the key-note mapping). Rebember to turn up the volume on the output~ box!
2. *myNeonMIDI~.pd* is the same as *myNeonKey~.pd*, but the notes are determined by the MIDI input port.