Since Markdown also supports plain HTML, you can also use HTML and CSS attributes to stylize your Markdown file.

## The code.

```
<img src="https://static.wikia.nocookie.net/mlp/images/6/6c/Twilight_S2E25_cropped.png/revision/latest/scale-to-width-down/200?cb=20211016191356" alt="Twilight Sparkle Appearance in Season 1" style="display: block; margin: 0 auto">
```

## The breakdown:

```
<img src="https://static.wikia.nocookie.net/mlp/images/6/6c/Twilight_S2E25_cropped.png/revision/latest/scale-to-width-down/200?cb=20211016191356" alt="Twilight Sparkle Appearance in Season 1"
```

Here, `img src=""` is the image tag itself with it's source, and `alt="Twilight Sparkle Appearance in Season 1"` is the alternative title.

You can use CSS' style attributes as well and it will show in Obsidian for example. Just type `style` tag like you would in a proper HTML file. For example. `style="display: block; margin: 0 auto"`

## Result
This is the end result:

<img src="https://static.wikia.nocookie.net/mlp/images/6/6c/Twilight_S2E25_cropped.png/revision/latest/scale-to-width-down/200?cb=20211016191356" alt="Twilight Sparkle Appearance in Season 1" style="display: block; margin: 0 auto">

>[!info] Context
>Notice that this does not work in Github's repositories actually, but it does show in the center of the viewport using Obsidian md.

main reference: [Dev.to - Markdown : center image - DEV Community](https://dev.to/bdavidxyz/markdown-center-image-39j1)
