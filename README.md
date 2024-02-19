# enso-controlCambios

Práctica de ENSO, que consiste en definir el proceso de control de cambios para un proyecto software.

## Estructura del repositorio:

El esqueleto de este repositorio está asociado al proyecto software que se desarrolla, con la presencia del proceso de gestión de cambios. Se ha creado esta estructura base con la posibilidad de ser modificada y ampliada con el crecimiento del proyecto y en beneficio de un mejor funcionamiento. La rama principal cuenta con tres carpetas iniciales, de las cuales “Documentos_Proceso” hace referencia al almacenamiento y gestión de los archivos que especifican el proceso de control de cambios, en los que se incluye el desarrollo de las plantillas previamente mencionadas. Por otro lado, la carpeta “Proyecto” almacena todos archivos producidos en el desarrollo del proyecto software utilizado como supuesto. Por último, la carpeta “Cambios” contiene toda la información asociada a cada cambio y permite la ejecución del proceso de gestión de cambios. Cada vez que se recibe una solicitud de cambio se lleva a cabo el siguiente proceso:

1.	En la rama principal, se crea una carpeta exclusiva para el cambio en la carpeta “Cambios” denominada “Cambio_IDcambio”, cuyo identificador sea único entre todos los cambios del proyecto. Esta contendrá la carpeta “plantillas”, cuya estructura se describe en la sección de Definición de actividades y la plantilla “Solicitud de cambio” en la subcarpeta “completas”.
2.	Se crea una rama del repositorio específica para el cambio, que contiene los archivos en ese momento concreto del desarrollo del proyecto, de forma que la rama principal guarda constancia de la recepción del nuevo cambio. Existirá por tanto una rama activa por cada cambio activo del proyecto. Esto permitirá implementar los requisitos del cambio en una versión nueva de la línea base de forma paralela con otros cambios.
3.	El proceso de control de este cambio se realiza en esta nueva rama modificando los archivos de la carpeta asociada con las operaciones pertinentes de Git.
4.	En la fase de inclusión del cambio, una vez se ha verificado su correcta adhesión al proyecto, se combinan esta rama y la rama principal para incluir el cambio en la línea base y generar así una nueva versión. De este modo, se cierra el proceso de gestión del cambio y la rama finaliza su actividad.


