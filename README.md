
# Piano Tone Generator

## Overview

The **Piano Tone Generator** is a MATLAB-based project that allows users to create a sequence of piano tones by entering piano keys and their respective durations. The project features a graphical user interface (GUI) for easy interaction, making it accessible for users with varying levels of experience in programming.

## Features

- **User Input**: Accepts piano keys and note durations as input.
- **GUI Interface**: Provides a user-friendly interface for entering the piano keys and durations.
- **Frequency Calculation**: Computes the frequency of each piano key based on standard pitch (A4 = 440 Hz).
- **Waveform Generation**: Generates a sinusoidal waveform for each note corresponding to the entered piano keys.
- **Visualization**: Plots the generated waveform, allowing users to visualize the piano tones.
- **Playback**: Plays the generated piano tones as an audio signal.

## How to Use

1. **Input Piano Keys**:
   - Enter the piano keys (MIDI numbers) in the provided input field. The keys should be separated by spaces.
   
2. **Input Durations**:
   - Enter the durations for each corresponding piano key in seconds. These should also be separated by spaces.

3. **Generate and Play**:
   - Click the "Please Generate" button to generate the waveform and play the corresponding piano tones.

4. **View Output**:
   - The generated waveform will be displayed, showing the amplitude of the signal over time.

## Example

For example, to generate a sequence where:
- The piano key 60 (Middle C) is played for 0.5 seconds,
- Followed by the piano key 62 (D) for 0.5 seconds,
- And then the piano key 64 (E) for 1 second,

You would enter:
- **Piano Keys**: `60 62 64`
- **Durations**: `0.5 0.5 1`

## Notes

- The piano key numbers correspond to MIDI note numbers. For example, Middle C is 60.
- Ensure that the number of piano keys matches the number of durations to avoid errors.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
