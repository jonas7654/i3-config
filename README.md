# i3-config
https://github.com/Jvanrhijn/polybar-spotify #dependency: pip3 install dbus-python




Packages to install:

    xautolock so that auto-locking works properly.
    arandr for easily changing display settings.
    lxappearance to set gtk settings
    feh to set background image easily
    thunar, a file explorer
    gnome-icon-theme-full to get icons on thunar
    arc-theme. Needs to be added to sources - see instructions at https://github.com/horst3180/arc-theme
    rofi, a dmenu replacement
    picom, to support transparent windows in i3 (to beautify rofi). Compton messes up background settings, so we need to execute feh once when i3 logs in (this is in the config file). To generate the feh script, run this once: feh --bg-fill /usr/share/backgrounds/warty-final-ubuntu.png - it will generate a shell script in ~/.fehbg that the i3 config runs when it starts
    scrot, to be able to take screenshots for locking the screen
    imagemagick, to get the convert(1) command
    pavucontrol for setting and fetching the volume level. i3blocks relies on pulse audio to get the correct volume level
    betterscreenlock for better screenlocking 
    jq for weather widget

Fonts to install (copy the .ttf files to ~/.fonts):

    Awesome (https://github.com/FortAwesome/Font-Awesome), for the special cute icons
    Yosemite San Francisco (https://github.com/supermarin/YosemiteSanFranciscoFont), to set as system font with lxappearance. Note: shows up as SFNS Display on lxappearance.

