# Amazon_Qa_Automation
Prueba de habilidades para automatización OrionTek

## Breve descripción del proyecto

En el siguiente proyecto presento algunas de mis habilidades de automatizados enfocado a la funcionalidad y analisis de los problemas ,para automatizar algunos de los escenarios y casos de prueba que se pueden encontrar en la pagina de amazon.

En el test-sscript presentado se solucionan los casos de pruebas presentados en el docuemento "Documentacion de prueba" ubicado en la carpeta de "Documentacion".

### Preparativos

Requsitos para poder correr los Test-Scripts(Aclarando que tales herramientas seran econtradas en el repositorio mismo):
  - Python 3.8.2
  - GoogleChrome version 77.0.3865.75
  - chromedriver_win32 con su version  77
  
Instalación

Debemos descomprimir el archivo rar,preparando el ambiente debemos de instalar las herramientas en el sistema que se encuentran en una carpeta con ese mismo nombre:

## Instalar
- Python 3.8.2.
- GoogleChrome version 77.0.3865.75.

Instalar los modulos para poder correr el script:
1. Abrimos una consola del sistema(Tecleamos CMD en la barra de busqueda del inicio)
2. Instalamos los paquetes usados por python en este script:
  - pip install selenium
  - pip install pyautogui
  - pip install HtmlTestRunner
3. Esperamos que se instalen corriendo cada comando individualmente.
4. Descargar el repositorio en formato "*.rar" en su estacion de trabajo y lo hubicamos pegamos en una carpeta vacia
5. Descrompimimos el archivo "*.rar"

## Correr el script de prueba

Para correr el script de prueba debemos ubicarnos en la carpeta que descomrpimimos:
1. Seleccionamos con un click derecho el archivo "app.py"

![Abrir con Idle](https://user-images.githubusercontent.com/59577641/83972364-03e98e00-a8e0-11ea-8ff3-14b241f75c45.PNG)

2. Abrimos el archivo "app.py" con el editor "IDLE"
3. Una vez abierto el script seleccionamos la opcion "Run" en la barra de herramientas
4. Seleccionamos la opcion "Run Module"
![RunModule](https://user-images.githubusercontent.com/59577641/83972367-0e0b8c80-a8e0-11ea-94e7-90952e7222e1.PNG)

5. Y el script comenzara a ejecutar.

## Obseraciones
Aqui algunas funcionalidades adicionales del script:

- En caso de exista un captcha al ingresar a la pagina el script le pedira asistencia al automatizador por motivo de seguridad.
- Al final de la corrida el script tomara una ScreenShot de los articulos seleccionados y lo guardara con el nombre de "Confirmacion de Articulos" en la careta donde se encuentra.
- al final de la corrida el script generara un reporte con los resultados de la corrida y lo guardara en un carpeta llamada "Resultado de mi caso de prueba"



## Authors

**Luis Legreaux** - Amazon Automation -(https://github.com/LuisLegreaux39)

