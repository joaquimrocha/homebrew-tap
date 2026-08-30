# homebrew-tap

Homebrew packages for software by [Joaquim Rocha](https://github.com/joaquimrocha).

## thel

The terminal app built for AI coding agents and other long-running sessions
([repo](https://github.com/joaquimrocha/thel)).

```sh
brew install --cask joaquimrocha/tap/thel
```

### macOS (Apple silicon)

Installs `thel.app` into `/Applications` from the release `.dmg`. The app isn't
signed with an Apple Developer ID, so macOS Gatekeeper quarantines it. Clear the
quarantine flag once after installing:

```sh
xattr -dr com.apple.quarantine /Applications/thel.app
```

Or right-click `thel.app` in Finder, choose **Open**, and confirm — you only
need to do this the first time. (`brew` also prints this reminder on install.)

### Linux

Installs the prebuilt binary (x86_64 or aarch64), an app menu entry, and the
icon from the GitHub release. Needs the system WebKitGTK and GTK 3 libraries:

- Debian/Ubuntu: `sudo apt install libwebkit2gtk-4.1-0 libgtk-3-0`
- Fedora: `sudo dnf install webkit2gtk4.1 gtk3`
