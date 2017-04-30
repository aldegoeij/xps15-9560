# xps15-9560
My Dell XPS 15 9560 (2017) linux tweaks. Ubuntu, gnome, wayland, etc.

## Some one-off settings

### GRUB and boot:
Add the following to `/etc/defaults/grub` and run `sudo update-grub`:

```bash
GRUB_GFXMODE=1920x1080,1024x720,auto
GRUB_GFXPAYLOAD_LINUX=keep
```
