# Spotify UI Clone

A pixel-focused recreation of the Spotify web player<img width="1328" height="601" alt="spotify" src="https://github.com/user-attachments/assets/6b2c778a-3aac-483f-a060-6e8ee7f233c7" />
 interface sidebar navigation, playlist cards, and a fixed bottom music player, built with plain HTML and CSS to practice matching a real, polished product design.

🔗 **[Live Demo:]**(https://awaishussainsoomro.github.io/spotify-ui-clone/)

📁 **Tech Stack:** HTML, CSS (Flexbox), Font Awesome icons


## Why I Built It

UI cloning is a different skill from building from a blank canvas, it forces you to match real spacing, alignment, and layout decisions instead of choosing your own. I picked Spotify specifically because of its layout complexity: a fixed sidebar, a scrollable main panel, and a persistent bottom player bar, all needing to behave correctly together.

## What It Does

Recreates the core Spotify web player layout: home/search navigation, a "Your Library" panel with playlist prompts, scrollable rows of playlist cards, and a fixed bottom player with playback controls and a volume slider.

## Key Features

- **Three-panel layout** — sidebar, scrollable main content, and fixed bottom player, all built with Flexbox
- **Responsive design** — sidebar stacks above content on tablets, and the player bar simplifies on mobile instead of breaking
- **Hover interactions** — nav items, cards, and player controls all have real hover states, not static images
- **Sticky navigation** — the top bar inside the main panel stays visible while scrolling, matching the real Spotify behavior

## Running Locally

No build step needed, it's plain HTML/CSS.

```bash
git clone https://github.com/awaishussainsoomro/spotify-ui-clone.git
cd spotify-ui-clone
```

Then just open `index.html` in your browser.

## What I'd Improve Next

- Make the sidebar collapsible on mobile instead of stacking, closer to the real app's behavior
- Add real audio playback wired to the progress bar
- Recreate the "Made For You" and genre-browsing sections for a more complete clone

---

Built by [Awais Hussain Soomro](https://github.com/awaishussainsoomro)
