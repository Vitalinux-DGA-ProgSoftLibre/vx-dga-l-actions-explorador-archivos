# vx-dga-l-actions-explorador-archivos
Acciones o Action Scripts personalizados accesibles pulsando con el botón derecho del ratón sobre un elemento del Explorador de Archivos

# Usuarios/Equipos Destinatarios

Paquete obligatorio para los equipos Vitalinux DGA. 

# Aspectos Interesantes

Funciona sin necesidad de instalar dependencias en la mayoría de los Exploradores de Archivos Linux, como **pcmanfm**, aunque para que este paquete pueda funcionar en Nautilus es necesario instalar el paquete **nautilus-actions**.

Funcionalidades más destacadas que integra:

1. Crear un acceso directo o lanzador en el Escritorio para directorios o carpetas
2. 

# Como Crear el paquete DEB a partir del codigo de GitHub
Para crear el paquete DEB será necesario encontrarse dentro del directorio donde localizan los directorios que componen el paquete.  Una vez allí, se ejecutará el siguiente comando (es necesario tener instalados los paquetes apt-get install debhelper devscripts):

```
apt-get install debhelper devscripts
/usr/bin/debuild --no-tgz-check -us -uc
```
En caso de no querer crear el paquete para tu distribución, si simplemente quieres obtenerlo e instalarlo, puedes hacer uso del que está disponible para Vitalinux (*Lubuntu 14.04*) desde el siguiente repositorio:

[Respositorio de paquetes DEB de Vitalinux](http://migasfree.educa.aragon.es/repo/Lubuntu-14.04/STORES/base/)

# Como Instalar el paquete generado vx-dga-l-scripts*.deb:
Para la instalación de paquetes que estan en el equipo local puede hacerse uso de ***dpkg*** o de ***gdebi***, siendo este último el más aconsejado para que se instalen también las dependencias correspondientes.
```
gdebi vx-dga-l-explorador-archivos*.deb
```
