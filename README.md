# Uplift Arpeggio

Arpeggiator/sequencer/utility for Ableton Live.

![Screenshot](screenshot.png)

## Demo

Please see the included a [demo set](uplift-arpeggio-demo-project.zip) to see how to use the device! 

## What?

This device was designed to automate some of the melody-writing process I use in my own music (mostly uplifting trance). The idea is quite simple: 

* write a nice 3-notes chord progression 
* add the device and use the top grid to create a 1 bar long, 16th notes monophonic sequence from the given notes (the first, second and third rows represent the first, second and third notes of the chord respectively, ordered by increasing pitch). This is basically an arpeggiator, with a little bit more flexibility perhaps. 
* Tweak velocities and select which notes are (or are not) playing using the velocity editor and the little note on/off grid. 

And that's pretty much it really... The remaining controls are just the icing on the cake and allow you to:

* generate random note sequence, velocities or note on/off configuration (most randomisation functionality can be tweaked/constrained e.g. you can select the range of velocities, or the probability of a "note on")
* manipulate the note sequence in different ways e.g. shifting the pattern left/right or cycling vertically (please experiment with that, it's easier to play with than it is to explain!) 
* adjust the global note length 
* transpose the while thing up/down by semitones

## Troubleshooting

### There's no sound!! 

To function properly, ideally you need to play a 3 notes chord. If you play e.g. only 2 notes but in the notes grid you try to use the 3rd notes, that will not play - check that first! 

Moreover, the device needs the transport on (i.e. hit "play").

## Found a bug or want to suggest a feature?

Please feel free to [open an issue](https://github.com/dfilaretti/uplift-arpeggio/issues/new) and I'll look into it.  
