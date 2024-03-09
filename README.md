Clonar el repositorio:
Abre una terminal en Kali Linux.
Ejecuta el siguiente comando para clonar el repositorio de rxyhn/tokyo:
git clone https://github.com/rxyhn/tokyo.git

Instalar dependencias:
Asegúrate de tener las siguientes dependencias instaladas:
bspwm
sxhkd
rofi
kitty
picom-ibhagwan-git
calcurse
todotxt
feh
jq
dunst
betterlockscreen
brightnessctl
playerctl
maim
xclip
imagemagick
Puedes instalarlas con el siguiente comando:
sudo apt install bspwm sxhkd rofi kitty picom-ibhagwan-git calcurse todotxt feh jq dunst betterlockscreen brightnessctl playerctl maim xclip imagemagick

Copiar archivos de configuración:
Navega al directorio donde clonaste el repositorio:
cd tokyo

Copia los archivos de configuración a sus respectivas carpetas:
mkdir -p ~/.config/ && cp -r ./config/* ~/.config/
mkdir -p ~/.local/bin/ && cp -r ./bin/* ~/.local/bin/
cp -r ./misc/* ~/

Instalar fuentes:
Descarga e instala las siguientes fuentes:
Cartograph CF
JetBrainsMono NF
Font Awesome
Comic Mono
Actualizar la caché de fuentes:
fc-cache -fv

Reiniciar el sistema:
Cierra sesión y vuelve a iniciar sesión.
Selecciona bspwm como el gestor de ventanas al iniciar sesión.
Atajos de teclado:
Algunos atajos de teclado en este entorno:
Windows + Enter: Abre una ventana de emulador de terminal (kitty).
Windows + W: Cierra la ventana actual.
Windows + Alt + R: Reinicia la configuración de bspwm.
Windows + Alt + Q: Cierra la sesión.
Windows + (⬆⬅⬇➡): Navega entre las ventanas en el espacio de trabajo actual.
Windows + D: Abre Rofi (lanzador de aplicaciones).
Y más1.
