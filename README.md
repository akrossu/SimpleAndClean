<div align="center">
<h1>SimpleAndClean</h1>

![Release](https://img.shields.io/github/release/akrossu/SimpleAndClean?logo=github&include_prereleases=&sort=semver&color=62b061&style=flat-square) [![Discord](https://img.shields.io/discord/344266404993826817?logo=discord&logoColor=white&label=discord&color=7289DA&style=flat-square)](https://discord.gg/ANgfZVa)

</div>

## Overview

**SimpleAndClean** aims to deliver as clean of a UI as possible without nipping functionality. It ensures seamless integration and customizability for both casual users and developers alike.

Please note this is an active project—if you encounter issues or visual inconsistencies, open an issue so I can fix it promptly. Thank you for supporting the theme! :3

---

## Features

- **No branding or titlebar**  
  Keep things clean. Use native Windows shortcuts like `Win + ↑` or `Win + ↓` to manage window sizing.
> [!TIP]
> With the title bar removed, you may want to install [AltSnap](https://github.com/RafaelBergson/AltSnap) – a lightweight utility that lets you drag/resize windows by holding `Alt` and clicking anywhere in the window.

- **Full Vencord compatibility**  
  Built and tested with Vencord to ensure consistent experience.

- **Custom background and icons**  
  Personalize your setup with aesthetic visuals that still feel native to Discord.
  
- **Pre Visual Refresh styling**  
  Restores some of the older styling decisions like circlular guild icons.
  
- **Extensive color palette**  
  A wide range of colors to match your style and mood.

- **Accessibility first design**  
  Prioritizes accessible features so they will always work.

- **Developer-friendly comments**  
  Every element is clearly labeled in the source, making it easy to tweak and extend.

## Previews

![Banner](https://github.com/akrossu/SimpleAndClean/blob/main/src/resources/preview1.png?raw=true)

![subBanner](https://github.com/akrossu/SimpleAndClean/blob/main/src/resources/preview2.png?raw=true)

## Installation

### ![Vencord](https://camo.githubusercontent.com/a8c728c8a3c92c7ac59e8c811da0e9a00513661c22f6fa4419ed4fbad662cc30/68747470733a2f2f646973636f72642d657874656e73696f6e732e6769746875622e696f2f6173736574732f69636f6e732f76656e636f72642e676966) [Vencord](https://vencord.dev/)

#### QuickCSS

> If you're just interested in changing things like the backgrounds, you can simply install themes by importing them using QuickCSS

1. Navigate to `Settings` > `Vencord` > `Themes` > `Local Themes`

2. Select `Edit QuickCSS`

3. Copy and Paste `@import url(https://akross.dev/SimpleAndClean/SimpleAndClean.theme.css);` at the top of the file.

4. You may edit custom properties found in the [theme file](https://akross.dev/SimpleAndClean/SimpleAndClean.theme.css) by placing them within a `:root` selector for example:

```css
:root {
    --app-bg-url: url('https://4kwallpapers.com/images/walls/thumbs_3t/5669.jpg');
}
```

#### Local

1. Head over to the [Latest Release](https://github.com/akrossu/SimpleAndClean/releases) and download `SimpleAndClean.theme.css`

2. Navigate to the Vencord Themes folder:
    - `Settings` > `Vencord` > `Themes` > `Local Themes` > `Open Themes Folder`

3. Place `SimpleAndClean.theme.css` in the folder

4. Make sure to click `Load Missing Themes` to load your new theme!

<br/>


### ![BetterDiscord](https://camo.githubusercontent.com/7d1f99fb97e9ddfc29029b00bed5b0e72f659aa321a8745c60c382e26ee67c35/68747470733a2f2f646973636f72642d657874656e73696f6e732e6769746875622e696f2f6173736574732f69636f6e732f626574746572646973636f72642e706e67) [BetterDiscord](https://betterdiscord.app/)

> [!IMPORTANT]
> BetterDiscord is not entirely supported as of right now, but I will be slowly adding specific platform support as soon as core features work.

#### Local

1. Download the latest release of the theme:
    - From the [BetterDiscord Website](https://betterdiscord.app/theme/)
    - [Latest Release](https://github.com/akrossu/SimpleAndClean/releases) and download `SimpleAndClean.theme.css`

2. Navigate to the BetterDiscord Themes folder:
    - `Settings` > `BetterDiscord` > `Themes` > `Open Themes Folder`

3. Place `SimpleAndClean.theme.css` in the folder

## Related Themes

> Note: My previous theme fork, [ModifiedRoundedDark](https://github.com/akrossu/ModifiedRoundedDark), is no longer in active development. Future updates will focus on SimpleAndClean.

[![SimpleAndClean](https://github-readme-stats.vercel.app/api/pin/?username=akrossu&repo=SimpleAndClean&bg_color=1B1D23&title_color=FFFFFF&text_color=AAAAAA&icon_color=D68881&hide_border=true)](https://github.com/akrossu/SimpleAndClean) [![ModifiedRoundedDark](https://github-readme-stats.vercel.app/api/pin/?username=akrossu&repo=modifiedroundeddark&bg_color=1B1D23&title_color=FFFFFF&text_color=AAAAAA&icon_color=D68881&hide_border=true)](https://github.com/akrossu/ModifiedRoundedDark)

## Feedback & Community

If you enjoy the theme or run into bugs, feel free to open an issue or join the [support Discord server](https://discord.gg/ANgfZVa). Suggestions and contributions are always welcome!

---

Thank you for using SimpleAndClean 💚
