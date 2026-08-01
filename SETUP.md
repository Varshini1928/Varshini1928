Setup Guide

Upload the supplied files to the GitHub profile repository Varshini1928/Varshini1928:

Varshini1928/
├── README.md
└── .github/
    └── workflows/
        ├── arcade.yml
        └── snake.yml

Run the games

Open the repository Actions tab.

Run Generate Contribution Snake.

Run Generate Contribution Arcade.

Wait for both workflows to show a green check.

Refresh the GitHub profile.

The workflows create or update an output branch containing the generated SVG files.

Push from VS Code

git add README.md .github/workflows/snake.yml .github/workflows/arcade.yml
git commit -m "Redesign profile with contribution games"
git push origin main

Workflow permission error

Open Settings → Actions → General → Workflow permissions, select Read and write permissions, save, and run the workflows again.
