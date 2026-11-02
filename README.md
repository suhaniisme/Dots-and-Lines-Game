# Silhouette Architect 📐✨

A browser-based line and Bezier curve puzzle game where players act as speed architects, drawing geometric shapes from memory based on enigmatic clues, strict countdown timers, and pattern-matching accuracy thresholds.

---

## 🎮 Game Features

* **Dual Drawing Modes**: Switch dynamically between **Straight Lines** and **Bezier Curves** with control point adjustments.
* **Smart Pattern Matching**: Features an automated canvas rasterizer that verifies your drawing against the target silhouette requiring at least an **80% visual overlap** to clear.
* **Dynamic Clues**: On-screen keywords and descriptive 1-liner clues help players guess and construct the target shape. Need extra help? Click **Show Answer** (with a competitive life penalty if used before drawing!).
* **Progressive Difficulty & Timers**:
  * **Stages 1–3**: 30 seconds
  * **Stages 4–6**: 45 seconds
  * **Stages 7–10**: 75 seconds (including the final **Grand Dragon** challenge)
* **Survival Mechanics**: A 3-lives system (`❤️❤️❤️`) coupled with witty, sarcastic loss messages whenever the timer expires or accuracy falls short.
* **Non-Repeating Shape Pool**: Randomly shuffles 20 unique geometric puzzles across stages to keep every playthrough fresh.
* **Persistent Progress**: Powered by `localStorage` to securely track unlocked levels and rankings.

