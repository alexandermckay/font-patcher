# Font Patching with Font Forge

- Only use this option if you want to patch a custom font that is not available from [nerd fonts](https://github.com/ryanoasis/nerd-fonts)

## Steps

- `brew install fontforge`
- `git clone` this repo
- Copy the font file you would like to patch into the downloaded repo
- `cd <repo location>`
- `fontforge -script font-patcher <path to font>`
- Wait for the script to finish and then open the newly created font file with **Font Book** (right click -> open with -> Font Book)
- Click _Install Font_
- Restart **iTerm** or **Terminal** and select the newly created font in preferences

## Troubleshooting

- You need to have `python` installed and correctly linked
- This can be as simple as `brew install python` but if that is not working for you, try the steps outline [here](https://stackoverflow.com/questions/46179672/python-bash-usr-local-bin-python-no-such-file-or-directory)

## Windows

- If you are trying this on Windows, follow the installation instructions [here](http://designwithfontforge.com/en-US/Installing_Fontforge.html)
