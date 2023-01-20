# Let's begin

-----------------

### GDM Login setting

You can follow the desktop environment settings

    cp ~/.config/monitors.xml /var/lib/gdm/.config/
theme and background setting tool [gdm-tools](https://github.com/realmazharhussain/gdm-tools)

setting background

    set-gdm-theme set -b /home/user/picture/youset.jpg
setting theme

    set-gdm-theme -l
    set-gdm-theme -s orchis
    
-----------------

### Shutdowm On-screen keyboard

install tool

    gnome-shell-extension-manager
open extension-manager

    caribou 36
    
-----------------

### Global input method

    vim /etc/environment
    
    GTK_IM_MODULE=fcitx
    QT_IM_MODULE=fcitx
    XMODIFIERS=@im=fcitx
    SDL_IM_MODULE=fcitx
    DefaultIMModule=fcitx
