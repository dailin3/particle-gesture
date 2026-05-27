# Particle Gesture

A browser-based 3D particle interaction demo controlled by hand gestures.

## Features

- Open hand scatters particles.
- Closed fist forms a ball.
- Index finger shows `hello, world`.
- Peace gesture shows `I'm Dailin`.
- Keyboard fallback works when camera access is unavailable.
- Mouse or touch drag rotates the particle view.

## Usage

Open `particle-gesture.html` in a modern browser.

The app requests camera access for hand tracking. If the camera is unavailable or permission is denied, the keyboard controls can still switch between particle states.

## Controls

| Input | Effect |
| --- | --- |
| Open hand | Scatter particles |
| Fist | Form a ball |
| Index finger | Show `hello, world` |
| Peace gesture | Show `I'm Dailin` |
| `O` | Scatter particles |
| `C` | Form a ball |
| `1` | Show `hello, world` |
| `2` | Show `I'm Dailin` |
