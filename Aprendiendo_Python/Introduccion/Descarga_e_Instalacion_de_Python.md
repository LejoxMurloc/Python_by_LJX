By: CISCO - NETCAD "PYTHON ESSENTIALS 1"

## Sistemas Operativos:
- **Linux:** ya viene por defecto con Python3 , para probar en la terminal escribir "python3" y debe salir el entorno de Python, donde se mostrará la versión y el modo ejecución ">>>"
- **Windows / MacOS:** se podrá obtener mediante la tienda del sistema operativo o la opción mas recomendable es mediante su sitio oficial [https://www.python.org/downloads/](https://www.python.org/downloads/).
## Mediante líneas de comandos
- **Linux:** aunque este depende del gestor de paquetes que utilice la distribución, para el caso practico utilizaremos Ubuntu / Debian:
	1. Asegúrate de tener el sistema actualizado: `sudo apt update`
	2. Instala Python con `sudo apt install python3 python3-pip`
	   *NOTA: al instalar pip (gestor de paquetes de python) puedes instalar paquetes adicionales mas adelante*
- **Windows:** este utiliza el gestor de paquetes oficial de Microsost Windows *wingwt*
  `winget install Python.Python.3`
- **MacOS:** la recomendación para la gente de Mac es utilizar el gestor *Homebrew*, que es el gestor de paquetes por excelencia para Apple. `brew install python`
____
## Para comenzar:
Lo ideal es que  cuentes con tres (3) cosas básicas:
- Editor
- Consola / Terminal
- Depurador
Cuando se descarga Python3, dentro de sus paquetes que se instalan por defecto viene un complemento llamado **IDLE** que proviene del ingles Integrated Development and Learning Environment o en español Desarrollo Integrado y Entorno de Aprendizaje. No obstante hay otras herramientas muy conocidas para el uso del lenguaje de programación Python, como:
- VS Code: multiplataforma gratuita, creada por Microsoft 
- PyCharm: tiene una versión de pago y una gratuita, creada por JetBrains
- PyDev: opensource, con soporte para CPython , Jython y buenas integraciones con Django
- Vim y sus derivados: editor de texto comúnmente utilizado en Linux, no es un IDE como tal.
Esos son los editores más comunes, pero ahora con todo el tema de la IA llegaron los nuevos editores con Agentes de IA que nos ayudan con diversas tareas, algunos de estos editores nuevos son:
- Antygravity 
- Cursor
- ZEN

Al momento de querer ejecutar un programa escrito en Python, existen dos (2) formas fáciles de hacerlo, los IDE o los editores de Código / Texto, suelen tener un botón con un símbolo de "play" llamado "Run", el cual se encarga de leer lo que tengas en el editor, lo depura y lo muestra en consola. Dicha función "Run" en muchas ocasiones también se puede ejecutar mediante la tecla de función "F5". 
Por otro lado, el segundo método es directamente desde la consola de comandos utilizando el siguiente: `python3 nameFile.py`, recuerde que para hacer esto primero debió haber creado un archivo con la extensión .py y guardar los cambios realizado en el archivo antes del momento de ejecución mediante comandos en la consola.

Al momento de ejecutar un código Python y poseer un error en su estructura, saldrá un mensaje de error que suele ser de color rojo, el cual tiene la siguiente organización:
- el **traceback** (que es la ruta que recorre el código a través de diferentes partes del programa; puedes ignorarlo por ahora, ya que está vacío en un código tan simple) ;
- la **ubicación del error** (el nombre del archivo que contiene el error, el número de línea y el nombre del módulo); nota: el número puede ser engañoso, ya que Python suele mostrar el lugar donde notó por primera vez los efectos del error, no necesariamente el error en sí;
- el **contenido de la línea errónea**; nota: la ventana del editor de IDLE no muestra números de línea, pero muestra la ubicación actual del cursor en la esquina inferior derecha; utilízalo para localizar la línea errónea en un código fuente largo;
- el **nombre del error** y una breve explicación.