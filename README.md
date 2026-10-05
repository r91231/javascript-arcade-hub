# javascript-arcade-hub
A modern web application featuring user authentication, interactive client-side logic, and multiple browser-based logic challenges built with vanilla JavaScript, HTML5, and CSS3.

🕹️ Arcade Web Platform

A modern, comprehensive, and dynamic web-based arcade platform built with Vanilla JavaScript, HTML5, and CSS3. The project delivers an engaging user experience, featuring local user authentication and management via localStorage, a modular main menu, personal and global highscore tracking systems, and an assortment of challenging browser-based minigames.

🚀 Key Features

Secure Local Authentication & User Management:

Complete registration system featuring smart field validation (unique username, email format verification, password length check, and password confirmation matching).

Flexible login functionality supporting authentication via either username or email.

"Remember Me" preference handling utilizing localStorage versus sessionStorage for advanced session control.

Highscores System:

Automated tracking and updating of Personal Bests for each individual user (backed by unique keys in localStorage).

Global highscore tracking per game, designed to foster friendly competition across all platform users.

Global Navigation System:

A responsive, accessible dropdown navigation bar embedded across all game pages to enable seamless transitions and smooth user flows.

Advanced UI/UX Design:

Modern Dark Mode design aesthetic inspired by high-end design systems (featuring deep color palettes, smooth transitions, and subtle gradients).

Fully responsive layout with complete Right-to-Left (RTL) Hebrew language support.

📂 Project Structure

The project is structured as a multi-page client-side application interconnected via Vanilla JavaScript logic:

g.html (Registration Page):

Handles the creation of new user accounts, validates input integrity, and checks for duplicate usernames or emails within the local database.

g_enter.html (Login Page):

The primary entry point for existing users, verifying credentials against stored data and managing session preferences.

g_menu.html (Main Dashboard):

The central arcade hub. Displays a personalized welcome message for the active user, interactive game cards, highscore previews, and navigation options.

g_game.html (Game 1: "Find the Number"):

A fast-paced reflex and focus game on a dynamic number grid. Features a countdown timer, bonus time mechanics for correct answers, and automated highscore verification.

g_simon.html (Game 2: "Simon Says"):

A classic memory and sequence game powered by the browser's Web Audio API. Tests the player's concentration and pattern recognition across progressively complex rounds.

g_reveal.html (Game 3: "Image Reveal"):

A multi-tier trivia challenge (Easy, Medium, Hard). Correctly answering general knowledge questions progressively uncovers hidden image tiles behind a grid overlay.

g_dice.html (Game 4: "Dice Challenge"):

A placeholder architectural layout for upcoming platform expansions.

🛠️ Tech Stack

HTML5: Semantic document structure and DOM layout.

CSS3: Custom styling featuring Flexbox, CSS Grid, custom properties, and smooth animations.

Vanilla JavaScript (ES6+): Complex game logic, DOM manipulation, robust event handling, and data persistence via localStorage and sessionStorage.

Web Audio API: Programmatic synthesis of dynamic audio tones for interactive feedback.

🚀 Getting Started

Since this project is entirely client-side, no backend server or external database installation is required!

Ensure all project files (g.html, g_enter.html, g_menu.html, g_game.html, g_simon.html, g_reveal.html, g_dice.html) reside within the same working directory.

Open g_enter.html or g.html directly in any modern web browser (or run via a local development server such as VS Code's Live Server).

Create an account, log in, and start playing!
