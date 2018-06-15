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

#### a)

Buscar en el `Ubuntu Software store` la palabra `Gnome tweaks` e instalar mediante la herramienta. 

#### b)

Para instalar el paquete `gnome-tweak-tool` se debe de correr el siguiente comando:

```
$ sudo apt install gnome-tweak-tool
```

* **Usamos `apt` en ves de `apt-get` por eficiencia** [link de explicacion](https://itsfoss.com/apt-vs-apt-get-difference/)

### 3. Instalar User Themes

Para instalar los usert themes debemos dirigirnos a `gnome extensions` e instalar:

1. Link User Themes: [USER THEMES](https://extensions.gnome.org/extension/19/user-themes/)

* **Para instalarlo de manera rapida usar el `gnome shell integration` plugin en chrome o su respectivo plugin en otro navegador, ademas de esto debe de instalar el `chrome-gnome-shell` en ubuntu con el siguiente comando:**

```
$ sudo apt install chrome-gnome-shell
```

### 3. Instalar Tema Gnome-OSC

#### Instalar

Para instalar el tema debemos de dirigirnos a `Gnome look` y buscar el tema `Gnome-OSC`. El link es el siguiente:

1. Link Gnome-OSC: [GNOME-OSC](https://www.gnome-look.org/p/1171688/)

#### Copiar archivos

Despues de descargar el tema lo debemos de descomprimir y copiar los temas: `Gnome-OSC-HS-(not-transparent)` y `Gnome-OSC-HS-(transparent)`.

Antes de copiarlos, debemos de crear un directorio en la carpeta `home` con el nombre `.themes`. Para poder ver archivos ocultos debemos abrir el nautilus (el explorador de archivos de ubuntu) y aplastar la combinacion de teclas: `ctrl` + `h`.

Ahora si copiamos `los archivos` en la carpeta `.themes`

#### Habilitar el tema con Gnome Tweak 

Finalmente buscamos en las actividades (activities o programas) `tweaks` y nos dirijimos a la pestaña **Appearance** y cambiamos en `Themes > Applications` al tema preferido.

### 3. Instalar Iconos

Para instalar los iconos debemos de dirigirnos a `Gnome look` y buscar el tema `MacOS sierra ct`. El link es el siguiente:

1. Link MacOS sierra ct: [MACOS SIERRA CT](https://www.gnome-look.org/p/1210856/)


#### Copiar archivos

Despues de descargar los iconos lo debemos de descomprimir y copiar los iconos: `Macos-sierra-CT-0.2`.

Antes de copiarlos, debemos de crear un directorio en la carpeta `home` con el nombre `.icons`. Para poder ver archivos ocultos debemos abrir el nautilus (el explorador de archivos de ubuntu) y aplastar la combinacion de teclas: `ctrl` + `h`.

Ahora si copiamos `los archivos` en la carpeta `.icons`

#### Habilitar el tema con Gnome Tweak 

Finalmente buscamos en las actividades (activities o programas) `tweaks` y nos dirijimos a la pestaña **Appearance** y cambiamos en `Themes > Icons` al tema preferido.

