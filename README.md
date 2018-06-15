# Instalacion de macbuntu en Ubuntu 18.04
Instala el tema de Macbuntu, macos en un ubuntu 18.04

## Video
Revisa el link del video en youtube para poder usar o en mega:

1. Link YouTube: [YOUTUBE](https://www.youtube.com/watch?v=sfsKwzElxQg)
2. Link Mega: [MEGA](https://mega.nz/fm/z4piGQQb)

## Pasos

### 1. Instalar ubuntu

Descarga e Instalar Ubuntu 18.04

1. LINK: [UBUNTU](https://www.ubuntu.com/download)

### 2. Instalar Gnome Tweak Tool

#### a) Ubuntu Software

Buscar en el `Ubuntu Software store` la palabra `Gnome tweaks` e instalar mediante la herramienta. 

#### b) Terminal

Para instalar el paquete `gnome-tweak-tool` se debe de correr el siguiente comando:

```
$ sudo apt install gnome-tweak-tool
```

* **Usamos `apt` en ves de `apt-get` por eficiencia** [link de explicacion](https://itsfoss.com/apt-vs-apt-get-difference/)

### 3. Instalar User Themes

Para instalar el `User Themes` debemos dirigirnos a `gnome extensions` e instalar:

1. Link User Themes: [USER THEMES](https://extensions.gnome.org/extension/19/user-themes/)

* **Para instalarlo de manera rapida usar el `gnome shell integration` plugin en chrome o su respectivo plugin en otro navegador, ademas de esto debe de instalar el `chrome-gnome-shell` en ubuntu con el siguiente comando:**

```
$ sudo apt install chrome-gnome-shell
```

### 4. Instalar Tema Gnome-OSC

#### Instalar

Para instalar el tema debemos de dirigirnos a `Gnome look` y buscar el tema `Gnome-OSC`. El link es el siguiente:

1. Link Gnome-OSC: [GNOME-OSC](https://www.gnome-look.org/p/1171688/)

#### Copiar archivos

Despues de descargar el tema lo debemos de descomprimir y copiar los temas: `Gnome-OSC-HS-(not-transparent)` y `Gnome-OSC-HS-(transparent)`.

Antes de copiarlos, debemos de crear un directorio en la carpeta `home` con el nombre `.themes`. Para poder ver archivos ocultos debemos abrir el nautilus (el explorador de archivos de ubuntu) y aplastar la combinacion de teclas: `ctrl` + `h`.

Ahora si copiamos `los archivos` en la carpeta `.themes`

#### Habilitar el tema con Gnome Tweak 

Finalmente buscamos en las actividades (activities o programas) `tweaks` y nos dirijimos a la pestaña **Appearance** y cambiamos en `Themes > Applications` al tema preferido.

### 5. Instalar Iconos

Para instalar los iconos debemos de dirigirnos a `Gnome look` y buscar el tema `MacOS sierra ct`. El link es el siguiente:

1. Link MacOS sierra ct: [MACOS SIERRA CT](https://www.gnome-look.org/p/1210856/)


#### Copiar archivos

Despues de descargar los iconos lo debemos de descomprimir y copiar los iconos: `Macos-sierra-CT-0.2`.

Antes de copiarlos, debemos de crear un directorio en la carpeta `home` con el nombre `.icons`. Para poder ver archivos ocultos debemos abrir el nautilus (el explorador de archivos de ubuntu) y aplastar la combinacion de teclas: `ctrl` + `h`.

Ahora si copiamos `los archivos` en la carpeta `.icons`

#### Habilitar el tema con Gnome Tweak 

Finalmente buscamos en las actividades (activities o programas) `tweaks` y nos dirijimos a la pestaña **Appearance** y cambiamos en `Themes > Icons` al tema preferido.

### 6. Instalar Dash to Dock

Para instalar el `Dash to Dock` debemos dirigirnos a `gnome extensions` e instalar:

1. Link Dash to Dock: [DASH TO DOCK](https://extensions.gnome.org/extension/307/dash-to-dock/)

* **Para instalarlo de manera rapida usar el `gnome shell integration` plugin en chrome o su respectivo plugin en otro navegador, ademas de esto debe de instalar el `chrome-gnome-shell` en ubuntu con el siguiente comando:**

```
$ sudo apt install chrome-gnome-shell
```


### 7. Instalar Blyr

Para instalar el `Blyr` debemos dirigirnos a `gnome extensions` e instalar:

1. Link Blyr: [BLYR](https://extensions.gnome.org/extension/1251/blyr/)

* **Para instalarlo de manera rapida usar el `gnome shell integration` plugin en chrome o su respectivo plugin en otro navegador, ademas de esto debe de instalar el `chrome-gnome-shell` en ubuntu con el siguiente comando:**

```
$ sudo apt install chrome-gnome-shell
```


### 8. Instalar macOS High Sierra a21 Shell Theme

Para instalar el tema del shell debemos de dirigirnos a `Gnome look` y buscar el tema `macOS High Sierra a21`. El link es el siguiente:

1. Link macOS High Sierra Shell Theme: [MACOS HIGH SIERRA SHELL THEME](https://www.gnome-look.org/p/1213208/)


#### Copiar archivos

Despues de descargar los iconos lo debemos de descomprimir y copiar el tema: `MacOS_HS`.

Antes de copiarlos, debemos de crear si no existe un directorio en la carpeta `home` con el nombre `.themes`. Para poder ver archivos ocultos debemos abrir el nautilus (el explorador de archivos de ubuntu) y aplastar la combinacion de teclas: `ctrl` + `h`.

Ahora si copiamos `los archivos` en la carpeta `.themes`

#### Habilitar el tema con Gnome Tweak 

Finalmente buscamos en las actividades (activities o programas) `tweaks` y nos dirijimos a la pestaña **Appearance** y cambiamos en `Themes > Shell` al tema preferido.

#### Copiar fonts en carpeta .local

al descomprimir `MacOS_HS` se nos crean algunas carpetas, una de estas se llama: `FONT` dentro de esta carpeta se encuentran dos archivos, uno **.ttf** y otro **.otf**. Copiar estos dos archivos  a la carpeta :`home > .local > share > fonts`.

#### Ejecutar comandos

Para finalizar con este paso, abre una `terminal` y ejecuta los comandos en **ORDEN**:

1. Mostrar botones a la izquierda

```
$ gsettings set org.gnome.shell.extensions.dash-to-dock show-apps-at-top true
$ gsettings set org.gnome.desktop.wm.preferences button-layout 'close,maximize,minimize:'
```

2. Custom dock indicator

```
$ gsettings set org.gnome.shell.extensions.dash-to-dock custom-theme-running-dots false
$ gsettings set org.gnome.shell.extensions.dash-to-dock custom-theme-customize-running-dots false
```

3. Dock Shrink 

```
$ gsettings set org.gnome.shell.extensions.dash-to-dock custom-theme-shrink false
```

4. Dock Transparency 

```
$ gsettings set org.gnome.shell.extensions.dash-to-dock transparency-mode DEFAULT
```


### 9. Cambiar login screen

Para instalar el login screen debemos de dirigirnos a `Gnome look` y buscar el tema `MacOS High Sierra cdm theme`. El link es el siguiente:

1. Link MacOS High Sierra cdm theme: [MACOS HIGH SIERRA cdm theme](MacOS High Sierra cdm theme)

#### Copiar archivos

Despues de descargar los iconos lo debemos de descomprimir y abrir la carpeta: `SetAsWallpaperV1.3`.

Abrir una terminal en la carpeta `SetAsWallpaperV1.3` y ejecutar los siguientes comandos en orden:

1. Copiar css (cambiar los directorios segun la ubicacion

```
$ sudo cp ubuntu.css /usr/share/gnome-shell/theme/ubuntu.bak
$ sudo cp ubuntu.css /usr/share/gnome-shell/theme/
$ sudo chmod 777 /usr/share/backgrounds/
```
2. Copiar mediante el explorador de archivos el archivo con nombre `SetAsWallpaper` en la carpeta `home > .local > share > nautilus > scripts`.

3. Cambiar permisos
```
$ chmod a+x ~/.share/local/nautilus/scripts/
```

Finalmente cambiar el wallpaper sobre una imagen con un `click derecho > scripts > SetAsWallpaper`


#Creditos 

- Adrian Eguez
- Shivam ashtikar













