# zsh_ascii
Ascii art system for terminal, including colors and custom art depending on whether its the first tab or a new tab.

## Setup
1. In your .zshrc file, add the line: source ~/.config/zsh_art/.art_select.
2. In the zsh_art directory, edit the file .art_select to choose the source of the actual ascii art.

## Creating Art
Use chafa (install with brew) to create ascii art:
```
chafa -f symbols --symbols ascii -c 256 --fg-only -s 28x beastling.png  > beastling.txt
```

### Chafa Flags
```
-s 60x sets width to 60
--symbols has options ascii, block, and braille
-c 256 is colored, -c none is not
-f symbols makes it ascii art and not an image
```
