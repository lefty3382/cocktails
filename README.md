# Cocktails

A repository for storing cocktail recipes and cocktail information.

## Table of Contents

- [Overview](#overview)
- [Cocktail List](#cocktail-list)
- [Directory Structure](#directory-structure)
- [Recipe Format](#recipe-format)
- [Categories](#categories)
- [Contributing](#contributing)

## Overview

This repository serves as a personal collection of cocktail recipes, including classic cocktails, modern creations, and variations. Each recipe includes ingredients, measurements, preparation instructions, and additional notes about the drink's history or serving suggestions.

## Cocktail List

Quick access to all recipes:

```
Recipes/
├── Classic/
│   └── (none yet)
├── Modern/
│   └── Bourbon Midnight Flip ─── Recipes/Modern/bourbon-midnight-flip.md
├── Tiki/
│   └── (none yet)
├── Shots/
│   └── (none yet)
└── Non-Alcoholic/
    └── (none yet)
```

| Category | Cocktail | Link |
|----------|----------|------|
| Modern | Bourbon Midnight Flip | [View Recipe](Recipes/Modern/bourbon-midnight-flip.md) |

## Directory Structure

```
cocktails/
├── README.md              # This file - project overview and documentation
├── WARP.md                # Project rules and guidelines
├── Images/                # Cocktail images (named to match recipe files)
├── Logs/
│   └── changelog.md       # Record of all changes to the repository
└── Recipes/
    ├── Classic/           # Traditional and timeless cocktails
    ├── Modern/            # Contemporary cocktail creations
    ├── Tiki/              # Tropical and tiki-style drinks
    ├── Shots/             # Shot recipes
    └── Non-Alcoholic/     # Mocktails and alcohol-free drinks
```

## Recipe Format

Each recipe is stored as a Markdown file with the following structure:

- **Name**: The cocktail's name
- **Category**: Type of cocktail (Classic, Modern, Tiki, etc.)
- **Glass**: Recommended glassware
- **Ingredients**: List of ingredients with measurements
- **Instructions**: Step-by-step preparation guide
- **Garnish**: Recommended garnishes
- **Notes**: History, variations, or serving tips

## Categories

| Category | Description |
|----------|-------------|
| Classic | Traditional cocktails with established recipes |
| Modern | Contemporary creations and craft cocktails |
| Tiki | Tropical drinks with rum and exotic flavors |
| Shots | Small, quick drinks served in shot glasses |
| Non-Alcoholic | Mocktails and alcohol-free alternatives |

## Contributing

To add a new recipe:
1. Choose the appropriate category folder
2. Create a new `.md` file named after the cocktail (e.g., `margarita.md`)
3. Follow the recipe format template
4. Document changes in `Logs/changelog.md`
