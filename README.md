<h1 align="center">🚀 C4RL</h1>
<div align="center">A free and open-source Roblox script hub</div>
<br>
<div align="center">
	<a href="https://github.com/c4rl/hub/actions"><img src="https://github.com/c4rl/hub/actions/workflows/eslint.yaml/badge.svg" alt="ESLint Status" /></a>
	<a href="https://github.com/c4rl/hub/releases/latest"><img src="https://img.shields.io/github/v/release/c4rl/hub?include_prereleases" alt="Latest Release" /></a>
</div>
<div>&nbsp;</div>

## 🚀 Introduction

**C4RL** is a **general-purpose** Roblox script hub designed to make convenient tasks **easy** and **satisfying**.

Use many different **action cards** on the [**Home**](https://github.com/c4rl/hub#house-home) and [**Apps**](https://github.com/c4rl/hub#iphone-apps) page, or check out what we have featured on the [**Scripts**](https://github.com/c4rl/hub#newspaper-scripts) page.

Press `K` to open or close C4RL. For the best experience, a 1080p monitor or above is recommended!

&nbsp;

## 🚀 Quick start

When run with auto-execution, C4RL will start minimized by default.

### 📌 Latest release

Runs the latest release build of C4RL.

```lua
loadstring(
  game:HttpGetAsync("https://raw.githubusercontent.com/c4rl/hub/master/public/latest.lua")
)()
```

### 🚧 Nightly snapshot

Runs a snapshot of new updates we have not published yet. You will get new features earlier, but they may be unstable.

```lua
loadstring(
  game:HttpGetAsync("https://raw.githubusercontent.com/c4rl/hub/master/public/snapshot.lua")
)()
```

&nbsp;

## 📚 Navigation

### 🏠 Home

The **Home** page has a handful of intuitive information and action cards.

- 😊 **Profile** - You, and some actions that modify your character.

  - 🔘 **Sliders** - Flight, walk speed, and jump height
  - 🔘 **Buttons** - Refresh, ghost, godmode, or freecam

- 🖥️ **Server** - Your server, and options to rejoin or server hop. Tap again to cancel.

- 🎮 **Friend Activity** - A list of games your friends are playing.

### 📱 Apps

The **Apps** page acts as a hub for general and miscellaneous features.

- 🤗 **Players** - A selection of players and some actions you can perform on them.

  - 🔘 **Goto** - Moves your character to theirs. Tap again to cancel.
  - 🔘 **Hide** - Hides their character locally until disabled. Persists between players.
  - 🔘 **Kill** - Uses a tool with a handle to "bind" to their character and teleport to the void.
  - 🔘 **Spectate** - Toggles a third-person view of their character. Disables when they respawn or the subject changes.

### 📰 Scripts

The **Scripts** page is a small collection of community-favorites you should try.

- 📚 **Solaris** - https://solarishub.dev
- 📚 **V.G Hub** - https://github.com/1201for
- 📚 **EvoV2** - https://projectevo.xyz
- 🛡️ **CMD-X** - https://github.com/CMD-X
- 🛡️ **Infinite Yield** - https://github.com/EdgeIY
- 🔍 **Dex Explorer** - https://github.com/LorekeeperZinnia
- 🔍 **Unnamed ESP** - https://github.com/ic3w0lf22

### ⚙️ Options

The **Options** page lets you configure theming and UI performance.

 - [x] Set theme
 - [ ] Toggle acrylic effect
 - [ ] Keybinds
 - [ ] Save settings

&nbsp;

## 💖 Support

- ✅ ScriptWare
- ✅ Synapse X
- ✅ Krnl
- ✅ Wave
- ✅ Fluxus

&nbsp;

## 🛠️ Development

### Building

To build C4RL from source:

```bash
# Install dependencies
npm install

# Build the project
npm run build

# Bundle for distribution
npm run bundle
```

### Project Structure

- `src/` - TypeScript source code
- `ci/` - Build and CI scripts
- `public/` - Generated Lua files
- `components/` - Reusable UI components
- `views/` - Page components
- `store/` - State management
- `hooks/` - Custom React hooks
- `jobs/` - Background tasks and utilities

&nbsp;

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

&nbsp;

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

&nbsp;

## ⭐ Credits

Originally based on Orca by 0866, now rebranded and enhanced as C4RL.

Thanks to all the contributors and the Roblox scripting community!
