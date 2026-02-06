# ¢hange.machine // operator manual

https://santismo.github.io/Change.Machine/

<img width="1178" height="757" alt="Screenshot 2026-02-06 at 9 57 14 AM" src="https://github.com/user-attachments/assets/03b221dc-16b8-43b8-9472-6fe7ea8a4fdf" />

<img width="1172" height="756" alt="Screenshot 2026-02-06 at 9 58 10 AM" src="https://github.com/user-attachments/assets/50787234-d2d1-4080-8546-5ed485c12ca5" />

SYSTEM: Generates chord progressions and exports MIDI blocks.

CONTROLS
- Key center: Choose a root or random.
- Genre + Subgenre: Pick a main style and a specific variant.
- Tempo: BPM for playback and MIDI.
- MIDI out: WebMIDI in Chrome, defaults to Logic Pro Virtual In/Out, follows external clock when detected.
- MIDI velocity: Sets chord + bass + melody + drum velocity while MIDI Out is on.
- Bars: Length of the progression.
- Form: Toggle song form for longer progressions (auto bumps to 8+ bars); complexity controls the layout.
- Harmonic density (%): How busy the harmony feels.
- Color (%): How extended the chord voicings are (higher = more extensions).
- Theme: Use the bottom slider to shift the overall palette.
- Modulation amount (%): Likelihood of key shifts.
- Subdivision density (%): How often bars subdivide.
- Subdivision mode: Even only or even + triplet feel.
- Backing: Auto, Random, blocks, raked/strum, arps, chopped, stabs, or genre comp (auto or choose a specific genre comp style).
- Backing complexity (%): Controls how busy the comp pattern is and shapes arp density.
- Form lane: Section labels appear under the bar ruler.
- Bass controls ($ong): Genre/subgenre, density, movement, color, fills, subdivision, style, register, and channel.
- Melody controls ($ong): Genre/subgenre, density, movement, color, fills, subdivision, style, register, and channel.
- Drum controls ($ong): Genre/subgenre, fills, ghost notes, velocity, plus style (GM drums on MIDI ch 4).
- $ong mode follows form sections with dynamics and repeated motifs.
- Drum genre is independent from chord/bass/melody genre if you want.
- Bass fills (%): Scale-based fill notes (0% none, 100% every chord).
- Bass rests (%): 0% legato, 100% choppy spacing.
- Melody fills (%): Melodic fill notes within the chord scale.
- Melody rests (%): 0% legato, 100% choppy spacing.
- Track VOL: Per-panel audio level (center = current loudness, can boost louder).
- Select: Drag a box over clips, then hit ¢hords/฿ass/Melody/Drums to replace only the selection.
- Loop/Regen (per track): Loop that track or regenerate it at the end.
- Mute icons: Toggle chord/bass/melody/drums audio + MIDI.

BUTTONS
- ¢hords: Generate a new progression.
- Play: Listen with a sine synth (loops).
- Download .mid: Save the MIDI file.
- MIDI Out: Enable WebMIDI output (Chrome).
- Route: Select MIDI in/out ports (default Logic Pro Virtual In/Out).
- Random: Randomize chord settings (key/genre/density/etc); in Blend mode it randomizes the mix.
- Copy progression: Copy chord text.
- ฿ass: Generate a bass line in $ong mode.
- Melody: Generate a melody line in $ong mode.
- Drums: Generate a drum pattern in $ong mode.
- Random bass / Random melody: Randomize track controls and regenerate.
- Random drums: Randomize drum controls and regenerate.
- Undo/Redo: Step backward/forward through recent changes.
- Reset: Restore default settings.
- Click clips: Jump the playhead and audition that chord/bass/melody/drum.

HOTKEYS
- Space: Play/Stop (global).
- Left/Right: Step through chords.
- C: ¢hords (new progression).
- B: Generate bass.
- M: Generate melody.
- D: Generate drums.
- Click clips: Jump to that point and audition the chord/bass/melody/drum.
- $ong button: Toggle $ong mode (auto-bass + auto-melody + auto-drums).
