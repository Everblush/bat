# Everblush Bat
Everblush colors brought into bat, which is based on the syntax of [sublime-snazzy](https://github.com/greggb/sublime-snazzy)

![](https://github.com/mehedirm6244/bat/blob/main/screenshot.png)

## How to install?
```
mkdir -p "$(bat --config-dir)/themes"
cd "$(bat --config-dir)/themes"
git clone https://github.com/mehedirm6244/bat
bat cache --build
```
Check if the theme is installed successfully by looking at the output of `bat --list-themes`

To apply this theme, add the following line to the config file of bat:
`--theme="Everblush"
