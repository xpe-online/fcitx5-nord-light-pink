# fcitx5-nord

Fcitx5 theme based on Nord color.

Nord-Light was changed into Nord-Light-pink in this fork.

## Screenshot

![Light Variant](https://github.com/user-attachments/assets/1321929c-dad1-4973-b7cf-5f63e9766a25)
![Dark Variant](https://user-images.githubusercontent.com/29998228/127147288-372b2a8b-59ff-47be-9f60-274b12361c8c.png)

## Usage

### Installation

```sh
git clone https://github.com/xpe-online/fcitx5-nord-light-pink.git
mkdir -p ~/.local/share/fcitx5/themes/
cd fcitx5-nord
cp -r Nord-Dark/ Nord-Light/ ~/.local/share/fcitx5/themes/
```

### Enabling

In `~/.config/fcitx5/conf/classicui.conf`, change the `Theme` line as

```dosini
Theme=Nord-Dark
# or
Theme=Nord-Light
```

Then restart fcitx5 to apply the theme.

```sh
fcitx5 -r
```
