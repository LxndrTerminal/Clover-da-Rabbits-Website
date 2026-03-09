# 🕵️‍♂️🐰 Project: Agent Clover - The Great Easter Heist

An immersive, high-tech Easter scavenger hunt designed for mobile devices. This project transforms a traditional indoor egg hunt into a "Secret Agent" operation. Physical mission cards hidden around the house trigger cinematic video transmissions from **Agent Clover**, leading the "agents" to the final Easter stash.

## 🤖 The AI & Creative Stack

This mission was built using a cutting-edge AI-native workflow:

* **Video Generation:** [Hailuo AI](https://hailuoai.com/) for cinematic footage of Agent Clover, edited in **CapCut**.
* **Voice Synthesis:** [ElevenLabs](https://elevenlabs.io/) for a professional-grade tactical "Easter Bunny" voiceover.
* **Asset Creation:** [Google Gemini](https://gemini.google.com) for character concept art and Easter-themed mission assets.
* **Graphic Design:** [Canva](https://www.canva.com/) for the final design of the physical "Top Secret" Easter mission cards.
* **QR Engine:** [Segno (Python)](https://github.com/heuer/segno) for high-resolution, reliable QR codes.

## 🛠 Web Technology Stack

* **Frontend:** HTML5, CSS3, and Vanilla JavaScript.
* **API:** [YouTube IFrame Player API](https://developers.google.com/youtube/iframe_api_reference) for controlled mission playback.
* **Hosting:** [Vercel](https://vercel.com) for instant global deployment via GitHub CI/CD.

## 🕵️‍♂️ Tactical Easter Features

### 🛡 The Spy-Shield
To keep the agents focused on the mission (and prevent them from accidentally closing the transmission), a **transparent CSS shield** layers over the player, blocking YouTube UI interactions while the video plays.

### 🎭 The Connection Curtain
A custom **"Signal Decryption" curtain** hides the YouTube interface during the buffering phase. This maintains the "Easter Agent" immersion by ensuring the first thing the kids see is the mission briefing, not a loading bar.

### 🔄 Tactical Fullscreen
Automatically triggers the **Fullscreen API** upon user interaction, ensuring the hunt is viewed in a cinematic landscape mode on any smartphone.

## 🏠 Mission Map

| Clue ID | Physical Location | Mission Phase |
| :--- | :--- | :--- |
| `0` | **Mission Brief** | Handshake: The Heist Begins | 
| `1-9` | Indoor Drop Points | Tactical Egg Retrieval | 
| `10` | **Final Briefing** | Mission Success: The Easter Stash | 

## 📁 Field Assets
<div align="center">
<p><i><b>Asset 00: The Briefing Card</b><br>
<img src="./assets/1.png" width="200" style="border-radius: 50%;" alt="Starting card">
  <br>
<p><i><b>Asset 03: Clue Card Example)</b><br>
<img src="./assets/4.png" width="200" style="border-radius: 50%;" alt="Clue card">
  <br>  
  <p><i><b>Asset 11: Final Card</b><br>
<img src="./assets/11.png" width="200" style="border-radius: 50%;" alt="Final card">
<br>
    <p><i><b>Asset 12: Card (Back)</b><br>
<img src="./assets/12.png" width="200" style="border-radius: 50%;" alt="Back of card">
<br>

</div>

---

## 🛠 For the Mission Commander
* For setup and automation, see [DEVELOPMENT.md](./DEVELOPMENT.md).
* For a full breakdown of hidden secrets and Easter eggs, see [SPOILERS.md](./SPOILERS.md) (Level 5 Clearance required).

## 🕵️‍♂️ The Lore: Who is Agent Clover?

**Agent Clover** is a high-ranking operative in the **Bunny Intelligence Agency (BIA)**. 

* **The Backstory:** After the "Great Carrot Crunch of '24," Clover was assigned to the Western Cape sector to oversee the security of high-value seasonal assets. 
* **The Mission:** In this specific hunt, Clover’s care packages has been hijacked by "The Shadow Warren." Agents must scan the physical relay points (the Toaster, the Fridge) to help Clover retrieve her care packages and secure the house.
* **Character Assets:** Generated using **Google Gemini**, **Hailuo** (visuals) and **ElevenLabs** (voice ID: WtA85syCrJwasGeHGH2p).

## 🕵️‍♂️ Classified Intel (Easter Eggs)

The BIA network is known for its deep encryption and hidden frequencies. While the main mission path (Clues 1-11) is clear, there are **rumors of "Ghost Signals"** hidden within the codebase and the physical environment.

* **Status:** Multiple non-sequential relay points detected.
* **Access:** Level 5 Clearance required. 
* **Hint:** Not all clues follow the linear path of the Great Heist. Some exist only for those who look "outside the burrow."

> "If you find a signal that shouldn't exist... you didn't hear it from me." — Agent Clover
