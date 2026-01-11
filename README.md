Este repositorio contiene los ficheros generados durante la realización de la práctica de la asignatura Sistemas Informáticos, correspondiente a los apartados 
sobre auditoría de espacio en disco y variables de entorno en GNU/Linux (Ubuntu) y Windows 11.

El objetivo es documentar los resultados obtenidos mediante comandos en consola, tal como se indica en las instrucciones de la práctica. Los ficheros incluyen 
las listas completas de variables de entorno exportadas desde cada sistema operativo.

Archivos incluidos

variables_linux.txt: Fichero generado en Ubuntu mediante el comando set > variables_linux.txt. Contiene todas las variables de entorno definidas en la sesión de Bash, 
incluyendo las específicas anotadas en el apartado 3.1 (SHELL, HOME, USER, PATH, PS1, HOSTNAME, LOGNAME y LANG).

Env-Windows.csv: Fichero generado en Windows 11 mediante PowerShell con el comando Get-ChildItem Env: | Select-Object Name, Value | Export-Csv -Path Env-Windows.csv 
-NoTypeInformation -Encoding UTF8. Contiene todas las variables de entorno del sistema, en formato CSV, incluyendo las específicas anotadas en el apartado 3.2 
(HOMEPATH, USERNAME, USERDOMAIN y SystemDrive).

Instrucciones de generación

En Ubuntu: Se accedió a la terminal y se ejecutó set | less para visualizar, seguido de set > variables_linux.txt para exportar.
En Windows: Se abrió PowerShell y se ejecutó Get-ChildItem Env: | more para visualizar, seguido del comando de exportación a CSV.

Estos ficheros se utilizan como evidencia de los comandos ejecutados y los resultados obtenidos. Para más detalles, consultar el documento PDF principal de la práctica.
Autor

Nombre: Robert Bica Moya
Fecha: 11/01/2026
