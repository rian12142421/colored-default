# Iris
A cozy [Spicetify](https://spicetify.app/) theme for Spotify, and for those who love simplicity, the default scheme keeps things clean and close to the original look.

<img width="1920" height="1080" alt="iris-readme" src="https://github.com/user-attachments/assets/900a4eaf-2a0f-4b14-b479-aaec02a2a54f" />

<img width="1920" height="1080" alt="iris-preview" src="https://github.com/user-attachments/assets/4364576b-3d24-46ad-8b21-2a62d3bdac42" />

## Color schemes

| Type | Schemes |
| ---- | ------- |
| Dark | Default, Mint, Coffee, Crimson, Dracula, Everforest, Malachite, Midnight, Monochrome, Nord, Plum, Vaporwave |
| Light | Cherry, Matcha, Peach, Retro, Lilac |

## Requirements

- [Spicetify CLI](https://spicetify.app/docs/getting-started) installed and working
- Spotify desktop app

## Installation

### Option 1: Marketplace

1. Install [Spicetify Marketplace](https://github.com/spicetify/marketplace) if you haven't already.
2. Open Spotify and go to **Marketplace**, then the **Themes** tab.
3. Search for **Iris** and click **Install**.
4. Pick a color scheme from the theme's card, then restart Spotify if the colors don't update.

### Option 2: Manual

1. Download or clone this repository.
2. Find your Spicetify config folder:

   ```
   spicetify path userdata
   ```

3. Create an `Iris` folder inside its `Themes` folder, and copy `color.ini` and `user.css` from this repository's `theme` folder into it:

   ```
   Themes/Iris/color.ini
   Themes/Iris/user.css
   ```

4. Apply the theme:

   ```
   spicetify config current_theme Iris color_scheme Default
   spicetify apply
   ```

## Switching color schemes

Replace `Default` with any scheme name from the table above, then apply again:

```
spicetify config color_scheme Mint
spicetify apply
```

## Troubleshooting

- **Nothing changed:** run `spicetify apply` again, then restart Spotify.
- **Colors look wrong after a Spotify update:** run `spicetify restore backup apply`.

## Credits

Some schemes are based on popular palettes: [Dracula](https://draculatheme.com), [Nord](https://www.nordtheme.com), and [Everforest](https://github.com/sainnhe/everforest).
