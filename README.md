# OldCord

A Discord theme that tries to restore its 2023 UI

 By default, it removes profile effects (like banners) and clan tags. See `addons` below to get them back!

![Preview](https://raw.githubusercontent.com/milbits/oldcord/master/.github/preview.webp)

> [!IMPORTANT]
> - For the old grey colors, use the "Ash" theme in `Appearance` under settings
>   - Don't use vencord's "Client Theme" plugin, use Discord's own theme picker (with fakenitro if needed)
> - Enable "Sync Profile Themes" in `Settings > Accessibility` to fix broken profile colors
> - Disable "display name style" in `Settings > Accessibility`  if you don't want the flashy names
> - UI Density should be on default, i won't support the other 2 options (they still kinda work, though)
> - If you use BetterFolders, expect half your screen to turn blank every few months

## 3rd party

| Name                                                                                                                                  | Description                                                 |
| ------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------- |
| [Icon Revert](https://github.com/davart154/Icon-Revert-2023/blob/main/2023%20Icon%20Revert.theme.css)                                 | Reverts all icons to pre-2023. Can cause lag (see #37) |
| [Vencord's NoMosaic plugin](https://vencord.dev/plugins/NoMosaic)                                                                     | Restores the old image layout                               |
| [hide-nitro-upselling](https://github.com/D3SOX/complementary-discord-theme/blob/master/hide-nitro-upselling.betterdiscord.theme.css) | Hides nitro ads, could cause lag                            |

---

</details>

# Installation

## 😺[Vencord](https://github.com/Vendicated/Vencord)

#### Local method

1. Download [OldCord.theme.css](https://raw.githubusercontent.com/milbits/oldcord/main/OldCord.theme.css) (right-click > "Save As")
2. Move the file to the Vencord theme folder:

- `Settings > Themes > Open theme folder`

#### Online method

Paste the following in `Settings > Themes`:

- `https://milbits.github.io/oldcord/src/main.css`

## 🎛️ Other

1. Paste the following at **the top** of the CSS file/window:

```css
@import url("https://github.com/CalmFor/oldcord-patches/blob/main/src/main.css");
```


