📚 Kindergarten CVC Builder: Adaptive Phonics Game

A simple, single-file HTML/CSS/JavaScript game designed to help early learners (Pre-K to Kindergarten) master CVC (Consonant-Vowel-Consonant) words through fun, interactive play.

✨ Features

30 CVC Words: A comprehensive set of short vowel words (A, E, I, O, U) paired with engaging emojis.

Adaptive Difficulty: The game starts in EASY MODE (6 letter options) and automatically transitions to HARD MODE (8 letter options) after a streak of 5 correct words, ensuring continuous challenge.

Real-Time Feedback: Correct and incorrect audio cues and visual flashes provide instant learning reinforcement.

Single-File Build: The entire application (HTML structure, Tailwind CSS styling, and all JavaScript logic, including Tone.js for audio) is contained within a single index.html file, making it easy to deploy, share, or embed.

Fully Responsive: Designed using Tailwind CSS for a seamless experience on mobile, tablet, and desktop devices.

🚀 How to Run Locally

Since this is a single, self-contained HTML file, no server or complex setup is required.

Download: Save the index.html file to your computer.

Open: Double-click the file. It will automatically open in your default web browser (Chrome, Firefox, Edge, etc.).

Play! The game will start immediately.

⚙️ Technology Stack

Technology

Purpose

HTML5

Core structure and content.

Tailwind CSS

Utility-first framework for responsive and modern styling.

Vanilla JavaScript

Game logic, state management, and DOM manipulation.

Tone.js

Lightweight library used for generating synthesized correct/incorrect sound effects.

🕹️ Game Logic Highlights

The core adaptive mechanism is managed by the JavaScript logic:

State: The correctStreak variable tracks consecutive correct words.

Threshold: The DIFFICULTY_THRESHOLD is set to 5.

Progression: When correctStreak is less than 5, the game provides the 3 correct letters plus 3 distractors (6 total buttons).

Hard Mode: When correctStreak is 5 or more, the game provides the 3 correct letters plus 5 distractors (8 total buttons), increasing cognitive load and engagement.

Reset: Any incorrect answer resets the correctStreak to 0, returning the student to Easy Mode to rebuild confidence.
