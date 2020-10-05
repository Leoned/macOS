# macOS
Soluciones en macOS

## En macOS High Sierra
El problema es por el límite de huellas registradas en macOS High Sierra.

![image](https://user-images.githubusercontent.com/17074687/77921203-15217900-7265-11ea-83c3-7fea19e13107.png)

### Como eliminar las huellas existentes
* Reinicia o inicia tu Mac.
* Mientras se reinicia su Mac, mantenga presionadas las teclas Comando + R hasta que aparezca el logotipo de Apple.
* Cuando lo haga, suelte las teclas. Su Mac ahora ingresará al modo de recuperación; debería ver un panel de utilidades de macOS.
* Haga clic en Utilidades en la barra de menú superior.
* Seleccionar terminal .
* Una vez que se abre, escriba el siguiente comando en el terminal:  xartutil –erase-all
* Presione Entrar / Volver .
* Escriba yes en la terminal.

![image](https://user-images.githubusercontent.com/17074687/77921306-34b8a180-7265-11ea-8ca1-92d3f280f2ad.png)

_____________________________
# Reinstalar macOS
https://support.apple.com/es-cl/guide/mac-help/mchlp1599/mac

https://support.apple.com/es-lamr/HT204904

__________________________________
# Para restaurar usuario root y configurar modo de arranque de disco
Ingresar con, Comand + s

First Command:
mount -uw /

Second Command:
rm /var/db/.AppleSetupDone

Third Command:
reboot

# How to solve Download installer information to the target volume failed in Mac
Cuando se tenga descargado y sin embargo no se puede instalar, entonces hay que borrar

y cuando se descarga de vuela sale error

Abrir la terminal y escribir el siguiente comando: sudo softwareupdate --fetch-full-installer --full-installer-version 10.15.6
