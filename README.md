# Gold Zone Express - Demo Website

A modern, responsive landing page for Gold Zone Express - showcasing premium express services.

## Features

- 🎨 Modern, elegant design with gold and dark blue color scheme
- 📱 Fully responsive layout that works on all devices
- ⚡ Pure HTML and CSS - no dependencies required
- 🔗 Smooth navigation with anchor links

## Quick Start

To view the demo, simply open `index.html` in any modern web browser:

```bash
# Open directly in your default browser
open index.html

# Or use a local server (optional)
python -m http.server 8000
# Then visit http://localhost:8000
```

## Project Structure

```
├── index.html    # Main demo page
└── README.md     # This file
```

## Customization

The website uses inline CSS for simplicity. Key colors used:
- **Primary Gold**: `#d4af37`
- **Dark Background**: `#1a1a2e`
- **Secondary Dark**: `#16213e`

## License

© 2025 Gold Zone Express. All rights reserved.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Gold Zone Express – 1933 Gold Confiscation</title>
  <link rel="stylesheet" href="assets/styles.css">
</head>
<body>
  <header>
    <h1>Gold Zone Express</h1>
    <h2>The 1933 Gold Confiscation Slot Machine</h2>
  </header>

  <main>
    <section class="theme-intro">
      <img src="assets/images/gold-bars.png" alt="Gold Bars" class="main-image">
      <p>
        Step into the world of 1933, when the Federal Reserve and Treasury agents swept the nation, confiscating gold from the people. Spin the reels, dodge the agents, and unlock Treasury bonuses in this animated slot machine experience!
      </p>
    </section>

    <nav>
      <a href="slot.html" class="play-btn">Play Now</a>
      <a href="pages/rules.html">Game Rules</a>
      <a href="pages/terms.html">Terms of Service</a>
      <a href="pages/privacy.html">Privacy Policy</a>
    </nav>
  </main>

  <footer>
    <p>&copy; 2025 Gold Zone Express. All rights reserved.</p>
  </footer>
</body>
</html>
