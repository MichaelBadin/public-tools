# MacOS: Create Dock Spacers

```Bash
# Left side (normal)
defaults write com.apple.dock persistent-apps -array-add '{tile-data={}; tile-type="spacer-tile";}'

# Left side (small)
defaults write com.apple.dock persistent-apps -array-add '{tile-data={}; tile-type="small-spacer-tile";}'

# Right Side (normal)
defaults write com.apple.dock persistent-others -array-add '{tile-data={}; tile-type="spacer-tile";}'

# Right side (small)
defaults write com.apple.dock persistent-others -array-add '{tile-data={}; tile-type="small-spacer-tile";}'

# Reset the dock
sudo killall Dock
```
