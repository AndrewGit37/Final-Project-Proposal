# PFDA-Final
This is my final for PFDA which is Audio visualizer

# Title

Python Audio Visualizer

# Demo

Demo Video: https://youtu.be/6SsUfIcZjvk

## Repository

<Link to your project's public GitHub repository>

https://github.com/AndrewGit37/Final-Project-Proposal.git

## Description

This program explores digital art through real-time audiovisuals generated from live audio input. Inspired by YouTube audio visualizers from film, TV, anime, and game soundtracks, it highlights the rhythm and flow of music. It also reveals how a computer receives, processes, and transforms audio into a visual experience.

## Features

- **Feature 1**  
	- Capture audio and analyze its frequency and volume. Start with audio files, then add live input from a microphone.
  
- **Feature 2**  
	- Generate visuals based on the audio. For example, louder sounds can trigger brighter colors or larger shapes. Visuals like waveforms or particles can move with the music. 
  
- **Feature 3**  
	- Let users customize the visuals using keyboard or mouse input. This includes changing colors, patterns, and sensitivity. Also add a recording and playback feature to save and replay audio with visuals.

## Challenges

- I will first need to NumPy to process and analyze audio data.
- Learn and use PyAudio to capture audio.
- Learn Pygame to create visuals and adjust them based on audio input.

## Outcomes

- **Ideal Outcome:**  
	The program runs using live audio input and turns it into visuals in real time. Different sounds create different colors, shapes, and animations—for example, loud audio shows stronger or brighter effects, while softer audio shows calmer ones. Inspired by film, TV, anime, and game soundtracks visualizers on YouTube, the program will also let users customize the visuals using keyboard and mouse controls.

- **Minimal Viable Outcome:**  
	The program captures audio and displays basic visuals based on frequency. Customization will be limited, but the core goal is to show audio reacting visually in real time hopefully the user can find it interesting and exciting.
## Milestones

- **Week 1**
  1. Learn PyAudio and how to capture audio in Python
  2. Display basic waveforms or frequency data

- **Week 2**
  1. Add simple visuals that react to audio
  2. Test how visuals respond to different sounds
- **Week 3 (Final)**
  1. Add customization options and improve visuals
  2. Final testing and submission


- **Description of functions and effects used for visualizers**
  1. Implemented audio capture from WAV file
  2. Implemented animation of bars 
  3. Separated frequencies from bars into Bass, midrange, and treble
  4. Keyboard press 1 changes color of visualizer to white
  5. Keyboard press 2 changes color of visualizer to Orange
  6. Keyboard press 3 changes color of visualizer to Pink
  7. Keyboard press 4 changes color of visualizer to Purple
  8. Keyboard press 5 changes color of visualizer to Red
  9. Keyboard press 6 changes shape of visualizer to Default bars
 10. Keyboard press 7 changes shape of visualizer to circles 
 11. Keyboard press 8 changes shape of visualizer tov diamonds
 12. Keyboard press 9 turns on trail effect that gives the visualizer a bit of an after image effect on it
 13. Keyboard press 0 turns off trail effect
 14. Keyboard press P pauses and unpauses music and visualizer
 15. Visualizer has a particle effect on it and shows the amount of particles based on the frequencies of the song. For example if the song is slow the particles will barely
     show up. However in the second song the particles are abundant and are very prominent in the demo.
