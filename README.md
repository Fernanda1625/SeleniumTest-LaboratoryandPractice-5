# Selenium WebDriver
WebDriver es una herramienta para automatizar las pruebas de aplicaciones web. Usa un marco subyacente diferente, e interactúa directamente con el navegador sin ningún intermediario.
## Requisitos 
### Eclipse
Vamos a: https://www.eclipse.org/downloads/packages/release/mars/r/eclipse-ide-java-ee-developers y descargamos la versión adecuada para nuestro sistema.
### Java 11+
Para usar Selenium podemos tener Java 8, pero debido a que lo configuraremos en Eclipse, es necesario tener Java 11 o alguna versión posterior. Para instalarlo debemos ir a: https://www.oracle.com/java/technologies/javase-downloads.html
### GeckoDriver
Descargamos Geckodriver desde Github: https://github.com/mozilla/geckodriver/releases.
Elegimos la versión que corresponda con nuestro Sistema Operativo, descomprimimos el .zip, y configuramos las variables de entorno del sistema, colocando el directorio en el que se encuentre nuestro geckodriver.exe, esto para no establecer la propiedad System cada vez que tengamos un script de prueba: (System.setProperty("webdriver.gecko.driver","C:\\carpeta\\geckodriver.exe");)
## Scripts de prueba
A continuación se muestran los atributos que se obtienen de la página web que usaremos de prueba:
![Scheme](img/script1.png)
## Resultados
Los resultados de ejecutar el script de prueba serian:
![Scheme](img/script2.png)

## JUnit
Integramos JUnit para verificar los resultados de ejecución de pruebas:
![Scheme](img/script3.PNG)

### Asserts
Usamos Asserts para verificar el resultado de los test:
![Scheme](img/script4.png)
