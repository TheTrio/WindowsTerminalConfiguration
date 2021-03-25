# Final Result

![Screenshot of my Windows Terminal](WindowTerminal.png)

## How to make your terminal look like this

1. Install Powerline for bash. Detailed article [here](https://earlybyte.medium.com/powerline-for-bash-6d3dd004f6fc). You might run into an issue regarding incorrect paths. A solution is given [here](https://stackoverflow.com/questions/52338593/powerline-no-such-file-or-directory-scripts-powerline-config)
2. Install [colorls](https://github.com/athityakumar/colorls). Detailed instructions can be found on their GitHub page.
3. Install any Nerd font which supports the Glyphs and Ligatures used by colorls. I used the [Hack](https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/Hack) font. If you want to check out other fonts, see [this](https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts)
4. Copy my settings to your `settings.json`. To open your settings file, press `Ctrl+,` after opening WindowsTerminal. Note: If you used a different font than mine, remember to change the `fontFace` property in your `settings.json` 
5. That's it! Just restart your terminal or do `source ~/.bashrc` and you should be good to go!

## Optional 

1. Install neofetch to get your system information in a cool looking way. To install, type `sudo apt install neofetch` in your terminal. I also like having an alias for `neofetch` as `nf`. For that, just add the line `alias nf="neofetch"` to your `.bash_aliases` under `/home/yourUsername`
2. `neofetch` also allows you to have custom ascii art. While you can make your own ASCII art from scratch, you can also download them from [ASCII Art Archive](https://www.asciiart.eu/). From here, find the ASCII art you like the most. Save that in a file, and let `neofetch` know to use it by typing `neofetch --source pathToFile`. To make this the default behavior for neofetch, just edit the value of the alias `nf`. 

Install Windows Terminal from the [Microsoft Store](https://www.microsoft.com/en-us/p/windows-terminal/9n0dx20hk701). 

You can also view the project on GitHub [here](https://github.com/Microsoft/Terminal) 
