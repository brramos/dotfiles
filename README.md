# How to use the dotfiles

## Setup
1. Create `.config` folder
2. Install stow from homebrew
3. From dotfiles folder, un-stow config for app, e.g. `stow aerospace`
4. Confirm configuration is created inside `.config` folder

## Learn to stow
1. Create folder for the app that needs a config
2. Inside folder, create the same folder structure the app needs
  - If app's configs are in .config
    - create folder path <app>/.config
    - and move configs to this folder
3. Then from root of dotfiles folder execute stow <app>
4. Verify that configs have been symlinked back to original locations
5. Test app
6. Commit and push
7. Done

