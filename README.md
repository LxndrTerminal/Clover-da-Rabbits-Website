# 🕵️‍♂️🐰 Project: Agent Clover - The Great Easter Heist

An immersive, hybrid-reality Easter scavenger hunt. This project transforms a traditional indoor egg hunt into a live tactical operation using a custom-built SaaS platform to deliver mission-critical intel in real-time.

## 🤖 The AI & Creative Stack

This mission was built using a cutting-edge AI-native workflow:

* **Asset Creation:** [Google Gemini](https://gemini.google.com) for character concept art and Easter-themed mission assets.
* **Graphic Design:** [Canva](https://www.canva.com/) for the final design of the physical "Top Secret" Easter mission cards.
* **QR Engine:** [Segno (Python)](https://github.com/heuer/segno) for high-resolution, reliable QR codes.

## 🛠 Web Technology Stack (V2 Redesign)
The platform has been upgraded from a static site to a dynamic, database-driven terminal:

* **Frontend:** Vanilla JavaScript with Async/Await architecture.
* **Backend-as-a-Service:** Supabase for real-time mission data and riddle persistence.
* **Deployment:** Vercel with a custom CI/CD pipeline utilizing sed for secure environment variable injection during build-time.

## 🕵️‍♂️ Tactical Easter Features

### 📡 The BIA Secure Terminal
The heart of the V2 redesign. The website now functions as a dual-mode operative tool:
  **Tactical Text Mode:** A live-updating terminal that fetches "Decrypted Intel" (riddles) from the Supabase cloud.

### 🔐 The "Handler" Override
Each mission station starts in an uninitialized state. The Handler (Parent/Organizer) can scan the station, enter a custom local riddle into the secure terminal, and "Lock" it. Once locked, the station becomes a permanent mission objective for the Agents (Players).

### 💾 Local-First Resilience
Built with a Fail-Safe Fallback system. If the operative loses internet connectivity in a "Dead Zone" (like behind the fridge), the terminal automatically switches to Browser LocalStorage to ensure the heist continues without interruption.

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

## 🛠 Setup for Mission Commanders (Devs)

To deploy your own BIA network:
* Connect your GitHub to Vercel.
* Initialize a Supabase table named mission_data with columns card_id (text), riddle_text (text), and is_locked (bool).
* Configure the Build Command to inject your API keys into the index.html during the build process.

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
