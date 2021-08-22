# Taller de Linux

1. **¿Qué es Linux?**
	- Breve historia de Linux
		- Problema closed-source de Unix
		- Surgimiento de GNU
		- Integración de Linux como kernel  
		para GNU (GNU/Linux)
	- Definición de conceptos clave
		- Definición de la ideología *open-source*
			- Mucho énfasis en esto para adoctrinarlos  
			ideológicamente
		- Definición de distribuciones/distros
			- Distros y familias de distros  
			principales

2. **Instalación de Ubuntu-based**
	- ¿Por qué Ubuntu-based?
		- Prominencia en la industria
		- Ease-of-use
	- Requisitos mínimos y recomendados
	- Instrucciones de instalación
		- Descarga de la imágen de disco
		- Crear un bootable USB
			- Instrucciones para MacOS  
			y Windows
		- Preparativos por si se quiere hacer Dual-boot
		- Bootear hacia la BIOS
		- Uso de un live-environment
		- Instalación desde un live-environment
			- Instrucciones de instalación para  
			hacer dual-boot
3. **Uso de Linux**
	- Definición de Desktop Environment
	- Uso de aplicaciones gráficas
		- File Browser
		- System Monitor/Task Manager
		- Browser
		- Instalador gráfico de paquetes/App store
	- Sistema de usuarios en Linux
		- Usuario root
	- Estructura de directorios en Linux y uso de cada uno
		- Passing mention de la función de los siguientes
			- bin
				- sbin
			- boot
				- NO TOCAR
			- media/mnt
				- Tus drives se montan aquí
			- snap
			- tmp
			- usr
		- Énfasis en el home directory y en .config
			- home
				- .config
	- Uso de la Terminal **nota: ya hay un curso de Terminal de ITAM4Code**
		- The all-powerful sudo
		- Navegación del sistema
			- ls/la
			- cd
			- mkdir
			- mv
			- wget
			- cat
			- grep
		- Task Management
			- top
		- Manejo de paquetes
			- Instalación de paquetes, remover paquetes,  
			update/upgrade del sistema de manera distro-agnostic
			- Comandos de Debian para el manejo de paquetes
		- Paquetes útiles
			- GIMP
			- Inkscape
			- VLC
			- Spotify
			- Steam
			- Telegram
			- Audacity
			- Neofetch
			- Visual Studio Code
		- Uso de Git **nota ya hay un curso de Git de ITAM4Code**
			- ¿Qué es Git?
			- Crear, committear, subir,  
			clonar, mergear y jalar repositorios
		- Uso de Vim
			- Entrar y salir de Vim
			- Navegación absoluta y relativa
				- ¿Dejar VimTutor de tarea?
			- Buscar y remplazar
			- Comandos
			- Macros
			- .vimrc
			- Uso de plugins 

4. **(Opcional y a consideración) Creación de documentos con Vim, Markdown y Pandoc** 
	- Descripción de la pipeline
		- Crea tus tus documentos con Markdown/Latex,  
		súbelos a Github, conviértelos a PDF con Pandoc.
	- ¿Qué es markdown?
		- Sintaxis
		- Use cases
		- Integración con Latex/Katex
		- markdown-preview plugin para  
		Vim
		- Ventajas sobre documentos  
		convencionales
	- ¿Qué es pandoc?
		- Uso y comandos básicos de  
		conversión de archivos
		- Interacción con Markdown
		- Uso de templates
		- Ventajas sobre Word y otros
		procesadores de texto

5. **¿Where to go from here?**
	- Call-to-action a experimentar usar otras distros
	- Useful skills to learn
		- Bash-scripting
		- Awk
		- Vim (si no se vio el tema 4)
	- Ejemplos de Ricing (r/unixporn)
		- Tiling Window Managers
			- Un demo del sistema personal de uno  
			de los instructores y su workflow
