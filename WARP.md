# Cocktails - Project Rules

## Changelog Requirement

**IMPORTANT**: All changes to files inside or outside this repository MUST be documented in the `Logs/changelog.md` file. This includes:

- Adding new recipes
- Modifying existing recipes
- Updating documentation
- Adding or removing categories
- Any structural changes to the repository

Each changelog entry must include:
- Date and time (local time)
- Description of changes made
- Files affected

## Recipe Guidelines

1. **File Naming**: Use lowercase with hyphens for recipe filenames (e.g., `old-fashioned.md`, `pina-colada.md`)
2. **Measurements**: Use standard bartending measurements (oz, ml, dashes, barspoons)
3. **Consistency**: Follow the recipe template format for all new recipes
4. **Attribution**: Credit sources for recipes that are not original creations

## Documentation Standards

- Keep README.md updated with accurate directory structure
- Update table of contents when adding new sections
- Ensure all documentation files remain free of contradictions

## Image Guidelines

### Storage

All cocktail images are stored in the `Images/` directory at the repository root.

### Naming Convention

Image files should match their recipe filename with the appropriate extension:
- Recipe: `Recipes/Modern/bourbon-midnight-flip.md`
- Image: `Images/bourbon-midnight-flip.png`

### Adding Images to Recipes

Use a relative path from the recipe file to the Images directory:

```markdown
![Cocktail Name](../../Images/cocktail-name.png)
```

### Image Sources

- **AI-generated images**: Use ChatGPT, DALL-E, or similar tools to generate cocktail images
- **Free stock photos**: Pexels (pexels.com) offers free, stable image URLs if AI generation isn't available
- **Original photos**: Personal photos of prepared cocktails are welcome
