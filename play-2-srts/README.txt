# Comand
sleep 5;play /usr/share/sounds/alsa/Side_Right.wav; recordmydesktop -x 0 -y 0 --width 700 --height 700 -o foo.ogv --no-sound

gifsicle --crop 350,100-1350,900 --output out2.gif out.gif ; firefox out2.gif
