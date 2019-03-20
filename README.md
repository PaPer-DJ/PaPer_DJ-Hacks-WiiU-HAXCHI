# PaPer_DJ-WiiU-Hacks-HAXCHI
Guía y Recursos para Hackear la Wii U - Instalar Custom Firmware basado en Coldboot Haxchi.

Esto es un Fork y Recopilación de recursos de: 
* https://wiiu.hacks.guide/es_ES/
* https://wiiu.hacks.guide/es_ES/vwii-modding
----------------------------------------------------------------

Lectura requerida
Con estos pasos prepararás tu tarjeta SD para instalar custom firmware basado en Coldboot Haxchi.

Antes de empezar, debes asegurarte de que tu Wii U posee el firmware de versión 5.5.0, 5.5.1, 5.5.2 o 5.5.3. Las versiones más antiguas no son compatibles actualmente.

Se recomienda que tu tarjeta SD sea de al menos 16GB o 32GB para tener espacio suficiente para volcar e instalar juegos. Si quieres hacer un respaldo del sistema de tu Wii U en caso de que quieras restaurarla en un futuro, necesitarás una tarjeta SD de al menos del doble del tamaño del sistema (una tarjeta SD de 16GB para la consola blanca de 8GB; una de 64GB para la consola negra de 32GB).

Tu tarjeta SD debe ser formateada como FAT32 (con un tamaño de unidad de asignación (Allocation Unit Size) de 32K (32768)). La mayoría de las tarjetas SD vendrán formateadas así por defecto.

Si necesitas formatear una tarjeta SD en Windows, no utilices el formateador incorporado porque podría causar problemas. Mejor usa guiformat y define un tamaño de unidad de asignación (Allocation Unit Size) de 32K (32768)).

Tu tarjeta SD no puede llamarse wiiu, o causará problemas.

¡Antes de empezar, deberías comprobar si tu tarjeta SD tiene errores usando H2testw (Windows),F3 (Linux), o F3X (Mac)!

Qué necesitas
config.txt
config.ini
La última versión de Homebrew App Store
La última versión de WUP Installer GX2
La última versión de disc2app
La última versión de hid_to_vpad
La última versión de Mocha CFW
La última versión de savemii_mod
La última versión del Homebrew Launcher Channel (el archivo .zip que dice “channel”)
Una versión anterior (v1.3) del Homebrew Launcher (el archivo .zip del launcher)
La última versión de Wii U NAND Dumper
Las últimas versiones de Haxchi y CBHC (los dos archivos .zip)
La última versión de NNU-Patcher
Instrucciones
Sección I - Preparativos
Apaga tu consola
Inserta tu tarjeta SD en tu computadora
Crea una carpeta llamadawiiu en la raíz de tu tarjeta SD
Crea una carpeta llamadainstall en la raíz de tu tarjeta SD
Copia la carpeta apps desde el .zip de Homebrew App Store a la carpeta /wiiu/ en tu tarjeta SD
Copia el contenido del .zip del Homebrew Launcher (v1.3) a la raíz de tu tarjeta SD
Copia el contenido del .zip de Haxchi a la raíz de tu tarjeta SD
Copia el contenido del .zip de CBHC a la raíz de tu tarjeta SD
Copia config.txt a la carpeta /haxchi/ de tu tarjeta SD (sobreescribe el archivo config.txt ya existente)
Crea una carpeta llamada hbc en la carpeta /install/ de tu tarjeta SD
Copia el contenido del .zip del Homebrew Launcher Channel a la carpeta /install/hbc/ en tu tarjeta SD
Copia la carpeta savemii_mod del .zip de savemii_mod a la carpeta /wiiu/apps/ de tu tarjeta SD
Copia el contenido del .zip de WUP Installer GX2 a la raíz de tu tarjeta SD
Copia el contenido del .zip de disc2app a la raíz de tu tarjeta SD
Copia el contenido del .zip de hid_to_vpad a la raíz de tu tarjeta SD
Copia el contenido del .zip de NNU-Patcher a la raíz de tu tarjeta SD
Copia el contenido del.zip de Wii U NAND Dumper en la raíz de tu tarjeta SD
Copia el contenido del .zip de Mocha CFW a la raíz de tu tarjeta SD
Copia config.ini a la carpeta /wiiu/apps/mocha/ de tu tarjeta SD
Reinserta la tarjeta SD en tu consola
Enciende tu consola
Sección II - Juego de la consola virtual de DS
Hay dos métodos para usar custom firmware para Wii U.

