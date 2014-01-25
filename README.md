# Wombat Theme

![Wombat Theme](https://dl.dropboxusercontent.com/u/9356056/wombat.png)

## Installation

Install it using [Sublime Package Control](http://wbond.net/sublime_packages/community) and append following settings:

```json
{
  "theme": "Wombat.sublime-theme",
  "wombat_color_blue": true,
  "wombat_dirty_bottom_bar_blue": true,
  "color_scheme": "Packages/Wombat Theme/Wombat.tmTheme",
}
```

You need to restart Sublime Text!

## Features

* Works for Sublime Text 3 (and 2).
* Highly customizable thanks to [Phoenix Theme](http://netatoo.github.io/phoenix-theme/) and [Soda Theme](https://github.com/buymeasoda/soda-theme/wiki/Theme-customisation).
* Supports high resolution Retina displays.
* Any italic fonts are disabled.
* Two more theme variations. One with darker background and one like Nexus Theme.

It also sets few default options I find useful (you can always change them):

```json
{
  "auto_complete_commit_on_tab": true,
  "highlight_line": true,
  "overlay_scroll_bars": "enabled",
  "tab_size": 2,
  "translate_tabs_to_spaces": true,
  "use_simple_full_screen": true
}
```

## Customization

Wombat allows any config available in the [Phoenix Theme](https://github.com/netatoo/phoenix-theme).

You just have to change the prefix from `phoenix_` to `wombat_`. Here are defaults set by Wombat:

```json
{
  "wombat_color_expanded_folder": true,
  "wombat_dirty_bottom_bar": true,
  "wombat_sidebar_tree_small": true,
  "wombat_solid_current_tab": true,
  "wombat_tabs_medium": true
}
```

You can disable them by changing `true` to `false` in your User settings.

## Thanks

* Ian Hill for [Soda Theme](https://github.com/buymeasoda/soda-theme)
* Simon Martins for [Phoenx Theme](https://github.com/netatoo/phoenix-theme)
* Tony Kemp for [Wombat Color Scheme](https://gist.github.com/305111/c6c7a1e1e598d741a4848c5445d2012603cedcd3)

## License

Wombat is licensed under the [Creative Commons Attribution-ShareAlike 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/). You are awesome.


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/sheerun/sublime-wombat-theme/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

