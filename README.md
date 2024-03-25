# Monaspace fonts patched for Powerline

The Github's monaspace fonts are patched with [font-patcher](https://github.com/ryanoasis/nerd-fonts?tab=readme-ov-file#font-patcher) .

To use font-patch in windows to path your own fonts, follow the steps below

1. Install fontforge
2. FontForge comes with ffpython, use the ffpython with font-patch script like below
   ```
   ffpython.exe .\font-patcher [--powerline] [-c] -out <output dir> <font that you want to patch>
   ```
