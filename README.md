:sparkles::sparkles::sparkles: HEY THERE :trollface: :sparkles::sparkles::sparkles:
==============================================



-~ My current conky config [.EN] ~-




I was annoyed because many configs didn't work for me. So I decided to make my own ✌️.

It is just a simple conky config without a lot of extras but it's enough for me.

You don't need to install any font in your system!

I tested this config only on Manjaro XFCE!



### How to install? ###

Arch:
sudo pamac install conky
maybe you have to install conky-colors-git as well

Debian:
sudo apt-get install conky-all


:point_right: git clone https://github.com/eClipZe88/MyConkyConfigEN.git

:point_right: cd MyConkyConf

:point_right: cp -rf conkyrc $HOME/.conkyrc

:point_right: cp -rf anonymous.png powered_by_linux.svg.png ip.sh $HOME/.conky

:point_right: change the path in .conkyrc 	
${image /home/insane/.conky/powered_by_linux.svg.png -p 30,35 -s 320x80}
${image /home/insane/.conky/anonymous.png -p 360,440 -s 65x65}
${goto 20}Public IP » ${exec sh /home/insane/.conky/ip.sh}
maybe you have to play with the resolutions.

:point_right: finally start conky 
conky -c ~/.conkyrc & 

or use my start-conky.sh



### :point_up_2:PLEASE NOTE:point_up_2: ###
If you have more than two cores then you have to add them manually. A sample is at line 60.


ENJOY(●'◡'●) 



