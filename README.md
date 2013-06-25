# Wombat Theme

![Wombat Theme](https://dl.dropboxusercontent.com/u/9356056/wombat.png)

## Features

* Works for Sublime Text 3 (and 2).
* Highly customizable thanks to [Phoenix Theme](http://netatoo.github.io/phoenix-theme/) and [Soda Theme](https://github.com/buymeasoda/soda-theme/wiki/Theme-customisation).
* Supports high resolution Retina displays.
* Any italic fonts are disabled. Everything's straight.
* A bit darker background. I find it more easthetic and easier to read.

It also sets few default options I find useful (you can always change them):

```
  "auto_complete_commit_on_tab": true,
  "highlight_line": true,
  "overlay_scroll_bars": "enabled",
  "show_full_path": true,
  "tab_size": 2,
  "translate_tabs_to_spaces": true,
  "use_simple_full_screen": true
```

## Installation

Install it by [Sublime Package Control](http://wbond.net/sublime_packages/community) and set following setting:

```
  "theme": "Wombat.sublime-theme",
  "color_scheme": "Packages/Wombat Theme/Wombat.tmTheme"
```

You also need to restart Sublime Text.

## Customization

Wombat allows any config available in the [Phoenix Theme](https://github.com/netatoo/phoenix-theme). 

You just have to change the prefix from `phoenix_` to `_wombat`. Here are defaults set by Wombat:

```
  "wombat_color_blue": true,
  "wombat_color_expanded_folder": true,
  "wombat_dirty_bottom_bar": true,
  "wombat_dirty_bottom_bar_blue": true,
  "wombat_sidebar_tree_small": true,
  "wombat_solid_current_tab": true,
  "wombat_tabs_medium": true
```

You can disable them by changing `true` to `false` in your User settings.

## Thanks

* Ian Hill for [Soda Theme](https://github.com/buymeasoda/soda-theme)
* Simon Martins for [Phoenx Theme](https://github.com/netatoo/phoenix-theme)
* Tony Kemp for [Wombat Color Scheme](https://gist.github.com/305111/c6c7a1e1e598d741a4848c5445d2012603cedcd3)

## License

Wombat is licensed under the [Creative Commons Attribution-ShareAlike 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/). You are awesome.
