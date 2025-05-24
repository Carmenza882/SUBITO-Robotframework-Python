AUTOMATIZACION DE PRUEBAS A FUNCIONALIDADES SUBITO WEB
python -m pip install --upgrade pip ## ROBOTFRAMEWORK - PYTHON

# DESCRPCION
Este proyecto es con el fin de ejecutar casos de pruebas.
Subito es una plataforma online de compra,venta y alquiler en Italia que permite al usuario por medio del motor de busqueda de  publicar anuncios para vender,comprar y alquilar  inmuebles.
Este proyecto es con el fin de aprender el uso de  framework Robot Framework


## . CARACTERISTICAS
El usuario va en busca de la opcion de interes, cuàndo encuentra su opciòn deseada procede a crear el anuncio adecuado con todos los dactos requeridos,en caso contrario contacta a la persona que ha creado el anuncio para ver si logran comercializar el inmueble.

# Tecnologias utilizadas

Python:  Es un lenguaje de programaciòn de alto nivel

SeleniumLibrary:  Es una opciòn para interactuar con pàginas web(simula interacciones humanas como hacer clic)

Robot Framework: Marco de automatizaciòn de prueba de còdigo abierto.(facilita la creaciòn y ejecuciòn de pruebas automatizadas)


PIP:  Es una herramienta de linea de comandos,que facilita la instalaciòn ,actualizaciòn y desinstalaciòn de paquetes de python

* [Python](https://www.python.org/downloads/)
* [Selenium](https://robotframework.org/SeleniumLibrary/)
* [Robot Framework](https://robotframework.org)
* [PIP](https://www.groovypost.com/howto/install-pip-on-a-mac/)

## Requisitos
Visual Studio Code instalado
Python instalado
Robot Framework instalado
PIP actualizado

#INSTALACION

# Para instalar el  proyecto se debe realizar las siguientes instrucciones
1 Ingresar a la consol de cmder y ejecutar los siguientes comandos:
python -m pip install --upgrade pip
pip install robotframework o pip3 install robotframework
pip3 install robotframework-seleniumlibrary
pip3 install robotframework-selenium2library

2 Para ejecutar las pruebas
 -Identificar en que carpeta del proyecto de visual studio,se encuentran los casos de prueba
 -Abrir el proyecto desde visual studio.  
 Abrir una nueva terminal a travès de la  siguiente ruta:
 - Ir a la terminal > New Terminal.
 -Ingrsamos en la ruta del directorio hasta llegar a la carpeta en dònde estàn los casos de prueba usando el comando cd.
 - Ejecutar un caso de prueba con el siguiente comando: robot + nombre del archivo de prueba+.robot.
El informe HTML generado estará disponible en:```""C:\Users\giaqu\Desktop\AUTOMATIZACION\Netflix_RobotFramework-main\Netflix\specs\report.html"

### Reporte de ejecucion
Robot Framework genera un reporte detallado donde podrá ver:
Casos ejecutados
Resultados (éxito o fallo)
Mensajes de error y logs
Estadísticas por test suite y por test case
