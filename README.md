# Bubble Todo

A playful, single-page to-do app where tasks float as colorful bubbles on a dark glassmorphic canvas. No build tools, no frameworks, no backend — just open `index.html` in a browser, or click [here](https://summerzhao618.github.io/BubbleTodo/).

![HTML](https://img.shields.io/badge/Pure-HTML%2FCSS%2FJS-blue)

## How It Works

1. **Add tasks** — Type one or more tasks (one per line) in the input area, then click **Add Bubbles** or press `Ctrl+Enter`. Each task spawns as a floating, gently wobbling bubble.
2. **Complete a task** — Press and hold a bubble for 2 seconds. A progress ring fills up, the bubble shakes, then pops with a particle burst. The task moves to the **Completed** list in the top-right corner.
3. **Delete a task** — Right-click any bubble to instantly remove it without recording it as completed.
4. **Drag to rearrange** — Click and drag bubbles anywhere on the canvas.
5. **Download your list** — Once you've completed tasks, click the **Download List** button to save a `.md` file of everything you finished that day.

## Persistence

- Your board (active bubbles, positions, completed list) is **auto-saved to `localStorage`** after every action.
- Closing the browser or refreshing the page restores your board exactly as you left it.
- **Each new day starts fresh** — saved data from a previous day is automatically cleared on first load.

## Getting Started

```
git clone <repo-url>
cd BubbleTodo
```

Then open `index.html` in any modern browser. That's it.

## Features

| Feature | Details |
|---|---|
| Zero dependencies | Single HTML file, no npm/build step |
| Auto-save | localStorage keeps your board across refreshes and browser restarts |
| Daily reset | Board clears automatically at the start of a new day |
| Drag & drop | Reposition bubbles freely on the canvas |
| Long-press to complete | 2-second hold with animated progress ring |
| Right-click to delete | Remove a task silently (no completed record) |
| Particle effects | Satisfying pop animation on completion |
| Congrats toasts | Random motivational message on each completion |
| Download list | Export completed tasks as a text file |
| Responsive | Bubbles stay within visible bounds and avoid overlap |

## Browser Support

Works in all modern browsers (Chrome, Firefox, Edge, Safari). Requires JavaScript enabled and `localStorage` available.

## License

MIT
