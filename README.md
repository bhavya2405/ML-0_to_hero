# ML Zero-to-Hero Roadmap

Welcome to the **ML Zero-to-Hero** repository! This project contains all the exercises, projects, and notes you’ll build as you progress from Python beginner to ML expert.

---

## Repository Structure

```
ml-zero-to-hero/
├── README.md          # This file
├── .gitignore         # Ignored files for Git
├── LICENSE            # Repository license (e.g., MIT)
├── Roadmap.md         # Detailed syllabus and project list
├── 1_python_foundations/
│   ├── exercises/     # Small drills on syntax, data types, control flow
│   ├── projects/      # Mini-projects like number-guessing-game
│   │   └── number-guessing-game/
│   │       ├── number_guess.py
│   │       └── README.md
│   └── notes.md
├── 2_math_refresher/
│   ├── linear_algebra/
│   ├── calculus/
│   └── statistics/
├── 3_data_handling_viz/
│   ├── pandas_tutorial.ipynb
│   └── eda_project/
├── …
└── 10_soft_skills/
    └── docs_and_ethics.md
```

---

## Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/<your-username>/ml-zero-to-hero.git
   cd ml-zero-to-hero
   ```

2. **Create a virtual environment**

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate   # macOS/Linux
   .\.venv\Scripts\activate  # Windows
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Explore Stage 1**

   * Navigate to `1_python_foundations/`
   * Start with exercises in `exercises/` and then complete the mini-project in `projects/`

---

## Roadmap Overview

Refer to [Roadmap.md](Roadmap.md) for the full syllabus, project list, and progress tracking using GitHub Issues & Projects.

---

## Contributing

1. Create an issue for any new exercise or project idea.
2. Fork the repo and create a branch:

   ```bash
   git checkout -b feat/python/your-feature
   ```
3. Commit your changes:

   ```bash
   git commit -m "feat: add description of your change"
   ```
4. Push to your fork and open a Pull Request.

Please follow the same folder structure and update this README with any new instructions if needed.

---

## License

This project is licensed under the [MIT License](LICENSE).
