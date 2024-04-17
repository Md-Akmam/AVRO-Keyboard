# AVRO-Keyboard
for new
setup bangla keyboard
# Use the AVRO Phonetic in any Linux Distro with the OpenBangla Keyboard

## Follow all the steps accordingly:

**The complete process has been provided in a [YouTube video](https://youtu.be/C8vnR1AY6sA) as well.**

1. Update and Upgrade the database

```bash
sudo pacman -Syu
```

```bash
sudo pacman -Syy
```

2. Manual installation

```bash
sudo pacman -S base-devel git
git clone https://aur.archlinux.org/openbangla-keyboard.git
cd openbangla-keyboard
makepkg -risc
```

3. Configure the desktop environment using the [official guideline](https://github.com/OpenBangla/OpenBangla-Keyboard/wiki/Configuring-Environment).

4. Install the `manjaro-asian-input-support-ibus` package

```bash
git clone https://aur.archlinux.org/manjaro-asian-input-support.git
cd manjaro-asian-input-support
makepkg
pacman -U ibus-input-support-*.pkg.tar.zst
```

5. Logout/Restart
