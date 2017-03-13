# GUIcontrollerforAlesisNanoSynth
State/program control and recall for Alesis Nano Quadra Synth


This is a compact program to inerface with the Alesis Nano Synth, which is a 1/3 rack unit release of the quadrasynth line of synthesizers.
The hardware interface is minimal (unusable) and so this program's primary purpose is to render all channels accessible and manageable.
Almost implemented is a preset store and recall feature.

Yet to come:  patch & effect configuration

To use:

1) cd into the directory
2) ~# pd-l2ok CONTROL.pd
3) connect puredata to midi port (I recommend patchage for this)
4) connect midi out of computer to midi in on nanosynth

necessary software packages:

pd-l2ork
python2

recommended software:

alsa
patchage
