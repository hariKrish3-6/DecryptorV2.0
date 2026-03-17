DECRYPTOR — The Ultimate Logic Challenge (v2.0)
DECRYPTOR is a high-stakes, logic-based puzzle game inspired by classic "Bulls and Cows" and Mastermind mechanics, wrapped in a sleek, retro-cyberpunk terminal interface.
Your mission: Interface with the encrypted system and crack a 4-digit security code using pure deduction.
The system generates a secret 4-digit code with the following constraints:
Unique Digits: No number appears more than once.
No Leading Zero: The first digit will never be 0.
Limited Intel: You must interpret system feedback to narrow down the possibilities.
Feedback System
After every "Injection" (guess), the terminal returns two critical data points:
Correct Number: How many digits in your guess exist anywhere within the secret code.
Position: How many of those digits are in the exact correct slot.
Example:
Secret Code: 5 2 3 4
Your Guess: 4 2 7 8
System Feedback: Correct Number: 2 (4 and 2), Position: 1 (only 2 is correctly placed).
Features in v2.0
Terminal Interface: Immersive CRT scanline effects and a "Share Tech Mono" aesthetic.
Boot Sequence: Animated system initialization sequence upon startup.
Scratchpad: An interactive "Numbers for Reference" grid to help you manually eliminate digits.
Audio Feedback: Synthetic blips, thrums, and "access granted" melodies using the Web Audio API.
Attempt Log: A persistent history of your guesses to track your deductive path.
Mobile Optimized: Responsive design with a hidden input trigger for virtual keyboards.
Technical Stack
Language: Vanilla JavaScript (ES6+)
Styling: CSS3 Custom Properties (Variables) & Keyframe Animations
