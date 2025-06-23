🧠 Tower of Hanoi AI Simulation

Visual demonstration of how an AI "thinks" its way through the classic Tower of Hanoi puzzle — and where that thinking fails.

This project is part of a broader exploration inspired by the paper The Illusion of Thinking, which examines how Large Reasoning Models (LRMs) perform under increasing problem complexity. Spoiler: more thinking doesn’t always mean better thinking.
🎯 What this is

An educational Python simulator that:

    Graphically displays the Tower of Hanoi puzzle.

    Animates the steps of a recursive AI-generated solution.

    Increases the number of disks until the AI’s reasoning begins to collapse.

    Visually signals failure conditions (e.g., token overuse, logical breakdowns).

    Simulates AI "thoughts" through recursive solving (like Chain-of-Thought reasoning).

📽 Why it matters

In the paper, LRMs like Claude 3.7 or DeepSeek-R1 solve Hanoi with 3–6 disks perfectly. But past 8–10 disks, accuracy collapses — even when given the algorithm.

This simulation makes that collapse visible.

    “It’s like watching a chess master forget how the game works once the board gets too crowded.”

💻 Run it locally

git clone https://github.com/your-username/hanoi-collapse-ai
cd hanoi-collapse-ai
pip install -r requirements.txt
python tower_of_hanoi_ai_sim.py

Requirements:

    Python 3.8+

    pygame

📂 Folder structure

This script is part of a broader project simulating four puzzles from the paper:

    Tower of Hanoi ✅ (this repo)

    Checker Jumping 🔜

    River Crossing 🔜

    Blocks World 🔜

Each puzzle is being turned into a standalone simulator to show how AI fails gracefully (or not) as complexity grows.
📚 Reference

This repo is based on findings from:

    Shojaee et al. — The Illusion of Thinking: Understanding the Strengths and Limitations of Reasoning Models (PDF)

    .

⚠️ License

MIT — go wild, but cite responsibly.