El primer método es ejecutar un exploit del navegador que te permitirá modificar el sistema. Lamentablemente, la naturaleza de este exploit implica que debe ser ejecutado luego de cada reinicio.

La segunda opción consiste en comprar un juego de la consola virtual de DS barato y vulnerable para ejecutar Custom Firmware automáticamente al encender la consola.

El juego de consola virtual de DS debe ser una copia legítimamente comprada del juego instalada en la memoria interna de tu consola. No puedes instalar este juego de consola virtual de DS en una unidad USB.

Si quieres usar el método de la consola virtual de DS, deberías comprar el juego antes de pasar a la siguiente sección.

Los siguientes juegos de consola virtual de DS son compatibles:

Juegos compatibles con Haxchi
Animal Crossing: Wild World
Big Brain Academy
Brain Age
DK: Jungle Climber
Dr. Kawashima’s Brain Training
Kirby: Canvas Curse
Kirby: Mass Attack
Kirby: Squeak Squad / Kirby: Mouse Attack
Legend of Zelda: Phantom Hourglass
Legend of Zelda: Spirit Tracks
Mario & Luigi: Partners in Time
Mario Kart DS
New Super Mario Bros.
Pokemon Mystery Dungeon: Explorers of the Sky
Pokemon Ranger
Pokemon Ranger: Guardian Signs
Pokemon Ranger: Shadows of Almia
Starfox Command
Super Mario 64 DS
Wario: Master of Disguise
WarioWare: Touched
Yoshi’s Island DS
Yoshi’s Touch & Go
Actualmente, Brain Age es el más barato de todos en la eShop ($6.99 USD).

Si ya posees Brain Age o Brain Training y lo tenías instalado en tu Wii U de antes, prueba a borrarlo y a descargarlo nuevamente desde la eShop. Las versiones anteriores a la actual de este juego no son compatibles con el exploit.

-----------------------------------------------------------------------

Homebrew Launcher
Para soporte en inglés, pide ayuda en el Discord de Nintendo Homebrew.
Si aprecias esta guía, aceptamos donaciones.

 

 
 TABLA DE CONTENIDOS
LECTURA REQUERIDA
INSTRUCCIONES
SECCIÓN I - PREPARAR EL NAVEGADOR
SECCIÓN II - HOMEBREW LAUNCHER
MÉTODOS
MOCHA CFW
CONTINÚA A MOCHA CFW
HAXCHI
CONTINÚA A HAXCHI
Lectura requerida
El Homebrew Launcher es una aplicación casera que muestra una lista y permite el inicio de otras aplicaciones caseras presentes en la tarjeta SD.

Para iniciarlo usaremos el navegador de Internet incorporado en la Wii U, por lo cual tu consola Wii U requerirá de acceso a Internet.

Instrucciones
Sección I - Preparar el navegador
Inicia el navegador de tu consola
Ve a la configuración del navegador y selecciona “Borrar Datos”
Esto evitará problemas con el exploit
Esto también eliminará todos los datos que involucran configuración, historial de navegación y favoritos
Regresa al navegador
Sección II - Homebrew Launcher
Si tu consola está en versión de firmware 5.5.2 o 5.5.3, abre las cortinas del navegador
Esto aumenta la tasa de éxito del exploit de navegador para la 5.5.2/5.5.3
Ve a usploit.hacks.guide
Conviene que añadas esta dirección a favoritos para ahorrar el tiempo de escribirla en el futuro
Selecciona “Run Homebrew Launcher” para el primer intento de ejecutar el exploit
Esto puede tomar varios intentos
Si se congela, fuerza el apagado de la consola manteniendo presionado el botón de apagado y luego intenta el proceso de nuevo
Tu consola debería cargar el Homebrew Launcher
Métodos
Mocha CFW
Este método requiere que vuelvas a ejecutar el exploit web utilizado anteriormente después de cada reinicio.

