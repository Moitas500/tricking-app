# 🌀 Tricking Progress RPG – Database & System Design

**Tricking Progress RPG** is an application designed for tricking athletes to track their progress, learn tricks, build combos, and receive personalized recommendations.  
The app functions like an **RPG**, where the user gains experience, levels up, and improves stats as they train.

---

## 📌 Main Features

- Tracking of tricks learned by the user.
- Mastery level and proficiency for each trick.
- RPG-style experience and leveling system.
- Creation of combos and trick sequences.
- Combo recommendations based on the user’s skillset.
- Detailed logs of practice sessions.
- Tracking attempts, successful landings, and variations.
- Classification by category, difficulty, and variations.
- User statistics (learned tricks, mastered variations, combos, etc.).

---

## 🗂️ Database Model

The project uses a relational database model with a focus on:

- **Main entities:** `User`, `Trick`, `Combo`
- **Bridge tables:** `UserTrick`, `ComboTrick`, `UserCombo`
- **Practice system:** `Practice`, `PracticeDetails`
- **Classification:** `Category`, `Difficulty`, `Variation`

---

## 📎 ER Diagram

![ER Diagram](https://github.com/user-attachments/assets/b8a2dd5e-0646-4f8b-89f3-5697dbdc97c4)
