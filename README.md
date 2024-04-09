# dotfiles
My personal dotfiles that I keep portable between Linux installs. I currently use Arch Linux on the Hyprland WM.

## Note
I would highly recommend `--recursive` as these dotfiles do have git submodules linking to different subprojects of mine (cafmenu, dickdir, engima). This also has a `--jobs` flags for cloning concurrently.
```bash
git clone --recursive --jobs 3 https://github.com/WarpWing/dotfiles.git
```
