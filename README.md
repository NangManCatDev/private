[./install.sh]: Next command:
handle-deprecated-dependencies
[./install.sh]: Removing deprecated dependencies:
error: target not found: illogical-impulse-microtex
error: target not found: illogical-impulse-pymyc-aur
error: target not found: illogical-impulse-ags
error: target not found: hyprutils-git
error: target not found: hyprpicker-git
error: target not found: hyprlang-git
error: target not found: hypridle-git
error: target not found: hyprland-qt-support-git
error: target not found: hyprland-qtutils-git
error: target not found: hyprlock-git
error: target not found: xdg-desktop-portal-hyprland-git
error: target not found: hyprcursor-git
error: target not found: hyprwayland-scanner-git
error: target not found: hyprland-git
Attempting to set previously explicitly installed deps as implicit...
[./install.sh]: Command "handle-deprecated-dependencies" finished.
####################################################
[./install.sh]: Next command:
install-local-pkgbuild ./arch-packages/illogical-impulse-audio --needed --noconfirm
~/.cache/dots-hyprland/arch-packages/illogical-impulse-audio ~/.cache/dots-hyprland
[./install.sh]: Command "pushd ./arch-packages/illogical-impulse-audio" finished.
Sync Dependency (5): swww-0.9.5-2, pavucontrol-1:6.1-1, wireplumber-0.5.8-1, libdbusmenu-gtk3-16.04.0.r498-2, playerctl-2.4.1-4
warning: pavucontrol-1:6.1-1 is up to date -- skipping
warning: wireplumber-0.5.8-1 is up to date -- skipping
warning: libdbusmenu-gtk3-16.04.0.r498-2 is up to date -- skipping
warning: playerctl-2.4.1-4 is up to date -- skipping
warning: swww-0.9.5-2 is up to date -- skipping
 there is nothing to do
[./install.sh]: Command "yay -S --needed --noconfirm --asdeps pavucontrol wireplumber libdbusmenu-gtk3 playerctl swww" finished.
==> WARNING: A package has already been built, installing existing package...
==> Installing package illogical-impulse-audio with pacman -U...
