## Introduction

### 1.1 Background

Free Synthesizer

Synthesizer is an instrument which sound is created by electronic signals. The earliest synthesizers were analogue synthesizers, i.e. hardware synthesizers consisting of analogue circuits. With the development of digital computers, in essence today digital synthesizers are becoming more mainstream due to their cost advantage. However, for a synthesizer there are many parameters and knobs that the user must learn and understand. This has certainly raised the bar for the public to get started with synthesizers. Here I wanted to make a synthesizer that would lower the barrier to entry. This synthesizer needs to have some automated features that will help the public to understand and use the synthesizer better.

### 1.2 Brief

This report focuses on two aspects of my project – “Free synthesizer”. The first part is the basic part, where I will present the flowchart and some details of the basic part of my synthesizer. In the second part, I will present the concept and the innovative part of my project including its functionality and the music created by it.

## Part I: Basic Part

### 2.1 Composition of “Free Synthesizer”

The Flow Chart of the synthesizer is shown in Figure 2.1.

​			 	![image-20221227145924920](/Users/dpg/Library/Application Support/typora-user-images/image-20221227145924920.png)

​																						Figure 2.1
 There are three basic oscillators – a sine oscillator, a triangle oscillator and a square oscillator.

Each oscillator has a switch for users to control them if is added into the output. And they also be modulated by two LFOs (Low Frequency Oscillators). The LFOs modulate the amplitudes and frequencies of the basic oscillators. For the two LFOs, they all have a switch to control if it

works and their gains and frequencies can be adjusted by users too. This part could let users to choose and test which timber they like and sounds good. That is because there are different feelings between different type of basic oscillators and LFOs and different combination of them.

Then the output will go into a low pass filter which has two modes. Under the first function – normal mode, the cut off frequency will be set by users. It is functional, because in this mode, users could use it to cut off some high frequency noise. In terms of the second function, the cut off frequency will be modulated by Envelope. In other words, when envelope value attack, decay, sustain and release, the cut off frequency also attack, decay, sustain and release at the meantime. It is a so interesting way to modulate the Low pass filter that be used into many electronic music pieces.

When it comes to Envelope, it has four parameters – attack, decay, sustain and release which are all controlled by users. By adjusting these four parameters, users can generate timbers which sound very different. For example, with a short attack, decay, no sustain and a quick release, the timber sounds like a drum. But with a short attack, decay and a long sustain, the timber will sound like a piano.

Then the output will come into a delay effect. For the delay effect, it has two parameters – delay size and feedback controlled by users. Delay size means the percentage of samples in one second and delay feedback means the gain of the delayed samples added into the output. The delay effect also has a switch to control it open or close.

Finally, the output will go into the Reverberation effect. It is worth mentioning that the reverberation effect will work for all master track – the sum of all voices’ output instead of previous processes which work for one single voice. The Reverberation effect also has a switch and two parameters controlled by users. Two parameters are dry to wet ratio and room size. 2.2 The Role of ‘Free Synthesizer’

This basic part of ‘Free Synthesizer’ is going to let people create some simple but interesting timbers for themselves. They do not need extra learning, just adjust the parameters, control the switches, and try to feel the timber. Then they will feel electronic music is so interesting. In fact, many of my friends test my synthesizer and they all think although it looks simply, they still could have fun by generating timbers by themselves. Compared with Serum, ‘Free Synthesizer’ is easy to use and could generate unexpected and surprised timbers.

## PartII:InnovationPart

In this part, I create two intelligent modes – Chord Mode and Arpeggio Mode. For Chord Mode, the purpose of it is help people accompany automatically. The users only need open the Chord Mode switch and input a note between C3 and B4, the Synthesizer will play a seventh chord in C major scale. If the note of the chord is out of the range from C3 to B4, the note will drop an octave. It is said a transposed chord will be played.

With regard to the Arpeggio Mode, it also has a switch. After being opened, when users input a note between C4 and B5, an arpeggio of a seventh chord in C major scale will be played in a setting tempo.

