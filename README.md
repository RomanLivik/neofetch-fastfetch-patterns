# Fastfetch and neofetch patterns
This is repo with styled banners for fastfetch and neofetch for every distros. You can copy all of them and add to your neofetch/fastfetch. File list updates regulary.
---
> On preview some text in configs can "swim off". It is a trouble with browser only. In CLI text readers they looks correctly
---
> You should rewrite some data in config files to look on your data in neofetch
---
> All configs you can use on every system. If you see config for MacOS you can use it for linux too
---

You can watch configs in [catalog](https://github.com/RomanLivik/neofetch-fastfetch-patterns/blob/main/CATALOG.md). There are some screnshots of every config

## Linux fonts for correct unicode-symbols
* noto-fonts
* ttf-dejavu
* ttf-unifont
* noto-fonts-emoji
* ttf-ancient-fonts
* nerd fonts

## MacOS fonts for correct unicode-symbols
* Noto (Google)
* EB Garamond
* Brill
* Nerd fonts (add as default)

## Installation (for neofetch)
* Open ~/.config/neofetch/config.conf with CLI text editor
```
vim ~/.config/neofetch/neofetch.conf
```
* Delete or comment some lines (like on screenshot)
<img width="1470" height="956" alt="image" src="https://github.com/user-attachments/assets/d3551f50-aa3a-48e0-a3f5-b37a13dd22fc" />
* Write your text or add a way for your .txt with it (to add like text - look on screenshot)
<img width="1171" height="765" alt="image" src="https://github.com/user-attachments/assets/7991ea66-dc7d-4ca4-ae31-d91904e8f7e0" />
* Or you can replace your config with one from this repo

## How to replace a config file
* Download config file from repo
* Rename your config file
```
cd .config/neofetch
mv config.conf config-backup.conf
```
* Replace downloaded config
```
cp /YOUR/WAY/TO/configX.conf ~/.config/neofetch
```
* Rename config
```
mv configX.conf config.conf
```

## Websites and specific symbols for your projects
* [Iconic unicode symbols](https://www.nerdfonts.com/cheat-sheet)
* [Big ASCII nickname](https://patorjk.com/software/taag/#p=display&f=ANSI+Shadow&t=&x=none&v=4&h=4&w=80&we=false)
* Unicode invisible symbol: "⠀" (use it to have no problems with text)
* [Nerd fonts download for mac](https://www.nerdfonts.com/font-downloads)

## If you want to help me your fork needed to have 
* Configuration file (N+1)
* Screenshot with neofetch/fastfetch (like my screenshots)
* URL near the screenshot in catalog
* Url must be on your config file in this repository
