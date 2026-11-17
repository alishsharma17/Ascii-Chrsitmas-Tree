# Ascii-Chrsitmas-Tree
This is the code for the ascii christmas tree from my recent tiktok: https://www.tiktok.com/@alishsharma/video/7708595506934467854
# ASCII Christmas Tree

A spinning 3D Christmas tree that runs right in your terminal. It has twinkling ornaments, a garland with chasing lights, a flickering star on top, and falling snow.

As seen on my TikTok: [@alishsharma](https://www.tiktok.com/@alishsharma/video/7708595506934467854)

## Requirements

- Python 3.7 or newer
- That's it. No packages to install.

It looks best in a big terminal window that supports 256 colors (Windows Terminal, iTerm2, or pretty much any Linux terminal).

## How to run it

1. Clone the repo or just download `tree3d.py`

   ```
   git clone https://github.com/YOUR_USERNAME/Ascii-Christmas-Tree.git
   cd Ascii-Christmas-Tree
   ```

2. Run it

   ```
   python tree3d.py
   ```

   On Mac or Linux you might need `python3` instead of `python`.

3. Press `Ctrl+C` to quit.

Tip: make your terminal full screen and zoom out a little (Ctrl and minus) for the best look.

## Customize it

All the settings are at the top of `tree3d.py`. A few fun ones to play with:

| Setting | What it does |
|---|---|
| `SPIN_SPEED` | How fast the tree spins |
| `NUM_ORNAMENTS` | How many ornaments are on the tree |
| `GARLAND_TURNS` | How many times the garland wraps around |
| `TIERS` | Number of branch layers |
| `MESSAGE` | The text at the bottom of the screen |
| `FPS` | Frame rate |

## Troubleshooting

**I see weird characters like `[38;5;46m` everywhere.**
Your terminal doesn't support ANSI colors. On Windows, use Windows Terminal instead of the old Command Prompt.

**The ornaments or star show up as boxes or question marks.**
Your terminal font is missing those symbols. Try a different font like Cascadia Code, Consolas, or any Nerd Font.

**The tree looks squished or cut off.**
Make the window bigger. The tree scales to fit whatever size your terminal is.

## License

Free to use, share, and remix. If you post something you made with it, tag me on TikTok, I'd love to see it.
