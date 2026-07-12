# Sounds

| File          | Plays when                                              |
| ------------- | ------------------------------------------------------- |
| `ta3fita.mp3` | An innocent (مواطن) is voted out                        |
| `chrab.mp3`   | Mr White guesses the civilians' word **wrong**          |
| `tnekt.mp3`   | Mr White guesses the civilians' word **right** and wins |

The filenames are mapped in the `Sfx` module in `index.html` (`const SRC`).
To swap a sound, either replace the file or point `SRC` at a different name.

If a file is missing or won't play, that event falls back to the synthesized
sound the game already has — so it stays playable either way.

`wiw.mp3` is currently unused.
