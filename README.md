# Homebrew Tap for fit

This is a custom Homebrew tap for [fit](https://github.com/FortranGoingOnForty/fit), a terminal-based merge conflict resolver with a three-pane TUI interface.

## Installation

```bash
# Add the tap
brew tap FortranGoingOnForty/fit

# Install fit
brew install fit
```

## Usage

```bash
# Resolve merge conflicts in a file
fit myfile.txt
```

## What is fit?

fit is a terminal-based merge conflict resolver written in Modern Fortran that provides:

- **Three-Pane Layout**: Visual side-by-side comparison with incoming, local, and preview panes
- **Color-Coded Diffs**: Green `+` for incoming additions, red `-` for local changes
- **Sequential Navigation**: Navigate through multiple conflicts with keyboard shortcuts
- **Interactive Resolution**: Choose incoming, local, or both changes for each conflict

### Keyboard Controls

| Key | Action |
|-----|--------|
| `i` | Select **incoming** changes |
| `l` | Select **local** changes |
| `b` | Select **both** changes |
| `n` / `→` / `↓` | Navigate to **next** conflict |
| `p` / `←` / `↑` | Navigate to **previous** conflict |
| `s` | **Save** resolved file and quit |
| `q` / `ESC` | **Quit** without saving |

## Links

- [GitHub Repository](https://github.com/FortranGoingOnForty/fit)
- [Report Issues](https://github.com/FortranGoingOnForty/fit/issues)

## License

MIT
