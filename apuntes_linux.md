---
YAML
---
# Linux

## log de instalaciones (2018)

* Linux LXLE ubuntu 16.04.03 LTS (Xenial Xerus)
* Guake Terminal (mediante Synaptic Package Manager)
* [Sublime Text 3](https://www.sublimetext.com/docs/3/linux_repositories.html#apt)
* [Ruby](https://gorails.com/setup/ubuntu/16.04)
* Git
* Bundler
* Firefox
* Dropbox (nautilius Dropbox, via Lubuntu Software Center)
* nodejs
* npm
* Bower/Yarn
* Rainbowstream (Twitter)
* gitg
* GNU emacs 24
* ARandR

Todo esto es lo que instalé en la compu que me robaron.

---

## Instalaciones 2019

Probando:

- **Bunsenlabs:** Con ambiente operativo **OpenBox, Tint2, etc.** _Tomar notas de componentes esenciales_ Ver: [https://youtu.be/TUXohePdiR4]
- **Kali linux:** Con ambiente operativo **LXLE.** _Chingón para pruebas con kali. era el anterior que instalé en la compu paolax_
- **MX linux:** Con ambiente operativo **XFCE.** _livianos o mediano, XFCE ha estado muy ien para empezar. Distribución chida.
  - Update (4 mayo): El USB con persistencia un poco lento.

Ambientes operativos:

- **XFCE:** thumbs up
- **LXDE:** Muy liviano y fácil de aprender. Basado en OpenBox. 
  - https://lxde.org
  - https://www.zdnet.com/article/how-to-customise-your-linux-desktop-lxde/
- **Openbox:** El puro gestor de ventanas, simple y súpoer rápido. Como en la distribución de Bunsen, un simple gestor de ventanas más un panel (Tint2), más un lanzador y alguna que otra cosa, bastan pa tener un mínimo ambiente operativo altamente configurable.

Me quedan por probar gestores de ventanas aún más simples como  **Ratpoison** o **Xmonad** [https://xmonad.org/] Que se ven interesantes en cuanto a la rapidez de trabajo que se logra con ellos aunque cuesta un poco más dominarlos. UPDATE: probé un poco **awesomeWM** y **xmonad**. voy a probar **bspwm**. Con Ratpoison no he podido hacer que jale.

De los más pesados y populares casi solo probé **Gnome**. Después descubrí **KDE** y me gustó más.


IRC:

Servidores: EFNet, UnderNet, DalNet, QuakeNet, freenode



* * *
- - -
* * *

# comandos

- ifconfig:
- lsusb:
- rfkill list all:
  - soft blocked
  - hard blocked
 - sudo apt-get install ibus
   - ibus-setup

 # portable bunsenlabs
 https://www.bunsenlabs.org/installation.html#live-cddvdusb-key-method
 https://unetbootin.github.io/

# Temas
- Dual Boot: (https://www.lifewire.com/dual-boot-linux-and-mac-os-4125733)
- Libro sobre linux
- **Boot manager.** rEFInd
- **Clonezilla:** Portable linux installation to clone any disc

# How do I change default terminal?

From within a terminal, try

'''
sudo update-alternatives --config x-terminal-emulator
'''

Select the desired terminal from the list of alternatives.

