# Argos Extensions

## Argos

_Argos lets you write GNOME Shell extensions in a language that every Linux user is already intimately familiar with: Bash scripts._

* [argos on github](https://github.com/p-e-w/argos)
* [argos on extensions.gnome.org](https://extensions.gnome.org/extension/1176/argos/)

## Extensions

These can be installed by copying the files to `.config/argos` after installing the argos extension itself.

### `zoom.sh`

This extension allows you to set fractional scaling factors using `xrandr`.

First you have to enable the experimental scaling feature in GNOME/Mutter:

```
$ gsettings set org.gnome.mutter experimental-features "['scale-monitor-framebuffer']"
```

Then install the extension and use the new dropdown menu on the top bar.

See also:
* [ArchWiki article on HiDPI](https://wiki.archlinux.org/index.php/HiDPI#Desktop_environments)
