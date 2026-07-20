# homebrew-tap

Homebrew packages for software by [Joaquim Rocha](https://github.com/joaquimrocha).

## thel

The terminal app built for AI coding agents and other long-running sessions
([repo](https://github.com/joaquimrocha/thel)).

```sh
brew install --cask joaquimrocha/tap/thel
```

Linux only for now (macOS coming soon). Installs the prebuilt binary, an app
menu entry, and the icon from the GitHub release. Needs the system WebKitGTK
and GTK 3 libraries:

- Debian/Ubuntu: `sudo apt install libwebkit2gtk-4.1-0 libgtk-3-0`
- Fedora: `sudo dnf install webkit2gtk4.1 gtk3`
