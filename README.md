# 🦕 dino-rl

A Q-learning agent that learns to play the Chrome Dinosaur game — built from scratch.

> Reinforcement learning meets a classic browser game. Watch the dino learn to survive.

---

## 🎯 Goals

- [ ] Implement Q-learning from scratch (no RL libraries for the core logic)
- [ ] Train an agent that can play the dino game
- [ ] Visualize the learning process (reward curve, Q-value heatmap)
- [ ] Reach complete project standard (see below)

**Complete Project Standard**
> - Non-technical users can understand what this repo does from the README
> - Demo video of the trained agent playing
> - Clear explanation of RL concepts used, architecture, and how to run
> - Both English and Chinese README provided

---

## 🗺️ Task Structure

> README tracks down to Task level. Sub-tasks are managed in Notion.

```
🏔️ Milestone: Environment ready
  └─ 📦 Feature: Playable game environment wrapper
       ├─ ✅ Task: Research environment options (custom / gym wrapper)
       ├─ ✅ Task: Implement state representation
       └─ ✅ Task: Define reward function

🏔️ Milestone: Basic agent working
  └─ 📦 Feature: Q-learning agent that can play
       ├─ ✅ Task: Implement Q-table
       ├─ ✅ Task: Implement epsilon-greedy exploration
       ├─ ✅ Task: Training loop
       └─ ✅ Task: Verify agent improves over time

🏔️ Milestone: Training visualized
  └─ 📦 Feature: Learning process visualization
       ├─ ✅ Task: Plot reward curve
       ├─ ✅ Task: Plot Q-value changes
       └─ ✅ Task: Record agent playing (before vs after training)

🏔️ Milestone: Complete project standard
  └─ 📦 Feature: Docs and demo
       ├─ ✅ Task: Record demo video of trained agent
       └─ ✅ Task: Finalize English + Chinese README
```

---

## 🧠 RL Concepts Applied

| Concept | Description | Status |
|---|---|---|
| Q-learning | Core algorithm | 🔴 Not started |
| State representation | How the game state is encoded | 🔴 To be designed |
| Reward shaping | What counts as good / bad | 🔴 To be designed |
| Epsilon-greedy | Exploration vs exploitation | 🔴 Not started |
| Q-table / DQN | Table-based or neural network | 🔴 To be decided |

---

## 🗂️ Project Structure

```
dino-rl/
├── README.md               ← This file (English)
├── README_zh.md            ← Chinese version
├── src/
│   ├── env/                ← Game environment wrapper
│   ├── agent/              ← Q-learning agent
│   └── train.py            ← Training entry point
├── notebooks/              ← Experiments, reward curves, analysis
├── docs/
│   └── rl-design.md        ← Design decisions and notes
└── demo/                   ← Demo video or GIF of trained agent
```

---

## 🗺️ Roadmap

| Phase | Task | Status |
|---|---|---|
| Phase 1 | Set up game environment | 🔴 Not started |
| Phase 2 | Implement basic Q-learning agent | 🔴 Not started |
| Phase 3 | Train and tune | 🔴 Not started |
| Phase 4 | Visualize learning process | 🔴 Not started |
| Phase 5 | Record demo, write docs | 🔴 Not started |

---

## 🔗 Related

- ML experiments context → [ml-experiments](../ml-experiments/README.md)

---

## 📝 Progress Log

| Date | What I did | Next step |
|---|---|---|
| — | Initialized repo | Research environment setup options |

---

## 📖 中文說明

請見 [README_zh.md](./README_zh.md)

---

*Last updated: please update this date after each session*
