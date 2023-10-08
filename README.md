<h1 align="center">surCord</h1>
<p align="center">Hello. Again. </p>

# ![screenshot](https://raw.githubusercontent.com/SlippingGittys-Discord-Themes/surCord/main/assets/Untitledpreview.png)

## How to use

### Discord App

* BetterDiscord, Vencord, and Openasar users can grab the [surCord.theme.css](hhttps://raw.githubusercontent.com/SlippingGittys-Discord-Themes/surCord/main/surCord.theme.css) file and either
  * Place the file in the BetterDiscord or Vencord themes folder
  * Copy the text in the file, and paste it in Openasar's quick CSS text field

### Browser 
 * [![](https://img.shields.io/badge/install%20with-stylus-006666?style=flat-square)](https://github.com/SlippingGittys-Discord-Themes/surCord/raw/main/surCord.user.css)
 
## Translucenty (Addon offically maintained on macOS only)

<details>
<summary>Information on enabling translucency</summary>

### Check out [this issue](https://github.com/SlippingGittys-Discord-Themes/surCord/issues/42) if you use Windows. [Mica for Everyone](https://github.com/MicaForEveryone/MicaForEveryone) is known to play decently, but be very spotty.

Albeit not out of the box, (and very much intentionally so), this theme supports translucency in some areas. 

![image](https://user-images.githubusercontent.com/76500838/231657975-018e1649-0cb0-4d3f-ad74-5698e305dc76.png)

### You can achieve the same look on Vencord/macOS by doing as follows:

* Go to Settings > Vencord, then toggle "Enable Translucent Window".

![image](https://user-images.githubusercontent.com/76500838/231659229-4f261d16-304e-4904-b9f5-88478ab2fe89.png)

* Assuming that the entire surCord.theme.css contents are in QuickCSS:
   * Paste `@import url('https://slippinggittys-discord-Themes.github.io/surCord/src/fixations/additions/translucency.css');` underneath the source @import, as demonstrated so bellow
   
![image](https://user-images.githubusercontent.com/76500838/231659909-ba832307-aca5-48a2-a800-9927a0f6a132.png)

### Extra info
 * You can adjust the oppacity and colors by pasting & messing with these varriables 
   
 ```css
 
.theme-dark {
  --background-tertiary: #2f31364b;
}

.theme-light {
  --background-tertiary: #ffffff1d;
}

```
   
   ##### Also see [Acorn, an Accord inspired theme based on surCord made specifically for Vencord + macOS](https://github.com/SlippingGitty/Acorn) 
</details>
 
## Extra info
<details>
<summary>Information about accents, themes, emoji, fonts, and more!</summary>

* You can very easily [change the accent and theme color](https://cdn.discordapp.com/attachments/816373850647953439/984177819204603924/unknown.png) for surCord by navigating to `/src/_theming.scss` and [uncommenting **>>>one<<<**](https://github.com/SlippingGittys-Discord-Themes/surCord/blob/main/src/_theming.scss) of the accent colors and one of the background colors.  
  
  BD and Stylus can uncomment these in surCord.theme.css / surCord.user.css

* You can set surCord to use Apple's Emoji font 

  * Navigate to `/src/_modules.scss` and uncomment `@import url(https://mwittrien.github.io/BetterDiscordAddons/Themes/EmojiReplace/base/Apple.css);`

* You can uncomment `font-weight: bold !important;` in your respective font sections  
to use **San Fransisco Display Bold**. *(Or specify your own weight, 100-900; bold = 700)*  
  
  - **BD:** surCord.theme.css 
  - **Replugged/Powercord:** `/src/_font.scss` 
  - **Stylus:** surCord.user.css

* Stylus users on Firefox have to be on version 102 or later and toggle "Patch CSP to allow style assets"  
  Chromium browsers shall be fine by default on any recent version.
  
  ![stylus setting](/assets/stylussettingneeded.png)
</details>


## Devs, Contributors, and other Creditors 

See [here.](https://github.com/SlippingGittys-Discord-Themes/surCord/graphs/contributors)

#### Support Server : https://discord.gg/7FQQTf8gGj
