Musician's Practice Suite 🎵

A comprehensive, mobile-friendly web application designed to help musicians practice music theory fundamentals, ear training visualization, and instrument proficiency. Built as a single-file application using HTML5, Tailwind CSS, and VexFlow.

🌟 Application Tools

The suite features five specialized tools accessible from a central dashboard:

1. 🎼 Note Flashcards

Build speed in recognizing chromatic notes.

Display Modes: Toggle between Sharps (♯), Flats (♭), or Mixed accidentals.

Timer: Auto-advance functionality with countdown beeps (10s - 30s).

Smart Cycling: "No Repeats" mode ensures you practice all 12 keys before seeing a duplicate.

2. 📏 Interval Trainer

Practice constructing or identifying intervals on your instrument.

Dual Modes:

Standard: Displays a Root Note + Interval (e.g., C + Major 3rd).

Pure Mode: Displays only the abstract interval (e.g., ♭5) without a root context.

Interactive Pickers: Select specific Roots via a Circle of Fifths wheel and specific Intervals via a grid.

Directional Practice: Practice intervals Ascending (→), Descending (←), Both, or Random.

Visual Feedback: Color-coded arrows (Green for Up, Red for Down).

3. 🎹 Staff & MIDI Trainer

Sight-reading practice with real-time instrument feedback.

Grand Staff: Renders target notes on Treble and Bass clefs using VexFlow.

MIDI Support: Connect a MIDI keyboard to see played notes highlight in real-time (Yellow) against target notes (White).

Note Values: Toggle display between Whole, Half, Quarter, and Eighth notes.

Custom Scope: Filter exercises by Root keys and Interval distances.

4. 🔄 Inversion Trainer

Master chord voicings and inversion shapes.

Flashcards: Generates a chord symbol (e.g., Cm7) and a required inversion (e.g., 2nd Inv).

Intelligent Filters: * Keys: Select specific keys via Circle of Fifths.

Extensions: Practice Triads, 7ths, 9ths, or a Mix.

Inversion Types: Toggle specific inversions (Root, 1st, 2nd, 3rd).

5. 🌊 Chord Flow

Generate harmonic progressions for comping and voice-leading practice.

Harmonic Logic: A slider that moves between Smooth (functional harmony rules) and Chaotic (random chords).

Key Lock: Constrain progressions to a specific key center (e.g., "Eb Major") or let it randomize.

Bass Lines: Options for Root bass, Inverted bass, or Poly/Slash chords.

Context: Toggle between Diatonic (strictly in-key) and Chromatic (borrowed chords) modes.

🛠 Features & Tech

Zero-Install: Runs entirely in the browser from a single HTML file.

Audio Cues: Subtle beep sounds for the final 3 seconds of any timer.

Responsive Design: Optimized for both desktop and mobile screens.

Tech Stack:

Vanilla JavaScript (ES6+)

Tailwind CSS (Styling)

VexFlow (Music Notation)

Web MIDI API (Controller Support)

🚀 Usage

Download the index.html file.

Open it in Chrome, Safari, or Edge.

For MIDI features, ensure your browser supports the Web MIDI API and allow permissions when prompted.