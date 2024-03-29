# Pattern randomizer presets for u-he Repro-1

This is a small collection of scripted presets that should make working with patterns in [Repro-1](https://u-he.com/products/repro/) a little bit more joyful.

## Installation

Download [latest release](https://github.com/drzhnn/repro-1-randomizers/releases/latest/download/repro-1-randomizers.zip).

Copy `Randomizers` folder to your Repro-1 presets location:

 - Windows: `...\VstPlugins\u-he\Repro-1.data\Presets\Repro-1\`
 - Mac: `~/Library/Audio/Presets/u-he/Repro-1/`

All presets are properly tagged and you can find them in the Preset browser, either in `Randomizers` folder or in `Randomizers` bank.

## How it works

Say, you have a preset in Repro-1 that you like and now you'd want an arpeggiated version of it. But you don't know where to start or don't feel too excited about programming patterns manually on the Repro's Sequencer page. Here's where these scripted randomizer presets come in. You load them just like any other regular preset from the Presets browser page, but they don't change your existing sound. Instead, only specific, Sequencer related parameters will be affected. Each time you load a scripted preset, it will generate a different result.

## Description

`01 Enable Arp Mode.h2p`  

This is a helper script. It simply enables Arpeggiator and Sequencer and turns any preset into a sequenced one, while keeping all other synth settings intact.

Next is a bunch of note randomizers. Each time you run these presets they will generate a different set of notes from predefined scales. Each preset has its own feel, and some of them are more random then the others:  

`02 Randomize Notes (Bassline).h2p`  
`03 Randomize Notes (Alt 1).h2p`  
`04 Randomize Notes (Alt 2).h2p`  
`05 Randomize Notes (Alt 3).h2p`  
`06 Randomize Notes (Octaves).h2p`  
`07 Randomize Notes (Pentatonic).h2p`  
`08 Randomize Notes (4+5).h2p`  
`09 Randomize Notes (News).h2p`  
`10 Randomize Notes (Tresor).h2p`  
`11 Randomize Notes (Twins 1).h2p`  
`12 Randomize Notes (Twins 2).h2p`  
`13 Randomize Notes (Waterfall).h2p`  
`14 Randomize Notes (Wild).h2p`  

Note type randomizers:  

`15 Randomize Type (Rest).h2p`  
`16 Randomize Type (Tied).h2p`  
`17 Randomize Type (Wild).h2p`  

Velocity randomizers:  

`18 Randomize Velocity (1-127).h2p`  
`19 Randomize Velocity (1-10).h2p`  
`20 Randomize Velocity (1-64).h2p`  
`21 Randomize Velocity (64-127).h2p`  

This one will shuffle the number of active steps in both patterns, while keeping the length of the resulting sequence:  

`22 Rebalance Active Steps.h2p`  

The rest are helper scripts.

Duplicate stuff (if there's enough space to duplicate to):  

`23 Duplicate Notes.h2p`  
`24 Duplicate Types.h2p`  
`25 Duplicate Velocity.h2p`  

Transpose notes by semitones or octaves:  

`26 Notes +1.h2p`  
`27 Notes -1.h2p`  
`28 Notes +12.h2p`  
`29 Notes -12.h2p`  

Increase and decrease velocity:  

`30 Velocity +10.h2p`  
`31 Velocity -10.h2p`  

Reset parameters:  

`32 Reset Notes.h2p`  
`33 Reset Types.h2p`  
`34 Reset Velocity to 1.h2p`  
`35 Reset Velocity to 64.h2p`  
`36 Reset Velocity to 127.h2p`  

All presets except 22-25 are active pattern aware and will only affect parameters in the currently active pattern. This allows you to target specific areas using Pattern switch (1, 2, 1+2) in the Sequencer panel of the Repro-1.

[Discussion on KVR](https://www.kvraudio.com/forum/viewtopic.php?f=31&t=475459)
