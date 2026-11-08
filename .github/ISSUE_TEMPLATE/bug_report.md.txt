---
name: Coaching Logic Failure
description: Report an edge-case where the AI loses its persona, breaks rules, or gives poor advice.
title: "[LOGIC BUG]: "
labels: bug, prompt-tuning
assignees: rajeevmankar1
---

### 🚨 Describe the Logic Failure
Provide a clear, brief explanation of where the AI deviated from its intended coaching persona or rules.

### 🔄 The Input Prompt / Message
What did the player, parent, or coach say to the AI? Paste the text or describe the media format here:
```text
(Paste input message here)
```

### 📉 The AI's Actual Response
What did the AI actually reply with? 
```text
(Paste the incorrect AI response here)
```

### 🎯 The Expected Behavior
Based on the rules in `skill.md`, what *should* the AI have done or said instead? (e.g., "It should have used the Courtside mode and kept its response under 40 words, but it gave a long bulleted list instead.")

### ⚙️ Environment Details
- **AI Platform Used:** [e.g., Claude Projects, ChatGPT Custom GPT, Gemini Gems]
- **Player Profile Context:** [e.g., Age 14, National Level, High Pressure Match]

### 💡 Suggested Fix (Optional)
If you know how to tweak the markdown sections in `skill.md` to prevent this failure, let us know your idea!
