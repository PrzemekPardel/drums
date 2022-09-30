# Drums for Developers (DfD)
Drums for Developers (DfD) repository includes notation explanations, samples, lessons, reference material, songs, and more for all drum-loving developers. Feel free to contribute or support this project if you like our mission.

# Percussion notation
Drum legend recommended by the Percussive Arts Society
![Drums notation](https://upload.wikimedia.org/wikipedia/commons/6/65/Sibelius_drum_legend.png) Source `Hyacinth at the English Wikipedia, CC BY-SA 3.0, via Wikimedia Commons`

# Drums for Developers tablature

## Standard drum kit

- `BD`  - Bass drum (Acoustic bass drum)
- `SD`  - Snare drum
- `T1`  - High-mid tom-tom
- `T2`  - Low-mid tom-tom
- `FT`  - Floor tom (high floor tom-tom)
- `HH`  - Hi-hat (closed hi-hat)
- `OHH` - Open hi-hat
- `PHH` - Pedal hi-hat
- `RD`  - Ride cymbal 1
- `CC`  - Crash cymbal 1

## Additional drum kit elements
- `GN`  - Ghost note
- `BD1` - Bass drum 1
- `LFT` - Low flor tom-tom
- `LTT` - Low tom-tom
- `TB`  - Tambourine
- `AS`  - Acoustic snare
- `ES`  - Electric snare
- `LWB` - Low wood block
- `SS`  - Side stick
- `HWB` - High wood block
- `COW` - Cowbell
- `HT`  - High tom-tom
- `OT`  - Open triangle

## Tempo
While tempo is described or indicated in many different ways, including with a range of words (e.g., "Slowly", "Adagio" and so on), it is typically measured in beats per minute (bpm or BPM) [Wikipedia](https://en.wikipedia.org/wiki/Tempo).
- `BPM80` - 80 bits per minute
- `BPM120` - 120 bits per minute

## Bar - Time signature
In musical notation, a bar (or measure) is a segment of time corresponding to a specific number of beats in which each beat is represented by a particular note value and the boundaries of the bar are indicated by vertical bar lines. Dividing music into bars provides regular reference points to pinpoint locations within a musical composition. It also makes written music easier to follow, since each bar of staff symbols can be read and played as a batch.

Typically, a piece consists of several bars of the same length, and in modern musical notation the number of beats in each bar is specified at the beginning of the score by the time signature. In simple time, (such as 3/4), the top figure indicates the number of beats per bar, while the bottom number indicates the note value of the beat (the beat has a quarter note value in the 3/4 example). [Wikipedia](https://en.wikipedia.org/wiki/Bar_(music)).
- `BAR3/4` - 3/4 time indicates that there are three beats per bar and each beat has the duration of a quarter note. 
- `BAR6/8` - 6/8 time indicates that there are six beats per measure and each beat has the duration of an eighth-note.
- `BAR4/4` - 4/4 time indicates that are four beats per measure and each beat has the duration of a quarter-note.

# Drums for Developers Notation
## Example 1
> Line 1 - Tempo
1. `BPM80` 
> Line 2 - Time signature
2. `BAR4/4` 
> Line 3+ Music Notation - Each line representes one bar (measure)
> Simbol `+` connecting all notes in bar
3. `HH`+`HH`+`HH`+`HH`
> Simbol `:` enabling notes for drum elements
4. `HH`:`BD`+`HH`:`SD`+`HH`:`BD`+`HH`:`BD`
> ![Line 3 and 4 - Notation](/images/2.jpg)
> Line 3 and 4 - Notation

> Simbol `|` connect multiple consecutive notes
5. `HH`:`BD`|`HH`+`HH`:`SD`+`HH`:`BD`|`HH`+`HH`:`BD`
> ![Line 5 - Notation](/images/3.jpg)
> Line 5 - Notation

### RAW File
```
BPM80
BAR4/4
HH+HH+HH+HH
HH:BD+HH:SD+HH:BD+HH:BD
HH:BD|HH+HH:SD+HH:BD|HH+HH:BD
```