Continúa a Mocha CFW
Haxchi
Este método utiliza un juego de la consola virtual de DS barato y vulnerable para ejecutar Custom Firmware automáticamente al encender la consola.

-------------------------------------------------------------------

Mocha CFW
Para soporte en inglés, pide ayuda en el Discord de Nintendo Homebrew.
Si aprecias esta guía, aceptamos donaciones.

 

 
 TABLA DE CONTENIDOS
LECTURA REQUERIDA
QUÉ NECESITAS
INSTRUCCIONES
CONTINÚA EN HOMEBREW LAUNCHER (CHANNEL).
Lectura requerida
Mocha CFW es un custom firmware que modifica la verificación de firmas y de región, así como habilita otras funciones de custom firmware.

Para poder utilizar Mocha CFW, necesitarás acceder al Homebrew Launcher a través del navegador y ejecutar Mocha CFW cada vez que reinicies la consola.

Qué necesitas
El archivo personalizado config.ini provisto en Comencemos debería estar ya en la carpeta /wiiu/apps/mocha/ de tu tarjeta SD
Instrucciones
Inicia Mocha CFW
La consola regresará al Homebrew Launcher y habilitará las funciones de custom firmware
Esto permitirá que títulos sin firmar (como el Homebrew Launcher) puedan ser ejecutados directamente desde el menú del sistema hasta el próximo reinicio
Ten en cuenta que necesitarás ejecutar Mocha CFW desde el Homebrew Launcher cada vez que reinicies para activar las características de custom firmware.

--------------------------------------------------------------------

Lectura requerida
Esto instalará el Homebrew Channel y, mientras se utilice Custom Firmware, el Homebrew Launcher aparecerá como un ícono en el menú del sistema.

Instrucciones
Sección I - Instalar el Homebrew Launcher Channel
Ingresa al Homebrew Launcher
Los usuarios de CBHC deben presionar (Home) mientras CBHC está iniciando para acceder al menú de opciones de inicio de CBHC y luego selecciona Homebrew Launcher
Los usuarios de Haxchi deben iniciar Haxchi una vez para habilitar el custom firmware, luego ejecutarlo una segunda vez manteniendo presionado (A) para iniciar el Homebrew Launcher
Usuarios de Mocha CFW deberían ya haber ingresado en éste
Inicia WUP Installer GX2
Ten en cuenta que si WUP Installer GX2 crashea con el error “DSi Exception Has Ocurred”, tan solo deberías apagar la consola y volver a intentar.
Selecciona el Homebrew Channel
Presiona “Install”, luego presiona “Yes” para confirmar
Selecciona “NAND” como destino
Presiona (Home), luego cierra el programa para salir del instalador una vez que haya terminado
Sección II - Bloquear actualizaciones del sistema
Ten en cuenta que para acceder a la eShop con estas direcciones DNS configuradas, primero debes ejecutar NNU-Patcher desde el Homebrew Launcher. Adicionalmente ten en cuenta que NNU-Patcher es una modificación temporal que debe ser ejecutada nuevamente para acceder a la eShop luego de reiniciar.

Ten en cuenta que, a menos que bloquees las actualizaciones con este método en todas las conexiones actuales y futuras, las actualizaciones en la Wii U se realizan automáticamente y no pueden ser desactivadas.

