**🌍 Globe Racer — Geography Millionaire**

A fast-paced, browser-based geography trivia game inspired by Who Wants to Be a Millionaire? — but racing you across the globe instead. Answer 20 questions that scale from easy to expert, learn fun cultural facts along the way, use lifelines to survive tough questions, and bank your winnings before it's too late.

No install. No dependencies. No build step. Just open the HTML file and play.

**🎮 Play Now**
Download/clone this repo.
Open index.html in any modern browser (Chrome, Firefox, Safari, Edge).
Click START RACE and go!
Works fully offline — all game logic, styles, and audio are self-contained in a single HTML file.

**✨ Features**
20 questions, Easy → Expert — covering Africa, Asia, Europe, the Americas, the Middle East, and the Pacific.
Millionaire-style prize ladder — from $100 up to $1,000,000, with guaranteed checkpoints at Question 5, 10, and 15.

Three lifelines:
🔀 50/50 — removes two wrong answers
⏱️ +10 Seconds — extra time when the clock is tight
💰 Walk Away — cash out your current winnings instead of risking it all
Typing Racer mode — the final three expert questions require you to type the answer, with a live mini race-car animation that moves as you type.
Juicy feedback — particle bursts, screen shake on wrong answers, animated score count-ups, confetti rain on a full win, and a "FAST!" bonus pop for quick correct answers.
Cultural facts — every question reveals an interesting fact about the place after you answer.
Full keyboard + touch support — play comfortably on desktop or mobile.
Pause, Resume, Restart, Game Over states — all instant, no reloads needed.
Local high-score leaderboard — top 10 scores saved in your browser via localStorage.
Runs at a smooth 60fps — single requestAnimationFrame loop handles the timer, screen shake, and canvas particle effects; everything else uses lightweight CSS transitions.

**🕹️ Controls**
Action	Keyboard	Touch/Mouse
Select answer	1 2 3 4 or A B C D	Tap the answer button
Submit typed answer	Enter	Tap GO 🚀
50/50 lifeline	F	Tap 50/50
+10 seconds	T	Tap +10s
Walk away (cash out)	W	Tap Walk Away
Pause / Resume	P or Esc	Tap ⏸ / ▶
Continue to next question	Enter	Tap Continue
Start game	Enter / Space	Tap START RACE

**🏆 Scoring & Reward System**
Milestone	Reward Behavior
Q1 – Q4	Build your winnings question by question
Q5 (checkpoint)	Winnings locked in — a wrong answer after this drops you only to this level
Q6 – Q9	Continue climbing
Q10 (checkpoint)	Second safety net
Q11 – Q14	Keep pushing into Hard/Expert territory
Q15 (checkpoint)	Final safety net before the big leagues
Q16 – Q20	High-risk, high-reward — answer all 20 to become a World Champion
If you answer incorrectly, you fall back to the last checkpoint you passed. You can also Walk Away at any time (after Q1) to bank your current winnings safely.

**Titles earned based on performance:**
🧳 Tourist — fewer than 5 correct
🧭 Explorer — 5+ correct
🗺️ Adventurer — 10+ correct
🌍 Globetrotter — 15+ correct
🏆 World Champion — all 20 correct
🛠️ Tech Stack
Pure HTML, CSS, and vanilla JavaScript — no frameworks, no libraries, no build tools.
Canvas API for particle effects (confetti, correct/incorrect bursts).
Web Audio API for synthesized sound effects (no audio files needed).
localStorage for persisting high scores and sound preference between sessions.
Fully responsive layout — adapts from desktop to small mobile screens.

**🌐 Browser Support**
Tested and optimized for the latest versions of:

Chrome / Edge (desktop & mobile)
Firefox
Safari (desktop & iOS)
Requires JavaScript enabled. No internet connection needed after the page loads.

📜 License
Free to use, modify, and distribute for personal or educational projects. Attribution appreciated but not required.

