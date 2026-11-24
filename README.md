# Superior Paint

A 2007-style desktop in the browser, built around a working Paint.

**Live:** https://andreysuperiorgit.github.io/paint/

- **Paint.** Pencil, brush, eraser, spray, fill, color picker, line, rectangle, rounded rectangle, ellipse, 28-color palette (right-click sets the background color). File → New / Save as PNG, Edit → Undo. Ctrl+Z, Ctrl+S, Ctrl+N.
- **The desktop around it.** Glass windows you can drag, minimize and maximize, a taskbar, a Start menu, a sidebar with a clock and gadgets, Flip 3D (the stacked-windows button next to Start, Tab to cycle), and a permission prompt before every app, like back then.
- **The other apps are my other builds**, opened live in their own windows: [V8 Engine](https://andreysuperiorgit.github.io/v8/), [Riemann, live](https://andreysuperiorgit.github.io/riemann/), [Afterglow](https://andreysuperiorgit.github.io/afterglow/) and NEONAMP.

Add `?demo` to the address to watch it run by itself. `?desktop` starts without opening Paint, `?noboot` skips the boot screen.

## How it was built

One HTML file, no libraries, no build step. Canvas 2D for Paint, CSS for the glass.
Written with Claude Code, which also ran the page in headless Chrome on desktop and phone sizes and checked it while it played.

## Run it locally

Open `index.html` in a browser.
