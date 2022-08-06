# Laboratorio1

# Prerequisitos
1. Descargar WinSCP: https://winscp.net/eng/download.php

WinSCP (Windows Secure Copy) es un protocolo de transferencia de archivos SSH (SFTP), un protocolo de transferencia de archivos (FTP), WebDAV, Amazon S3 y un cliente de protocolo de copia segura (SCP) gratuito y de código abierto para Microsoft Windows. Su función principal es la transferencia segura de archivos entre una computadora local y un servidor remoto. En nuestro ejemplo lo utilizaremos para lograr conectar el programa que se encuentra en nuestra computadora, al servidor.

2. Descargar PuTTY: https://www.putty.org/

PuTTY será la terminal que vamos a utilizar

3. Es requisito tener la instancia de aws encendida para poder probar el programa
![Captura2Lab1](https://user-images.githubusercontent.com/46933022/183263351-088a977d-3360-4b1d-80a3-4152c4a9d6fe.PNG)

# Probando programa
Es necesario iniciar sesión de Ubuntu con la Ip del servidor
![imagen](https://user-images.githubusercontent.com/46933022/183263466-9444d259-dc35-40f9-9e4b-ca22638bbc7a.png)

Una vez pegando los archivos del programa en la nueva sesión de Ubuntu de WinSCP, abrir la terminal de PuTTY y seguir los siguientes comandos de instalación de librerías y ejecución del programa:

1. sudo apt update
2. sudo apt install sodtware-properties-common
3. sudo add-apt-repository ppa:deadsnakes/ppa
4. sudo apt install python3.9
5. sudo apt-get install python3-pip
6. sudo pip3 install flask
7. screen -R <nombre>
8. screen -x <nombre>
9. sudo python3 server.py
  
# Referencias
  https://www.youtube.com/watch?v=TTE-ZxN3XkA
