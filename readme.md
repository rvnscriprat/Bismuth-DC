There aren't really any special changes to Basalt aside from my specific setup so I'll leave the original README more or less untouched.

# Bismuth

A frosted Discord theme with a splash of color.

<img width="2722" height="1802" alt="image" src="https://github.com/user-attachments/assets/0cfc45ca-5184-4be8-b5ae-e3c49aa1416f" />

## Customize

Everything lives in the `:root` block at the top.

| Variable                    | Does                                     |
| --------------------------- | ---------------------------------------- |
| `--bg-image`                | Wallpaper URL                            |
| `--bg-blur`                 | Wallpaper blur                           |
| `--bg-brightness`           | Wallpaper brightness                     |
| `--tint`                    | Base tint as `r, g, b`                   |
| `--tint-app`                | Overall darkening                        |
| `--tint-panels`             | Sidebar and member list darkening        |
| `--glass` / `--glass-heavy` | Surface opacity                          |
| `--blur-sm` / `--blur-lg`   | Backdrop blur strength                   |
| `--accent`                  | Mentions, hovers, scrollbar as `r, g, b` |

Swapping the wallpaper is one line:

```css
--bg-image: url(your-image-here);
```

## Notes

Selectors use prefix matching (`[class*="chat_"]`) instead of Discord's hashed class names, so updates are less likely to break it. If something does break, the hash rotated on a selector that needed a more specific anchor.

Backdrop blur requires hardware acceleration. Turn it on in Discord Settings > Advanced.

## Links

[Discord](https://discord.com/invite/Dvh2veTWU4) · rogo@galxy.it.com
