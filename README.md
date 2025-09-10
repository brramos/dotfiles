# How to use the dotfiles

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

