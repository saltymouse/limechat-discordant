# Discordant

A Discord inspired theme for [LimeChat](https://github.com/psychs/limechat).

![Preview screenshot of the Discordant theme for LimeChat](./discordant-screenshot.png)

## Features

- ð¡ Text is set in [Nunito](https://fonts.google.com/specimen/Nunito) font, similar to Discord's [Uni Sans](https://www.fontfabric.com/fonts/uni-sans/).
- ð¦ Unique\* [Openmoji](https://openmoji.org) avatar for each user's nickname.
- ð Uniqueâ¡ colour for each user's nickname.

<sub>\* Based on the first (2) characters of the user's nickname. Users that happen to have the same starting character sequences (beyond 2 characters) will use the same emoji avatar.</sub>  
<sub>â¡ Colours are randomly chosen; the same (or similar) colour may be assigned more than once.</sub>

## Basic Install

1. Download this project as a zip (from the "Code" menu above or [click here](https://github.com/saltymouse/limechat-discordant/archive/refs/heads/master.zip)).
2. Open LimeChat's theme folder.
   - LimeChat Preferences â Theme â Open in Finder
3. Unzip the project zip archive, then drag-and-drop everything inside the `dist` folder to inside LimeChat's `Themes` revealed earlier.
4. Close, then re-open LimeChat's preferences and select the "discordant" theme from the "Current theme" drop-down menu.

You should end up with a `Themes` folder similar to this:

```
âââ Sample.css
âââ Sample.yaml
âââ discordant-assets        # discordant theme folder
âÂ Â  âââ fonts
âÂ Â  âââ icons
âââ discordant.css           # discordant theme file
âââ discordant.yaml          # discordant theme file
âââ hipchat-facebook.css
âââ hipchat-facebook.yaml
```

## Developer Install

1. Open your LimeChat `Themes` in your Terminal
2. `npm install` to install dependencies
3. `npm run dev` for local dev (browser preview)
4. `npm run deploy` build and copy files to the `Themes` folder to test in LimeChat

### Developer Notes

> How it works...

#### Todo

- [ ] Light/Dark mode
- [ ] Oraganise SASS code
  - [ ] Colour theme variables
- [ ] Update `yaml` colours to be more Discordy
- [ ] Setup `<iframe>` in dev-HTML to emulate LimeChat layout
- [ ] Add JS functionality
- [x] Tune the list of comboChars based on combination frequency
