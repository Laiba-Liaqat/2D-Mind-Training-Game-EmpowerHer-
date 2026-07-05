# EmpowerHer: Street Boundary Rehearsal

**EmpowerHer: Street Boundary Rehearsal** is an interactive, immersive 2D training application designed to mentally prepare women for street harassment encounters. It enables players to practice active verbal self-defense, make critical safety decisions under pressure, and build spatial safety awareness in a risk-free digital sandbox.

The application addresses a crucial societal challenge: the psychological conditioning that often pressures women to prioritize social politeness over personal safety during uncomfortable public situations.

---

## 🎯 Core Objectives & Motives

1. **Breaking the "Polite Freeze" Conditioning**: Rehearses direct, clear boundary statements to replace compliance-oriented silence or stress-induced hesitation with assertive, decisive responses.
2. **Cognitive Rehearsal for Street Preparedness**: Builds proactive mental frameworks to identify environmental threats early, claim physical space, and plan exit vectors.
3. **Engaging Safety Education**: Translates complex psychological safety strategies (vocal, spatial, and social) into an interactive arcade medium.

---

## 🎮 Game Architecture & Core Working Flow

The user navigates from high-level educational training to active scenario-based street simulation:

```
[ Title Screen ]
       │
       ▼
[ Educational Hub ]  ◄── (Learn core de-escalation strategies & boundary-setting)
       │
       ▼
[ Mission Selection ] ◄── (Choose between Suburban, Transit Hub, or Park Walkway)
       │
       ▼
[ Active Street Simulation ] ──(Harasser Closes Distance)──► [ Interactive Choice-Point Dialogue ]
       │                                                                  │
       ├─► Maintain Lighted Zone (Lamps)                                 ├─► Assertive Choice (Success)
       ├─► Deploy Defensive Tools (Alarms, Voice, Calls)                  └─► Passive Choice (Confidence Penalty)
       │
       ▼
[ Reach Sanctuary Zone (Victory) ] OR [ Boundary Depleted (Defeat Screen) ]
```

### The Gameplay Loop:
1. **Learn & Prepare**: Review the **Educational Safety Hub** to understand key psychological defense strategies (vocal boundaries, situational awareness, phone support, bystander activation).
2. **Select & Navigate**: Pick a mission and navigate the character through challenging streets using the **Keyboard (W,A,S,D / Arrows)** or the **Virtual Touch D-Pad**.
3. **Maneuver & Survive**: Traverse dark environments, staying inside glowing golden **Street Lamp circles** to preserve your Boundary Confidence while avoiding loiterers.
4. **Deploy Countermeasures**: Spend collected resources to sound alarms, project vocal boundary pushes, or trigger active phone call shields.
5. **Resolve Scenarios**: Face direct encounters through interactive **Choice-Point Dialogues**, selecting assertive responses to maintain confidence.
6. **Reach Safety**: Secure arrival at the glowing green **Sanctuary Zone** to complete the level.

---

## 🛡️ Key Features & Defensive Tools

### 🕹️ Interactive Defensive Arsenal
* 🔔 **Personal Alarms (Indigo Tokens / Spacebar)**: Sound a high-decibel acoustic whistle that temporarily disorients and freezes nearby loiterers in their tracks.
* 🗣️ **Assert Boundaries (Emerald Tokens / Q)**: Shout a firm verbal command (*"Step back, I need space!"*) that projects a shockwave, physically pushing away obstacles.
* 📞 **Emergency Phone Calls (Cyan Tokens / E)**: Initialize a mockup phone support line that projects a protective communication field to prevent loiterers from approaching.

### 🗺️ Diverse & Scaled Level Design
* **Level 1: Suburban Sidewalk**: A training ground focused on basic movement, light zone mechanics, and gentle obstacle evasion.
* **Level 2: Transit Station Hub (Expanded Challenge)**: A 2,000px-wide platform layout where players must traverse crowded subway rails, avoid fast-moving commuters, utilize Emergency SOS Columns, and dodge static platform obstacles to reach the distant transit exit at 1,880px.
* **Level 3: Midnight Park Walkway (Marathon Challenge)**: A 2,400px-wide darkened woodland park containing a shimmering water pond, wooden guideposts, and a high density of patrolling stalkers. Players must carefully map lamp-to-lamp movements to reach the ranger sanctuary at 2,280px.

---

## 🎨 Immersive Visual Systems & Assets

To convey safety motives and provide immediate clarity, the application features a distinctive, high-contrast dark visual design:

* **High-Contrast Metro Platform Overlay**: Designed with fluorescent cyan-green floor lanes guiding commuters toward safe exits, concrete structural columns with realistic depth shadowing, and pulsing red emergency help beacons.
* **Tranquil Midnight Park Environment**: Styled with dark forest teal textures, winding slate walkways, a glistening animated pond with floating green lily pads, and circular golden-green firefly orbits that dance around active streetlights.
* **Vector Art Safety Illustrations**:
  * **Educational Guides**: Clean, empowering hand-crafted vector art depicting verbal boundaries, situational awareness, phone shields, and community bystander support.
  * **Level Selectors**: Artistic landscape thumbnails for each mission to prepare players for the environment's layout.
  * **Victory & Defeat Screens**: Beautiful, emotional illustrations of reaching a warm, cozy bookstore sanctuary versus supportive hands of mutual coaching and comfort.

---

## 🛠️ Technical Stack

* **Framework**: React 18 with Vite for lightweight, instant SPA client-side rendering.
* **Language**: TypeScript for complete type-safety across gameplay and canvas physics engines.
* **Graphics**: HTML5 Canvas running custom high-performance vector rendering loops, dynamic particle systems, and concentric light physics.
* **Styling & Animation**: Tailwind CSS for responsive spacing, custom neon layouts, and Motion for elegant transition animations.
* **Iconography & Typography**: Lucide React icons paired with `Space Grotesk` (headings), `Inter` (content), and `JetBrains Mono` (numerical HUD counters).

---

## 💻 Local Installation & Setup

To run this project locally on your machine:

1. **Verify Prerequisites**: Ensure you have [Node.js (v18+)](https://nodejs.org/) installed.
2. **Navigate and Install**:
   ```bash
   cd path/to/project
   npm install
   ```
3. **Run Dev Server**:
   ```bash
   npm run dev
   ```
   Open your browser at the local URL shown in your terminal (typically `http://localhost:3000`).
4. **Compile and Build**:
   ```bash
   npm run build
   ```

---

*EmpowerHer is a risk-free safe space for street boundary practice. Walk with confidence, protect your space, and reclaim your public streets.*
