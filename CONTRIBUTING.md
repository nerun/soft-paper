# Contributing to Soft Paper

Thanks for helping out.

## Reporting a problem

Open an issue with:

- What you expected and what you saw (a screenshot helps most)
- Light or dark mode
- Your Obsidian version, and which Style Settings toggles you have on
- Any CSS snippets or other themes' snippets you have enabled

## Suggesting a change

Open an issue first to talk it through. Pull requests are welcome after that.

## Guidelines for CSS changes

- Edit `theme.css` only. There is no build step.
- No `!important` and no `:has()`. Raise selector specificity or use Obsidian's CSS variables instead.
- Check both light and dark mode.
- Keep it light: no heavy animations, filters or broad wildcard selectors. Soft Paper exists to stay fast.

## License

By contributing, you agree that your contributions are licensed under GPL-3.0, the same license as the theme.
