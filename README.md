DECRYPTOR — The Ultimate Logic Challenge (v2.1)
DECRYPTOR v2.1 is a major evolution of the high-stakes terminal puzzle. This version moves beyond the legacy input system to provide a rock-solid, tactile experience with enhanced decryption tools.

Status: Version 2.1 — Stable Release

Mission: Crack the 4-digit encrypted sequence using advanced logical deduction.

✨ New in Version 2.1 (The "Engine Overhaul")
The v2.1 update focuses on Input Stability and New Logic Tools:

🛡️ Robust Input Architecture: Removed the hidden input dependency. Version 2.1 uses a direct keydown listener and a reactive on-screen Numpad, eliminating focus-loss bugs on mobile and desktop.

📡 Scan Hint System: One free Scan_Hint per session. It intercepts the code to reveal the exact value and position of a random digit.

📂 Session Archive 2.0: A persistent log that now tracks your full guess history for every game in the session, with a new "Clear Archive" function.

↩️ Navigation Support: Added a "Go Back" feature to return to the system initialization screen without losing your session state.

⌨️ Modal Intelligence: Keyboard inputs are now automatically ignored while the [Read_Manual] overlay is active.

🎮 Core Gameplay Constraints
The system generates a secret 4-digit code following strict security protocols:

Unique Digits: Every digit in the sequence is distinct.

Zero-Guard: The first digit is never 0.

Feedback Logic:

Correct Number: Total digits found in the secret code.

Position: Total digits placed in the exact correct slot.

🛠️ Tactical Interface
Numbers for Reference (Scratchpad): Tap digits in the grid to visually eliminate them from your logic path.

Live Feed (Mini-History): A floating real-time log of your most recent injections.

Manual [Read_Manual]: Detailed documentation on decryption examples and rules.

Audio Synthesis: Native Web Audio API generating square and sine wave feedback for every system action.

Open in any modern browser (Chrome, Safari, Firefox, or Edge).

Execute Initialize_Session.

💻 Technical Specification
Frontend: Vanilla HTML5 / CSS3 (Grid & Flexbox)

Logic: Native JavaScript (Direct Event Listeners / No Frameworks)

📜 Version History
v1.0: Initial Mastermind concept.
v2.0: Cyberpunk UI, Boot Sequence, and Audio.
v2.1: (Current) Scan Hint system, Numpad rewrite, and Archive management.
