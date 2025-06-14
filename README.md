#!/data/data/com.termux/files/usr/bash

echo $(pkg updatte && pkg upgrade)
echo $(pkg install python -y)
echo $(pkg install termux-api -y)
echo $(pkg install git -y)
echo $(pkg install curl -y)
echo $(pkg install wget -y)
echo $(pkg install tmux -y)
echo $(pkg install screen -y)

#en otro dia mejorare este porcierto todo esto en un archivo.sh y con los permisos x
