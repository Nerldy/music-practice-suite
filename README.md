Musician's Practice Suite 🎵

A mobile-friendly, web-based suite of tools designed to help musicians practice the fundamentals of music theory on the go.

🌟 Features

The suite includes three distinct tools accessible from a central dashboard:

Note Flashcards:

Learn to identify notes instantly.

Customizable timer (10s - 30s).

Supports Sharps, Flats, or Mixed accidentals.

"No Repeats" mode to cycle through all 12 keys without duplicates.

Interval Trainer:

Practice identifying or finding specific intervals (e.g., Major 3rd, Tritone) relative to a Root note.

Custom Decks: Enter specific roots (e.g., C, F, Bb) and intervals (e.g., 3, 7) to focus your practice.

Chord Flow (Progression Generator):

Generates random chord progressions (Roman Numeral / Bass Interval).

Key Lock: Practice in a specific key or let it randomize.

Extensions: Toggle between Triads, 7ths, 9ths, or Altered dominant chords.

Logic Slider: Control the chaos! Slide between "Smooth" (theory-correct functional harmony) and "Random" (pure chaos).

📂 Project Structure

/
├── index.html          # Main entry point and layout
├── css/
│   └── style.css       # Custom animations and overrides
└── js/
    ├── shared.js       # Router, Mobile Sidebar, and UI Utils
    ├── notes.js        # Logic for Note Flashcards
    ├── intervals.js    # Logic for Interval Trainer
    └── chords.js       # Logic for Chord Flow


🚀 How to Run

Option 1: GitHub Pages (Recommended for Mobile)

Upload these files to a GitHub repository.

Go to Settings > Pages.

Select the main branch and save.

Open the provided link on your phone!

Option 2: Local

Simply open index.html in any modern web browser. No server required.

🛠 Technologies

HTML5 & CSS3

Tailwind CSS (via CDN for styling)

Vanilla JavaScript (ES6+)

FontAwesome (Icons)

📝 License

Free to use for personal practice!