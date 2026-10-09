# Chinese Countryside

An [Omarchy](https://omarchy.org/) theme built around the colors of a rural sunset: rice fields, blue sky, and the warm orange of the setting sun.

![palette](#)

## Install

```bash
omarchy theme install https://github.com/FlyingBassHot/omarchy-chinese-countrysid-theme.git
```

Then switch to it:

```bash
omarchy theme set chinese-countrysid
```

Cycle through backgrounds with `omarchy theme bg next`.

## Palette

| Role | Color | Source |
| --- | --- | --- |
| `accent` | `#c7ea99` | 嫩芽绿 — young rice shoots |
| `foreground` | `#e8823d` | 夕阳橙 — the setting sun |
| `background` | `#22261a` | 夜色田野 — fields at dusk |
| `bright_foreground` | `#8abdd9` | 天蓝 — open sky |
| `blue` | `#5ea8d8` | 天蓝 — open sky |
| `cyan` | `#6fb8a8` | 溪水青 — stream water |
| `green` | `#96c470` | 秧苗绿 — rice seedlings |
| `yellow` | `#e5b84f` | 油菜花黄 — rapeseed blossoms |
| `red` | `#e06a4f` | 朱砂 — sunset red |

Dark mode, with warm off-white secondary text and muted green-greys for comments and inactive elements.

## Structure

```
colors.toml     # the entire palette — every app config is generated from this
backgrounds/    # wallpapers, cycled with `omarchy theme bg next`
```

Everything else — terminal colors, bar, notifications, lock screen, btop, editors, browser frame — is generated from `colors.toml` by Omarchy's templates when the theme is applied. To tweak the theme, edit `colors.toml` and re-apply:

```bash
omarchy theme set chinese-countrysid
```

## Notes

- This theme ships only `colors.toml` and wallpapers, so it works on any Omarchy install regardless of hardware.
- Keyboard lighting is left at the `accent` color and only applies to ASUS ROG (via `asusctl`) and Framework Laptop 16 keyboards.

## 中文说明

以乡村夕阳为灵感的主题：稻田的嫩芽绿、夕阳的暖橙、天空的天蓝。深色模式，正文用夕阳橙，强调色用嫩芽绿。

修改方法：编辑 `colors.toml` 后运行 `omarchy theme set chinese-countrysid` 重新应用即可，其他所有应用（终端、状态栏、通知、锁屏、编辑器）的配色都会自动从它生成。