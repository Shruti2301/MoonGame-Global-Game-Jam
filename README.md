# 🌕 MoonGame
### A Global Game Jam Entry

> *"It's About Time. Take a Walk."*
> Built in 48 hours for the Global Game Jam.

---

## 🎮 Concept

You are a cosmonaut sent to repair a broken communication tower on the lunar surface.

The repair goes wrong. The tower shocks you — your helmet cracks, your oxygen bleeds out.

Now you have one objective: **get back to the lander before you suffocate.**

But as your oxygen drops, your mind starts to go. Hallucinations creep in — enemies that aren't there, or maybe are. Fight through them, manage your panic, and make it home.

---

## 🕹️ Gameplay Loop

```
Land on Moon
    ↓
Walk to Communication Tower
    ↓
Attempt Repair → Tower shocks you → Mask breaks
    ↓
Oxygen begins depleting
    ↓
Hallucinated enemies appear as O₂ falls
    ↓
Fight / evade enemies while navigating back
    ↓
Reach the lander in time → Survive
          OR
Oxygen hits zero → Game over
```

---

## 🎯 Diversifiers

| Diversifier | How it's used |
|---|---|
| **It's About Time** | Core tension — you're racing against a countdown you can *feel* (oxygen depleting, vision deteriorating) |
| **Take a Walk** | The entire game is a walk: from lander → tower → lander, with the journey growing more hostile as your mind deteriorates |

---

## 🛠️ Built With

- **Godot Engine** — primary game engine
- **Unreal Engine** — Moon Landing environment prototype (`UnrealMoonLanding/`)
- **GDScript** — game logic and mechanics
- **Global Game Jam 2025**

---

## 📁 Repository Structure

```
├── UnrealMoonLanding/       # Unreal Engine first-person environment prototype
│   └── MoonLanding/
├── assets/                  # Art, audio, and visual assets
├── builds/                  # Exported game builds
├── docs/                    # Design docs and notes
├── scenes/                  # Godot scene files
├── scripts/                 # GDScript game logic
├── src/                     # Core source files
├── tests/                   # Test scenes / builds
└── tools/                   # Editor tools and utilities
```

---

## 🚀 How to Play

### Play in Browser
*[Link to itch.io build — add when published]*

### Run Locally (Godot)
1. Install [Godot Engine 4.x](https://godotengine.org/download/)
2. Clone this repository:
   ```bash
   git clone https://github.com/Shruti2301/Global-GameJam.git
   ```
3. Open Godot → **Import Project** → select the project folder
4. Press **F5** or click **Play** to run

---

## ⚠️ Current Status

> **Not Fully Functional Yet** — this is a jam build. Some systems are in progress.

| System | Status |
|---|---|
| Player movement | ✅ Working |
| Oxygen depletion | ✅ Working |
| Tower interaction | 🔧 In progress |
| Hallucination enemies | 🔧 In progress |
| Win / lose conditions | 🔧 In progress |
| Audio | 🔧 In progress |

---

## 👾 Design Notes

The core loop is deliberately slow and lonely — the Moon is vast and silent, and that emptiness *should* feel wrong. As oxygen drops, the game destabilizes: enemies that spawn are meant to be ambiguous. Are they real? Is the player's mind going? The answer is left open.

The two diversifiers reinforce each other: the walk is the timer. The further you've walked from the lander, the less time you have left.

---

## 🤝 Team

| Name | Role |
|---|---|
| Shruti Mandaokar | Developer |
| *[Add teammates]* | *[Role]* |

---

## 📜 License

Built for the Global Game Jam. Game jam submissions are open by default — feel free to explore the code. Please credit the team if you build on it.

---

*Made in 48 hours. Sleep-deprived. Worth it.*
