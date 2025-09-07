# Actualiza Debian 11 a Debian 12
## Importante

Hacer una copia de seguridad: antes de iniciar el proceso de actualización para evitar pérdida de datos.

Verificar la compatibilidad: de los paquetes y aplicaciones instaladas para evitar problemas durante la actualización.

Leer las notas de la versión: de Debian 12 para conocer los cambios y requisitos específicos.

Siguiendo estos pasos, podrás actualizar tu sistema Debian 11 a Debian 12 de manera segura y efectiva.

## Pasos para actualización a Debian 12

Actualiza los repositorios: 
```
sudo apt update
```
Actualiza los paquetes: 
```
sudo apt upgrade y sudo apt full-upgrade
```
Modifica el archivo sources.list: reemplaza "bullseye" por "bookworm" utilizando
```
sudo sed -i 's/bullseye/bookworm/g' /etc/apt/sources.list
```
Actualiza nuevamente:
```
sudo apt update y sudo apt full-upgrade
```
Reinicia tu sistema: 
```
sudo reboot
```
