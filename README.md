# Windows 10 Transformation Theme for RaspiOS
Make Raspberry Pi OS look as close to Windows 10 as possible.
Installs an icon theme, GTK theme, mouse cursor, openbox theme, xcompmgr, and custom panel.

To download:

    git clone https://github.com/Botspot/Windows-10
    
To install:
    
    /home/pi/Windows-10/install

To uninstall:

    /home/pi/Windows-10/uninstall
    sudo apt purge xcompmgr gtk2-engines-murrine tint2 -y
## Credit:
- The icon theme is originally from [the B00merang project](https://github.com/B00merang-Artwork/Windows-10). Customizations were added by [the TwisterOS team](https://twisteros.com/). Botspot further customized the icon theme to be compaitble with Raspbian.
- The GTK theme is based on [the B00merang project](https://github.com/B00merang-Project/Windows-10). Botspot heavily modified it to work best with Raspbian.
- The mouse cursor theme is non-modified Windows 8.1 mouse cursor theme, gotten from [here](https://www.gnome-look.org/p/1084938/).
- The openbox theme was designed from scratch by Botspot.
- Xcompmgr adds transparency and shadows to windows. Non-modified.
- The 'custom panel' is actually two panels, one over the other. The lower one is `lxpanel`, and Botspot designed the entire theme from scratch. The upper one is `tint2`, and Botspot designed all the taskbar elements from scratch.
