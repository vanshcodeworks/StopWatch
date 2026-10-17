# StopWatch

Browser stopwatch: plain HTML, CSS and JavaScript, no dependencies.

## Running

Open `index.html` directly, or serve the folder:

```bash
npx serve .
```

## Files

```
index.html   markup
style.css    styling
script.js    timing logic
logo.png     icon
```

## Notes

No build step and no framework. Timing uses `Date.now()` deltas rather than
accumulated intervals, which avoids drift over long runs.