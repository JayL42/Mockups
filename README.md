# Returnalyze Interactive Mockups

Interactive design prototypes hosted via GitHub Pages for team feedback.

**Live URL**: https://jayl42.github.io/Mockups/

## Prototypes

| File | Description | Status |
|------|-------------|--------|
| [rd-tag-config-prototypes.html](https://jayl42.github.io/Mockups/rd-tag-config-prototypes.html) | Returns Drivers tag category configuration — 3 design options (Toggle+Drag, Click-to-Rank, Two Column) | Active |

## Workflow

1. Design prototype in Claude (JSX or HTML)
2. Save standalone HTML to this folder
3. Push to GitHub → auto-deploys to GitHub Pages
4. Share the Pages URL in Slack/Confluence

```bash
cd ~/Development/projects/Mockups
git add .
git commit -m "Add [prototype name]"
git push
```

Live within ~60 seconds at `https://jayl42.github.io/Mockups/[filename].html`
