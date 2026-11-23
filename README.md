# Koi Pond

A live, procedurally generated koi pond for the browser. Nothing in it is a video loop. The water, fish and visitors are all simulated in real time. It is meant to run full-screen as a screensaver.

Open `index.html` in a browser. It is one self-contained file with no dependencies.

## Features

- A height-field water simulation with refraction, caustics and specular highlights, rendered with WebGL.
- Two looks, switched with **V**: a smooth painterly view and a pixel-art view with palette quantization and dithering. Both share the same pond and events.
- Koi with scales, fins, barbels and colourways. They fade into shadows as they go deeper, and they eat the bugs that fall in.
- Regular visitors: a cat that sometimes catches a fish, a rare fishing gnome, and a capybara with a towel on its head having a spa.
- About 200 random events that interact with each other like an ecosystem:
  - Birds and bats eat insects.
  - Herons, otters, eagles, pike and others hunt koi.
  - Koi eat larvae, eggs and tadpoles.
  - Spawning can add a new koi.

## Controls

| Key | Action |
| --- | --- |
| V | Switch between smooth and pixel view |
| E | Start a random event |
| N | Start the next event in the list |
| F / X | Add or remove a koi |
| C / G / S | Summon the cat / gnome / capybara |
| B | Drop a bug |
| R | Cycle the rain modes |
| P | Generate a new pond layout |
| [ / ] | Change the pixel size (pixel view only) |
| + / - | Change the simulation speed |
| H | Show or hide the help panel |