Ve a las “Configuraciones de la consola”, luego a “Internet”, luego “Conexión a internet” y presiona (X) para mostrar tus configuraciones de red actuales
Para cada conexión (y todas las futuras conexiones), haz lo siguiente
Selecciona la conexión
Selecciona “Cambiar configuración”
Ve a la segunda lista y selecciona “DNS”
Configura el DNS a “Modo manual”
Configura las IP’s de servidores DNS a las siguientes
168.235.092.108
081.004.127.020
Selecciona “Confirmar” y presiona (B) para guardar
Estos servidores bloquearán las actualizaciones en tu consola
Ahora puedes iniciar el Homebrew Launcher desde custom firmware simplemente iniciando el Homebrew Channel.

Ten en cuenta que para acceder a la eShop con los las direcciones DNS que bloquean las actualizaciones, antes debes iniciar NNU-Patcher desde el Homebrew Launcher (NNU-Patcher es un parche temporal y tendrás que iniciarlo después de cada reinicio para entrar a la eShop).

Para informarte acerca de cómo volcar los datos de tus discos de juego a un formato instalable para jugar sin necesidad del disco, echa un vistazo al apartado de disc2app.

Para informarte acerca de cómo modificar la vWii en custom firmware, echa un vistazo al apartado de Modear la vWii.

Para informarte acerca de cómo desinstalar el CFW de forma segura y regresar la consola a su estado original, echa un vistazo al apartado de Desinstalar CFW.

------------------------------------------------------------------
------------------------------------------------------------------

Modeo de vWii
 
 TABLA DE CONTENIDOS
LECTURA REQUERIDA
QUÉ NECESITAS
INSTRUCCIONES
SECCIÓN I - PREPARATIVOS
SECCIÓN II - WUPHAX
SECCIÓN III - VOLCAR LA NAND DE LA VWII
SECCIÓN IV - INSTALACIÓN DE CIOS
SECCIÓN V - PARCHEAR EL IOS80

Lectura requerida
Esto te permitirá instalar el Homebrew Channel y realizar otras modificaciones en la vWii (Wii virtual) de tu Wii U.

Qué necesitas
vWii_cIOS_apps_20131218.zip
Patched_IOS80_Installer_for_vWii.zip
La última versión de WUPhax
La última versión del Hackmii Installer
Una versión anterior del Homebrew Launcher (el archivo .zip del launcher)
Instrucciones
Sección I - Preparativos
Apaga tu consola
Inserta tu tarjeta SD en tu computadora
Copia el contenido del .zip de WUPhax a la raíz de tu tarjeta SD
Copia boot.elf desde la carpeta hackmii_installer_v1.2 del .zip de Hackmii Installer a la raíz de tu tarjeta SD
Copia la carpeta apps desde vWii_cIOS_apps_20131218.zip a la raíz de tu tarjeta SD
Copia la carpeta apps de Patched_IOS80_Installer_for_vWii.zip a la raíz de tu tarjeta SD
Copia el contenido del .zip del Homebrew Launcher a la raíz de tu tarjeta SD
Reinserta la tarjeta SD en tu consola
Enciende tu consola
Sección II - wuphax
Inicia el Homebrew Launcher
Si aún no has hecho la guía principal de Wii U y no sabes cómo hacer esto, por favor sigue Homebrew Launcher, luego vuelve a esta página.
Inicia wuphax
Presiona (A) para hacer una copia de seguridad de tu Canal Mii e inyectar Hackmii Installer
Se regresará al Homebrew Launcher
Utiliza el botón (Home) para salir al menú del sistema
Inicia la vWii
Inicia el Canal Mii en la vWii
Si el exploit fue exitoso, habrás ingresado al Hackmii Installer
Lee la advertencia de estafa y luego presiona (1) para continuar cuando se te pida
Sigue las instrucciones en pantalla para instalar el Homebrew Channel en la vWii
Sigue las instrucciones para regresar a la vWii
Si el exploit fue exitoso, verás el Homebrew Channel en el Menú de vWii
Regresa al menú del sistema y luego apaga tu consola
Inicia el Homebrew Launcher con el método utilizado anteriormente en esta sección
Inicia wuphax
Presiona (B) cuando se te pida para restaurar el Canal Mii
Sigue las instrucciones para regresar a la vWii
Sección III - Volcar la NAND de la vWii
Esta copia de seguridad de la NAND te permitirá restaurar tu vWii a un estado funcional en caso de que algo salga mal.

