# Soundtracker

Soundtracker is a Windows 11 desktop utility that estimates the horizontal direction of a game sound source from system output audio. It uses WASAPI loopback capture through the selected output device and does not inject into games, attach to game processes, or read/write game memory.

## Features

* Parameter console plus a compact transparent always-on-top overlay.
* Button and global hotkey toggle between console and overlay modes.
* Adjustable detection sensitivity.
* Adjustable pointer smoothing.
* Selectable output device.
* No game process interaction of any kind.

## Notes

Direction is estimated from stereo left/right energy balance in the system output stream. This works best with games using stereo or virtual-surround headphone output. If a game mixes directional audio mostly into mono, any system-level tool will have less information to infer a horizontal direction.

Hotkeys use `pynput` syntax, for example `<ctrl>+<alt>+h`, `<shift>+<f8>`, or `<cmd>+<alt>+h`.



This project is already \_packaged in .exe format\_, so it should be able to run without any environment deployment in \*\*windows 11 \& windows 10\*\* system.



It is born from vibe coding, so it's great to reflect bugs and provide me some opinion about new features, and I will use my spare time to fix bugs \& add new features.
