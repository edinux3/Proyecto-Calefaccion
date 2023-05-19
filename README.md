# Proyecto-Calefaccion

Pasos para instalar Raspbian y Node-RED en tu Raspberry Pi, a fin de diseñar un sistema de calefacción automatizado:

1. Descarga Raspbian: Visita el sitio web oficial de Raspberry Pi (www.raspberrypi.org) y descarga la última versión de Raspbian, un sistema operativo diseñado específicamente para la Raspberry Pi.

2. Prepara la tarjeta SD: Utiliza un programa como Etcher para escribir la imagen de Raspbian en una tarjeta SD. Asegúrate de seleccionar correctamente la tarjeta SD y la imagen descargada de Raspbian.

3. Configura la Raspberry Pi: Inserta la tarjeta SD en la Raspberry Pi y enciéndela. Sigue las instrucciones de configuración inicial, como seleccionar el idioma, ajustar la contraseña y conectarte a una red Wi-Fi.

4. Actualiza el sistema: Una vez que hayas completado la configuración inicial, abre una terminal y ejecuta los comandos `sudo apt update` y `sudo apt upgrade` para asegurarte de que el sistema esté actualizado.

5. Instala Node.js: Node-RED requiere Node.js para ejecutarse. Instala Node.js en tu Raspberry Pi ejecutando el comando `sudo apt install nodejs`.

6. Instala Node-RED: Luego de haber instalado Node.js, ejecuta el comando `sudo npm install -g --unsafe-perm node-red` para instalar Node-RED de forma global en tu sistema.

7. Inicia Node-RED: Una vez finalizada la instalación, ejecuta el comando `node-red` en la terminal para iniciar el servidor de Node-RED. El servidor se ejecutará en el puerto 1880 de forma predeterminada.

8. Accede a Node-RED: Abre un navegador web en tu computadora y visita la dirección IP de tu Raspberry Pi seguida de `:1880`. Por ejemplo, si la dirección IP de tu Raspberry Pi es 192.168.1.10, ingresa "192.168.1.10:1880" en el navegador.

9. Diseña el sistema de calefacción: Utiliza la interfaz gráfica de Node-RED para diseñar y programar el sistema de calefacción automatizado. Puedes arrastrar y soltar nodos, conectarlos entre sí y configurar sus propiedades según tus necesidades.

10. Descarga el flows.json e importalo. desde el dashboard.

