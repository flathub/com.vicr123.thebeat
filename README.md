# theBeat

___Audio Player___

Play and organise your music. theBeat automatically discovers music on your computer and presents it in an easy-to-use interface.

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```bash
flatpak install flathub com.vicr123.thebeat
flatpak run com.vicr123.thebeat
```

## Building

```bash
git clone git@github.com:flathub/com.vicr123.thebeat.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install com.vicr123.thebeat.yml
```
