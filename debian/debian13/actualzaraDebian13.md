# Actualiza Debian 12 a Debian 13
## Importante

Hacer una copia de seguridad: antes de iniciar el proceso de actualización para evitar pérdida de datos.

Verificar la compatibilidad: de los paquetes y aplicaciones instaladas para evitar problemas durante la actualización.

Leer las notas de la versión: de Debian 13 para conocer los cambios y requisitos específicos.

Siguiendo estos pasos, podrás actualizar tu sistema Debian 12 a Debian 13 de manera segura y efectiva.

## Pasos para actualización a Debian 13
Actualiza tu sistema actual: 
```
sudo apt update && sudo apt upgrade
```

Modifica el archivo sources.list: reemplaza "bookworm" por "trixie" utilizando
```
sudo sed -i 's/bookworm/trixie/g' /etc/apt/sources.list
```
Realiza una actualización mínima: 
```
sudo apt upgrade --without-new-pkgs
```
Realiza una actualización completa: 
```
sudo apt full-upgrade
```
Reinicia tu sistema: 
```
sudo reboot
```
