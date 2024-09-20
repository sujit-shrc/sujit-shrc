```bash
#!/usr/bin/env bash

# Last updated: 2024-09-20

➜ fastfetch

        ,
       /\         sujit@archlinux
      /  \        --------------------
     /\   \       OS: Arch Linux (btw) x86_64 🐧
    /      \      Shell: fish 3.7.1, with Alacritty + Starship 🚀
   /   ,,   \     WM: i3 (x11) 🪟
  /   |  |  -\    Editor: Neovim 📜
 /_-''    ''-_\   --------------------

➜ cat << EOF
# Hello, I'm Sujit Kumar

Full Stack Developer | CLI Enthusiast | Arch Fanatic 🎉

I craft efficient workflows and wield powerful tools. When I'm not battling bugs, you'll find me penning tech tales on [dev.to](https://dev.to/sujit-shrc) or fine-tuning my digital habitat.
> Arch is my digital canvas. Rust-based tools are my paintbrush. I break things, fix them, and call it art. 🎨

EOF

➜ echo -e "\n# What I'm Up To (still grinding XP)"
cat << EOF
- Developing full-stack applications with Next.js, TypeScript, Node.js, and FastAPI 💻
- Taming Linux systems and databases 🐳
- Building web crawlers and scrapers 🕷️
- Containerizing with Docker and setting up CI/CD pipelines 🔄
- Learning Rust (pending) ⚙️
EOF

➜ echo -e "\n# System Arsenal (a.k.a. \"Things I Can't Live Without\")"
declare -A spell_book
spell_book=(
    ["os"] = "Arch Linux          # Because it tries to keep things simple and minimalistic. Thinking about NixOS, though." 🐧
    ["wm"] = "i3                  # Tiling is life. Mouse? Never heard of her. I accidentally learned linear algebra trying to arrange windows." 📏
    ["editor"] = "Neovim          # Vim wasn't hardcore enough. Now I can exit Vim, but I don't want to." 🔧
    ["terminal"] = "Alacritty     # Because my terminal needs to render faster than my thoughts." ⚡
    ["multiplexer"] = "tmux       # It's like having multiple personalities, but for terminals." 🎭
    ["shell"] = "fish             # Because zsh was too mainstream, and bash didn't have enough colors." 🐠
    ["prompt"] = "Starship        # Because even the CLI deserves to look like a spaceship cockpit." 🌌
    ["file_manager"] = "yazi      # Rust-powered. Can navigate directories faster than I can say 'cd'. Life's too short for slow file operations." 🚀
)

for key in "${!spell_book[@]}"; do
    printf "%-12s: %s\n" "$key" "${spell_book[$key]}"
done

➜ echo -e "\n# Projects (They're Totally Stable, I Swear)"
sudo npm list -g --depth=0
├── pzr@1.1.1 -> /opt/pzr/bin/pzr  # CLI templates generator (Next.js, Express.js, Vite React) 📦
└── rnr@1.0.1 -> /opt/rnr/bin/rnr  # Intelligent script runner for JS/TS projects 🎬

cat /etc/pzr/README.md
pzr (pazer) CLI: Smart project template and component scaffolding tool.
Usage: pzr init && pzr create home about contact

cat /etc/rnr/README.md
rnr (runner) CLI: Because 'npm run dev' was too many keystrokes.
Usage: cd your-project && rnr

echo "Unnamed Neovim Theme (In Progress) - It's like staring into the void, but the void stares back with syntax highlighting. Your retinas will thank me later."

➜ echo -e "\n# Thoughts from /dev/brain"
cat << EOF
1. Debugged a production issue using only 'echo' statements. It was like performing surgery with a spoon. 🥄
2. I tried to explain Git to my cat. She just stared at me, then pushed everything off the table. 🐱
3. Wrote a script to automate my coffee-making while learning JS promises. My coffee maker now has an existential crisis. ☕
EOF

➜ echo -e "\n# Hack These to Connect (or Just Say Hi, That Works Too -- No Carrier Pigeons, Please):"
echo "Email   : $(echo 'c3VqaXQtc2hyY0BnbWFpbC5jb20=' | base64 -d)"
echo "GitLab  : $(echo 'uggcf://tvguno.pbz/fhwvg-fuep' | tr 'A-Za-z' 'N-ZA-Mn-za-m')"
echo "Discord : $(printf '873195413308588052' | xxd -r -p)"

➜ echo -e "\n# Shameless Plug"
echo "Found any of my repos useful? A star would fuel my energy! ⭐"
echo "I'm always up for interesting projects or just tech chat."

➜ # Exit with Flair
echo -e "\nLogging off. May your compile times be short and your bugs be shallow."
echo "Remember, there's no place like ~/home, unless you're in a Docker container."
exit 0
```
