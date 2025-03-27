# DJ Polyrhythm BPM Calculator

A web-based tool for DJs to calculate compatible BPMs across different time signatures for polyrhythmic beatmatching.

## About This Tool

This tool helps DJs create polyrhythmic mixes by calculating compatible BPMs between tracks with different time signatures. When two tracks have compatible BPMs, their measures will have the same duration, allowing for smooth beatmatching despite having different rhythmic structures.

For example, a track in 3/4 time at 90 BPM would perfectly match with a 4/4 track at 120 BPM. This creates a 3:4 polyrhythm where the downbeats will align every 3 measures of 4/4 or 4 measures of 3/4.

## Features

- Calculate compatible BPMs across 8 common time signatures (4/4, 3/4, 6/8, 5/4, 7/8, 2/4, 9/8, 12/8)
- Visual beat pattern representation showing how rhythms align
- Mobile-friendly interface for use in DJ booths
- Works offline once loaded (no internet connection needed)
- Shows exactly when rhythm patterns will realign

## How to Use

1. Enter your source BPM
2. Select your source time signature
3. Click "Calculate"
4. The results will show compatible BPMs for all common time signatures
5. The beat pattern visualization shows exactly how the rhythms will align

## Access the Tool

Visit https://waelgara97.github.io/dj-polyrhythm-tool to use the tool directly in your browser.

## Mathematical Background

The formula used for conversion is:
BPM₂ = BPM₁ × (beats_per_measure₂ / beats_per_measure₁)

For example, to convert from 90 BPM in 3/4 to 4/4:
BPM₄₄ = 90 × (4/3) = 120 BPM

## Common Polyrhythms for DJs

- 3:4 (3/4 with 4/4): Creates a waltz feel against a standard beat
- 3:2 (6/8 with 4/4): Common in Afro-Cuban and Latin music
- 5:4 (5/4 with 4/4): Creates complex, asymmetrical patterns
- 7:8 (7/8 with 4/4): Used in Balkan and Middle Eastern styles