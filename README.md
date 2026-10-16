# Mod-Dwarf-ARC-Delay
ARC Delay for the Mod Dwarf

## Overview

A four line delay, each delay line has a filter on the feedback and an LFO that can modulate time, mix, pan and filter cutoff.

Each line can feedback to itself and also the other lines.

Can run in synced mode where it follows BPM and time mode where each line is a ratio of the whole delay.

## Global controls

### TEMPO MODE

MS: for setting the total delay time in milliseconds.
Host: For using the Host BPM
User: For using the User BPM

### USER MS

Set the length of the delay in milliseconds, maximum time is 12 seconds.

### USER BPM

Set the tempo in BPM, range 20-280

### FEEDBACK

The maximum amount of feedback, range 0-100%

### MIX

The maximum amount of delay mix, range 0-100%

### GAIN

Output gain for the plugin, range -40 dB to + 40 dB

### LFO FREQ MULT

A multiplier for the LFO speeds, range 1-100

## Delay Line controls (4 sets of these)

### INPUT

Choose the external input into this line. Left, Right, Sum or None. When None is selected the line will only take input from other lines.

### Sync

If tempo is one of the BPM modes then here you can select the delay time from:

1/1,
1/2,
1/4,
1/8,
1/16,
1/32,
1/64,
1/1 dot,
1/2 dot,
1/4 dot,
1/8 dot,
1/16 dot,
1/32 dot,
1/64 dot,
1/1 trip,
1/2 trip,
1/4 trip,
1/8 trip,
1/16 trip,
1/32 trip,
1/64 trip,

### FILTER TYPE

Choose the filter type from:

Low Pass 12db,
Low Pass 24db,
High Pass 12db,
High Pass 24db,
Band Pass 12db,
Band Pass 24db,

### TIME RATIO

If in MS mode this is the ratio of the USER MS to use for this line. So if the USER MS is 1000ms and you set the ratio to 25% then the delay line time would be 250MS.

### MIX RATIO

This is the ratio of the Global MIX to send to the outputs.

### PAN

This is the output pan position of this delay line.

### CUTOFF

This is the filer cutoff frequency.

### RESONANCE

This is the resonance of the filter.

### FB RATIO 1-1

The ratio of the output of the line feedback into delay line 1.

### FB RATIO 1-2

The ratio of the output of the line feedback into delay line 3.

### FB RATIO 1-3

The ratio of the output of the line feedback into delay line 3.

### FB RATIO 1-4

The ratio of the output of the line feedback into delay line 4.

### LFO TYPE

Choose the LFO type from:

Tri,
Sine,
Square,
Saw

### LFO FREQ

The frequency of the LFO from 0Hz - 10Hz. The LFO FREQ MULT will multiply this vale going a range of 0Hz - 1000Hz

### LFO - TIME

Modulate the time of the delay line by the LFO, bipolar -1 to 1.

### LFO - MIX

Modulate the output mix of the delay line by the LFO, bipolar -1 to 1.

### LFO - PAN

Modulate the output pan of the delay line by the LFO, bipolar -1 to 1.

### LFO - CUTOFF

Modulate the cutoff frequency of the filter for the delay by the LFO, bipolar -1 to 1.



