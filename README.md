# fcitx5-nord-pink

Modified from [tonyfettes/fcitx5-nord](https://github.com/tonyfettes/fcitx5-nord).

Fcitx5 theme based on Nord color.

## Screenshot

![Light Variant](https://github.com/user-attachments/assets/1321929c-dad1-4973-b7cf-5f63e9766a25)

## Usage

### Installation

```sh
git clone https://github.com/xpe-online/fcitx5-nord-pink.git
mkdir -p ~/.local/share/fcitx5/themes/
cd fcitx5-nord-pink
cp -r Nord-Pink/ ~/.local/share/fcitx5/themes/
```

### Enabling

In `~/.config/fcitx5/conf/classicui.conf`, change the `Theme` line as

```dosini
Theme=Nord-Pink
```

Then restart fcitx5 to apply the theme.

```sh
fcitx5 -r
```
