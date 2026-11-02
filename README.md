![](assets/newest.png) 

> [!NOTE]
> **Maintenance.** This theme was created by [Ha'ani Whitlock (Bluemoondragon07)](https://github.com/Bluemoondragon07), who wrote the original [Wikipedia Theme](https://github.com/Bluemoondragon07/Wikipedia-Theme). The original repository has had no updates since December 2024, and the author did not respond to the [offer to take over maintenance](https://github.com/Bluemoondragon07/Wikipedia-Theme/issues/29) within 30 days, so the theme is now maintained by [Bingjie Li (Bingjie9978)](https://github.com/Bingjie9978) under the original MIT license, following Obsidian's [developer policy on forks](https://docs.obsidian.md/community-directory/developer-policies). If Ha'ani wants to resume maintenance, they are welcome to.
>
> Thanks to [saberzero1](https://github.com/saberzero1) for the Obsidian 1.13 callout fix.

# Familiar Look
Make your vault look like your own personal Wikipedia! This theme styles images, headings, and even the sidebar in the classic style of your favourite encyclopedia.

# Infoboxes
Any **Info** blockquote (created using `>[!info]`) will float to the right of the note like an infobox. Inline dataview fields wrapped in brackets (like `[category::research]`) inside these **Info** blockquotes will be displayed on separate lines, styled like Wikipedia's infobox headings and descriptions (see image above). You can also create an infobox heading with a yellow background by adding a **Heading 6**. 
>Tip - Hide the infobox callout's title with the Style Settings plug-in for a cleaner look.

You can also force any callout float with the alts `left`, `right`, or `info` (see **Callout Alts** below for more details).

# Callout Alts
- `right` - float a callout right
- `left` - float a callout to the left
- `normal` - add to an Info callout to override the usual infobox styling
- `info` - give another type of callout similar properties to the Info callout, giving it more of an infobox appearance

## Examples
```markdown
>[!info|normal] This will look like a regular callout instead of an infobox.

>[!bug|right] This is a bug callout, but it floats right like an info callout!

>[!quote|left] This will float to the left.

>[!check|info] This is a **Check** callout, but it looks more like an infobox.
```

# Image Alts
- `no-float`/`normal` - prevent an image from floating
- `right` - float an image to the right
- `left` - float an image to the left
- `center` - center an image

## Examples
```markdown
![[books.png|no-float]]
![[books.png|normal]]

![right](books.png)

![[books.png|left]]

![center](books.png)
```

# Changelog

## 2.1.0
- Works with Obsidian 1.13+ (callout colors).
- Settings window, file explorer, outline and bookmarks restyled to match the theme.
- New Style Settings options: body font (sans or serif), note title size and underline, compact heading 2, quiet tags, fading block IDs, file explorer indent, and options to hide individual interface elements.
- Style Settings reorganised with clearer wording.
- Fixes: heading 6 infobox style works without Style Settings (#6); tables no longer break words mid-word (#25); `![[image.png|100]]` sizes are respected (#3, #26); infoboxes and images are full width on phones (#23); hiding properties works with Obsidian's current properties view.

## 2.0 (original author)
- All images will now float except those placed inside callouts.
  - An image directly after another image will float to the left instead of the right.
- The info callout is now the only callout that will float to the right. For simplicity, infobox blockquotes can no longer float to the right, either.
- Dark mode has been updated.
- Callouts have a new look!
- Multiple changes to typography
  - Default font changed to **Arial**
  - Modifications to Headings
- Images now have the signature Wikipedia border around them.

# Notes from the original author
- I'm not a theme developer or anything, just a 15-year-old who likes to waste time with CSS.
- A good chunk of the CSS *was* actually taken directly from Wikipedia and mapped to components in Obsidian.
- Feel free to make pull requests or suggestions for this theme. Or remix it into your own thing. It's under the MIT license.
## Screenshots (Outdated)

![](assets/article-example.png)

![](assets/Headings-showcase.png)
*Wikipedia-style headings*

![](assets/dataview-table-showcase.png)
*Dataview Support*

![](assets/List-showcase.png)
*Square checkboxes*

![](assets/Article-showcase.png)
*Floating images & callouts; Wikipedia-style links*
