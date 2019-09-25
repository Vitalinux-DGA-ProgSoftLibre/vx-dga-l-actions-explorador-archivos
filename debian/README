# vx-dga-l-actions-explorador-archivos
Acciones o Action Scripts personalizados accesibles pulsando con el botón derecho del ratón sobre un elemento del explorador de archivos

# Usuarios/Equipos Destinatarios

Paquete obligatorio para los equipos Vitalinux DGA. 

# Aspectos Interesantes
```
Funciona sin necesidad de instalar dependencias en la mayoría de los Exploradores de Archivos Linux, como pcmanfm.
Para que este paquete pueda funcionar en Nautilus es necesario instalar el paquete nautilus-actions.
```
# Como Crear el paquete DEB a partir del codigo de GitHub
Para crear el paquete DEB será necesario encontrarse dentro del directorio donde localizan los directorios que componen el paquete.  Una vez allí, se ejecutará el siguiente comando (es necesario tener instalados los paquetes apt-get install debhelper devscripts):

```
apt-get install debhelper devscripts
/usr/bin/debuild --no-tgz-check -us -uc
```

# Como Instalar el paquete generado vx-dga-l-scripts*.deb:
Para la instalación de paquetes que estan en el equipo local puede hacerse uso de ***dpkg*** o de ***gdebi***, siendo este último el más aconsejado para que se instalen también las dependencias correspondientes.
```
gdebi vx-dga-l-explorador-archivos*.deb
```
