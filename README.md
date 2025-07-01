# Python-Final
README.md
Proyecto Python Final: Entorno Virtual y Comandos Git
Este repositorio contiene el trabajo realizado para la actividad "Un día como programadores"
en Python y Git.

Comandos Ejecutados en Terminal:
Aquí se listan los comandos de terminal utilizados, siguiendo el orden de la actividad:

sh

cd ~ #Descripción: Me posiciona en mi directorio de usuario antes de iniciar el proyecto.

mkdir python-final #Descripción: Crea la carpeta principal para este proyecto.

cd python-final

Descripción: Entra en la carpeta recién creada.
git init

Descripción: Inicializa un nuevo repositorio de Git en esta carpeta, permitiendo a Git
#empezar a rastrear y versionar los cambios en los archivos.

touch finales.py

Descripción: Crea un archivo Python vacío llamado finales.py dentro del proyecto.
code . #Descripción: Abre Visual Studio Code, cargando el directorio actual (python-final) #para poder editar los archivos del proyecto.

python -V y python3 -V #Descripción: Verifico las versiones de Python instaladas en el sistema. #(Mi versión detectada es Python 3.12.10).

python3 -m venv venv #Descripción: Crea un entorno virtual llamado venv dentro del proyecto. Esto aísla las dependencias y librerías de Python para este proyecto específico, evitando conflictos con otras instalaciones de Python o proyectos.

. venv/Scripts/activate

Descripción: Activa el entorno virtual en Git Bash (Windows). Una vez activado, el prompt
#de la terminal cambia para mostrar ((venv)), indicando que los comandos de Python #se ejecutarán dentro de este entorno aislado.

python3 -m pip install --upgrade pip #Descripción: Actualiza el gestor de paquetes pip dentro del entorno virtual. Esto
#asegura que pip esté en su versión más reciente (25.1.1) para una gestión eficiente y #segura de librerías.

Investigación sobre Pip
¿Qué es Pip?
Pip es el gestor de paquetes oficial de Python. Es la herramienta que nos permite instalar,
desinstalar y gestionar librerías y módulos de Python creados por terceros. Sirve como
un "repositorio" centralizado o una "tienda de aplicaciones" desde donde los programadores pueden
obtener herramientas pre-escritas para ampliar las capacidades de sus proyectos sin tener que
escribir todo el código desde cero.

¿Por qué lo actualizamos?
Actualizamos Pip regularmente por las siguientes razones:

Nuevas Funcionalidades y Mejoras: Cada nueva versión de Pip puede introducir mejoras
de rendimiento, nuevas características o una mayor facilidad de uso.
Corrección de Errores: Las actualizaciones solucionan fallos o "bugs" que pudieran
existir en versiones anteriores de Pip.
Compatibilidad: Para garantizar la compatibilidad con las últimas versiones de Python
y con las librerías más recientes, que a menudo requieren una versión actualizada de Pip
para su correcta instalación.
Seguridad: Las actualizaciones frecuentemente incluyen parches de seguridad importantes
que protegen el proceso de descarga e instalación de paquetes.
