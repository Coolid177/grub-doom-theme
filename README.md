installation instructions:
move this folder to /boot/grub/themes
the grub folder can also be named grub2, this should not cause any problems.
in /etc/default/grub you have to uncomment the "GRUB_THEME" and set it to /boot/grub/themes/grub-doom-theme/theme.txt
afterwards you run the following command: sudo grub-mkconfig -o /boot/grub/grub.cfg
Note: I noticed that the downloaded folder (directly from github) is called grub-doom-theme-main. if you don't change the name then make sure you put it like this in the grub file properly.

If you reboot now you will see the new theme
--
I would liike to add that this is a custom project. It should function normally however, the fonts and their sizes are not what they should be. The fonts are always the same as are their sizes, even when using different pf2 styles. This could be just my issue because I saw a lot of themes where this is not the case. If you know how to fix this don't hesitate to contact me.