Inicia el Homebrew Channel en la vWii
Inicia Dump Mii NAND
Prepárate para esperar; esto puede tomar un buen tiempo (hasta varias horas dependiendo del espacio que ocupa tu memoria interna)
Cuando haya terminado, tu Wii U se reiniciará automáticamente
Apaga tu Wii U
Introduce la tarjeta SD de tu Wii U en tu computadora
Copia los archivos nand.bin y keys.bin desde la raíz de tu tarjeta SD a un lugar seguro en tu computadora y haz varias copias de seguridad en distintos sitios (tales como almacenamiento de archivos en la nube); esto permitirá salvar tu vWii de un brick en caso de que algo salga mal
Borra los archivos nand.bin y keys.bin del directorio raíz de tu tarjeta SD
Sección IV - Instalación de cIOS
Asegúrate que no hay ninguna carpeta llamada wad o wads en el directorio raíz de tu tarjeta SD y que no hay otros archivos .wad en ningún lado excepto en la carpeta /apps/ dentro de la tarjeta SD.

Inicia el Homebrew Channel en la vWii
Inicia d2x cIOS Installer
Elige las opciones en la parte superior de la pantalla acorde a lo siguiente:
Selecciona cIOS : d2x-v10-beta52-vWii
Selecciona cIOS base : 56
Selecciona cIOS slot : 249
Presiona (A) para instalar
Espera a que la instalación se complete y luego presiona (A) para continuar
Elige de nuevo las opciones en la parte superior de la pantalla acorde a lo siguiente:
Selecciona cIOS : d2x-v10-beta52-vWii
Selecciona cIOS base : 57
Selecciona cIOS slot : 250
Presiona (A) para instalar
Espera a que la instalación se complete y luego presiona (A) para continuar
Elige de nuevo las opciones en la parte superior de la pantalla acorde a lo siguiente:
Selecciona cIOS : d2x-v10-beta52-vWii
Selecciona cIOS base : 58
Selecciona cIOS slot : 251
Presiona (A) para instalar
Espera a que la instalación se complete y luego presiona (B) para salir
Sección V - Parchear el IOS80
Este paso brickeará tu vWii si llega a fallar por alguna razón (apagones, etc), tras lo cual se deberá restaurar una copia de seguridad de la memoria NAND de la vWii. Asegúrate de tener tu copia de seguridad hecha antes de proseguir con esta sección.

Desde el Homebrew Channel en la vWii, inicia Patched IOS80 Installer for vWii
Lee la advertencia, luego espera 30 segundos para que te permita continuar
Presiona (A) para instalar
Esto debería ser muy rápido
Cuando haya terminado, presiona cualquier botón para regresar al Homebrew Channel
Sal al Menú de vWii
Ahora puedes instalar y usar cualquier homebrew de Wii, tales como USB Loader GX, CFG USB Loader, emuladores, etc.

Los discos duros externos deben ser conectados en el puerto USB superior trasero de la Wii U para ser detectados por la vWii. Este no puede ser el mismo disco duro externo que uses para juegos de Wii U. Si estás usando un disco duro externo que no tiene fuente de alimentación propia, entonces necesitarás un cable Y.

Asegúrate que cualquier archivo .wad (canales, forwarders, juegos, etcétera) que instales estén formateados para funcionar apropiadamente en vWii. Si instalas un archivo .wad formateado para una consola Wii común, brickearás la vWii tras lo cual se deberás restaurar una copia de seguridad de la NAND de la vWii.

Instalar temas personalizados en tu vWii la brickeará.

Remover archivos .wad manualmente sin saber lo que estás haciendo brickeará tu vWii.

Instalar Priiloader brickeará tu vWii.

