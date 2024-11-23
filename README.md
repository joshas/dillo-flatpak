# Dillo browser Flatpak

Dillo is a multi-platform graphical web browser, known for its speed and small footprint, that is developed with a focus on personal security and privacy. It is built with the FLTK 1.3 GUI toolkit.
This repository allows installing Dillo browser through [Flatpak](https://flatpak.org).

## Installation

```
flatpak install flathub io.github.dillo_browser.dillo
```

## Running
Launch Dillo browser from your desktop menu, or via command line:
```
flatpak run io.github.dillo_browser.dillo
```

## Building

```
flatpak-builder --user --install build-dir io.github.dillo_browser.yml --force-clean
```
