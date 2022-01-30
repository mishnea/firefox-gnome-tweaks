# firefox-gnome-tweaks

Adds some modifications to [Firefox GNOME theme](https://github.com/rafaelmardojai/firefox-gnome-theme/).

![image](https://user-images.githubusercontent.com/40896537/151719119-02324ae2-d1d7-420b-acff-299e4f8dbf45.png)

## Changes

### Container tabs

Changes the dot to a glow effect at the top of tabs. The glow is larger on mouse hover or on selecting the tab. Also provides a quick pulse effect on switching.

### Muted pinned tabs

Removes the stroke from the muted tab icon. Makes the icon smaller to prevent the tab size changing.

## Installation

1. Install the [Firefox GNOME theme](https://github.com/rafaelmardojai/firefox-gnome-theme/) if you don't have it already
2. Clone this repository
3. In the URL bar, navigate to to about:profiles
4. Open the root directory of the profile you want to change
5. Navigate to `chrome/firefox-gnome-theme/`
6. Copy `customChrome.css` there or make a symbolic link

## Customization

You should be able to achieve most of the changes you want by changing the variables at the top of the file, so not much knowledge of CSS is necessary.
