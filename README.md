# Bspwm-AIM

Configuración personal de Bspwm. Esta configuración requiere de Polybar, Compton, Nitrogen, Feh, Rofi y Dmenu para su funcionamiento básico.

**(De vital importancia que cada software tenga sus respectivas dependencias.)**


## Fuentes
Para agregar las fonts personalizadas al sistema debes asegurarte que la carpeta `/usr/local/share/fonts/` exista, de no ser así debes crearla con el siguiente comando: `# mkdir /usr/local/share/fonts`.

### Instalación
Entrar en el archivo descargado de git y seguir la siguiente secuencia de comando:

~~~
  $ cd Bspwm-AIM
  $ cp -r ~/Bspwm-AIM/fonts /usr/local/share/fonts/
~~~

Y listo.


## Bspwm & Sxhkd

### Instalación de prerequisitos
Instalación de `Nitrogen`, `Feh`, `Rofi` y `Dmenu`.

~~~
  # pacman -S nitrogen
  # pacman -S feh
  # pacman -S rofi
  # pacman -S dmenu
  # pacman -S compton
~~~

### Descarga
Se debe descargar `bspwm` y `sxhkd`.

~~~
  # pacman -S bspwm
  # pacman -S sxhkd
~~~

### Instalación de la configuración



## Github de los programas
- [bspwm](https://github.com/baskerville/bspwm).
- [sxhkd](https://github.com/baskerville/sxhkd).
- [nitrogen](https://github.com/l3ib/nitrogen).
- [feh](https://github.com/derf/feh).
- [rofi](https://github.com/davatorium/rofi).
- [dmenu](https://github.com/stilvoid/dmenu).
- [compton](https://github.com/chjj/compton).
