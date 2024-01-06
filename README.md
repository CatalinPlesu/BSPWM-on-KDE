# BSPWM on KDE
 Using BSPWM instead of KWIN on KDE
 
# systemd startup
Plasma uses a systemd user instance to launch and manage all the Plasma services. This is the default startup method since Plasma 5.25, but can be disabled to use boot scripts instead with the following command (however this may stop working in a future release):

$ kwriteconfig5 --file startkderc --group General --key systemdBoot false

# executable
bspwmrc, sxhdrc shoud be made executable
