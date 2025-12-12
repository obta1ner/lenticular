# Lenticular

A digital recreation of those nostalgic lenticular stickers that change as you tilt them.

## Live Demo

**[Try it here](https://obta1ner.github.io/lenticular)**

## Local Development

```bash
# Clone the repo
git clone https://github.com/yourusername/lenticular.git

# Open in browser
cd lenticular
open index.html
```

No build process needed - it's just vanilla HTML, CSS, and JavaScript!

## Project Structure

```
lenticular/
├── index.html          # Main application
├── images/             # Default lenticular images
│   ├── 1.png
│   ├── 2.png
│   └── 3.png
├── README.md
└── LICENSE
```

## How It Works

The lenticular effect is created using a barrier grid technique:
- 3 images are sliced into thin vertical strips
- Strips are interleaved together
- A black barrier grid is overlaid on top
- As you tilt/move, the barrier reveals different strips, creating the illusion of animation

## Credits

- **Made by:** [@obtainer](https://x.com/obtainer)
- **Inspired by:** [@kitasenjudesign](https://x.com/kitasenjudesign/status/1625453194544578562)

## License

MIT License - feel free to use this for your own projects!

