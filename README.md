# Tennis Mind Coach 🎾🧠

An open-source, multi-platform AI skill that acts as a top-tier sports psychologist and personal mind coach for tennis players aged 10 to 60 (from beginners to professionals). It is designed to help players manage match nerves, handle pressure, lock in focus, and build championship routines.

## 📄 Core Prompt File
The universal, platform-agnostic natural language prompt instructions are located in the [skill.md](./skill.md) file in this repository.

## ⚖️ License & Authorship
This project is open-source and licensed under the **MIT License**. 

**Copyright (c) 2026 Rajeev Mankar**

### Public Usage & Attribution Terms:
You are free to use, modify, and distribute this AI skill for personal or commercial use. However, under the terms of the MIT License, **you must include the original copyright notice and credit to Rajeev Mankar** in all copies or substantial modifications of this software or prompt architecture.

---

## 🚀 How to Implement This Skill Across Different AI Platforms

### 1. Claude (Anthropic)
* **Claude Projects (Recommended)**: 
  1. Open Claude and create a new **Project**.
  2. Copy the entire contents of `skill.md` and paste it into the **Set Instructions** text panel.
  3. Upload your past match notes or training schedules into the Project Knowledge base for deeper context.
* **Claude API**: Pass the entire text of `skill.md` as the string value for the `system` parameter in your API payload.

### 2. ChatGPT / Custom GPTs (OpenAI)
1. Log into ChatGPT and navigate to **Explore GPTs** -> **Create**.
2. Go to the **Configure** tab.
3. Paste the complete text of `skill.md` directly into the **Instructions** text box.
4. Turn on **Capabilities** (Web Search/Code Interpreter) if you want the coach to analyze tournament data arrays.

### 3. Gemini / Gems (Google)
1. Open Gemini and select **Gems** -> **Create a custom Gem**.
2. Give your Gem a name (e.g., `Tennis Mind Coach`).
3. Paste the contents of `skill.md` directly into the **Instructions** box.
4. Save the Gem.

---

## 🛠️ How to Initialize a Session
Once you load the skill into your preferred AI platform, start your chat by typing:
`@tennis_mind_coach Hello! Let's set up my profile.`
=======
# tennis-mind-coach
A personal tennis mind coach: a top-tier sports psychologist. Used by tennis player or a parent or coach 

