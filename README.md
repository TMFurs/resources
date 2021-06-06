# Trackmania Furs

This is a repository for *Trackmania Furs* community dedicated to furry fandom who enjoys **Trackmania** videogame series.

> Club for fellow members of furry community, now in *Trackmania*!

## Website

You can access our main website at [furs.trackmania.xyz](https://furs.trackmania.xyz/).

## Guidelines

### Basics

- White color is mostly *Gray 2.5%* using *InkScape Default* palette. But *4x1* decal logo is mixed with *Gray 2.5%* (*Trackmania* part) and *Pure White* (*Furs* part) colors.
- Activities which can be public (later — *public activities*) without entering *Club* (e.g. *Campaigns*, *Skins*, etc.) must be used with *4x1* decal on top of the main text. Simple activities (later — private activities) which are only available in the club (*News*, *Maps*, *Rankings*, etc.) can be made without *4x1* decal.
- Public activities can be stretched vertically, but not horizontally, text and logo is centered. Use *Items* activity as margins reference.
Private activities can be stretched horizontally, but not vertically. Use *About* activity as margins reference, text is slightly at the top.
- Special activities such as *Discord* can have custom text and color, but must follow private activities guidelines (e.g. can't be stretched vertically). Guidelines can be omitted if there is not enough space left.
- For main screen (centered, like on the *New Stadium* environment) use *16x9* screen if there is nothing to show. If there's anything else such as news, artwork or other content you want to present — use *16x9_blank* screen on top of your desired image. Don't forget to edit or remove credits text.
- *activity_banner* template can be used for banners in *News* activities. Any additional image can be added, but everything must be aligned in the center. Any additional background must be set to 75% opacity, keeping the blue background color.


### Logo

1. Use *Comfortaa* font, *Bold* style, *200pt* size.
2. Set *Spacing between letters* to *25*.
3. Set *Fill color* to *transparent* color, *Stroke color* to desired color, *Stroke style — Width* to *10mm*.
4. Select text, apply *Object to Path*, then *Stroke to Path*, then *Ungroup*.
5. Apply *Align and Distribute* — *Make horizontal gaps between objects equal*, adjust positions manually if needed, *Group* all letters.
6. Sometimes artifacts appear on the text. Remove them manually using *Edit paths by nodes*.
7. Align text as needed, duplicate it, hold *Shift* and click *Down* one time to move it down by some pixels.
8. Lower (-in Z axis) duplicated text using *Lower section to bottom (End)*. Apply desired color.
9. You're done with your fancy text!

### Structure

If you have a source of your project, use `content` and `source` folders inside the project (e.g. `trackmania/club`) folder. If you don't have a source, omit these folders and use the project root folder as your primary storage. Try not to omit the source as it can be helpful if you lose the access to the source or other people might want to use it in their creations.

### Naming

Keep it `snake_case`, unless different naming style is required (e.g. `trackmania/mod/stadium/source`).

### Software

Please stick to *open-source/libre* software (*InkScape*, *GIMP*, etc.) so it is easier for other people to pick up on creating new content and resources.

### Credits

Credits are specified in each project folder (where applicable) using the *CREDITS.md* file.
