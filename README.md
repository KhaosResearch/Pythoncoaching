Pythoncoaching
===================


<i class="icon-download"></i>Clonar con Pycharm
-------------


- En el IDE Pycharm > VCS > Checkout form version control > Github:
	URL del repositorio:  https://github.com/KhaosResearch/Pythoncoaching.git
- Crear entorno virtualenv en el proyecto:
	- File > settings > Buscar 'Project Interpreter'. Pulsar en 'create virtualenv'.
	- En la nueva ventana que se abre, poner como nombre 'env' por ejemplo. En el campo 'location' ubicarlo dentro del directorio del proyecto y elegir el interprete python3. Pulsar 'Ok'.
	- Ya se ha creado el entorno virtual del proyecto. En la misma ventana, aparece el listado de dependencias. Vemos que por defecto virtualenv ha instalado 3 paquetes: pip, setuptools y wheel. Actualizar los 3 a la ultima versión: seleccionarlos y pulsar en el botón de flecha hacia arriba.
	- Pulsar en 'Aplicar' y luego en 'Ok'.
- Instalar dependencias
	- Abrir el terminal de Pycharm pulsando en ALT + F12. Situarse en el directorio del proyecto si no lo está.
	- Acceder al entorno virtual del proyecto:
		source venv//bin/activate
	- Instalar las dependencias definidas en requirements.txt:
	 	pip freeze > requirements.txt