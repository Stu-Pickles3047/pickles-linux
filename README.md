# 🐧 Pickles Linux Repository

Welcome to the Pickles Linux Repository! This is a personal repository for testing and distributing packages for Arch Linux and compatible distributions.

**Note:** This is not an official repository, just a personal one for testing packages.

## How to Add This Repository

To add this repository to your Arch Linux system, add the following to your `/etc/pacman.conf`:

```
[pickles-linux]
SigLevel = Optional TrustAll
Server = https://stu-pickles3047.github.io/pickles-linux/
```

Then update your package list:

```bash
pacman -Sy
```

Install packages with:

```bash
pacman -S package-name
```

## Available Packages

- [**Pickles-Update**](https://github.com/Stu-Pickles3047/pickles-update) - A tool for updating packages from this repository.
- [**Pickles-Weather**](https://github.com/Stu-Pickles3047/Pickles-Weather) - A weather display widget for Conky.
- **Pickles-Man-Viewer** - A graphical man page viewer. (Page under construction, but PreRelease package available)

## License

This work is dedicated to the public domain under the [Unlicense](https://unlicense.org/).

## Links

- [GitHub Profile](https://github.com/Stu-Pickles3047)
- [Repository Website](https://stu-pickles3047.github.io/pickles-linux/)
