# Klassy support for flatpak

This is a flatpak extension to allow the usage of klassy kstyle for apps. (runtime: 6.7)

Installing:
```bash
git clone https://github.com/ry-diffusion/org.kde.KStyle.Klassy
cd org.kde.KStyle.Klassy
flatpak-builder build org.kde.KStyle.Klassy.json --force-clean --install --repo=repo
flatpak override --filesystem=xdg-config/klassy --user
```
