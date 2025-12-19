# Random HTML apps

Single-file HTML applications hosted at random.yprez.com. Each app is self-contained with no external dependencies.

## Apps

| File | Description |
|------|-------------|
| `minesweeper.html` | Classic minesweeper game |
| `meditation-timer.html` | Meditation timer with session tracking |
| `hydration-tracker.html` | Daily water intake tracker |

## General guidelines

- When suggesting changes to a file, prefer breaking them into smaller chunks
- Never tell the user "you're absolutely right" or similar affirmations
- Maintain single-file architecture - do not split into multiple files
- Act autonomously on reversible changes; ask before breaking localStorage schema

## Constraints

- Vanilla HTML, CSS, and JavaScript only - no external frameworks or CDN dependencies
- All data stored locally (localStorage) - no remote services or analytics
- Each app must work offline after initial load
- Preserve existing localStorage key naming for backwards compatibility

## Development

```bash
# Open any file directly in browser
open minesweeper.html

# Or use a local server
python -m http.server 8000
```

No build step. No tests. Manual browser testing only.

## Git standards

- Commit messages should be concise and descriptive
- Never add AI attribution or co-authorship markers to commits
