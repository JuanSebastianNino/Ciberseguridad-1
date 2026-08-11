# Ciberseguridad-1

Paso 1: Crear dos maquinas virtuales, una de Kali linux y otra de metasploitable 3 de windows

<img width="1918" height="1079" alt="Captura desde 2026-08-10 18-57-23" src="https://github.com/user-attachments/assets/a6ffc234-e82b-4774-89ad-402ae9527865" />

Paso 2: Crear un servidor DHCP para conectar las maquinas virtuales, (en un rango de ips donde esten ambas maquinas)

<img width="1918" height="1079" alt="Captura desde 2026-08-10 18-59-25" src="https://github.com/user-attachments/assets/a428b6d9-a6cd-4d31-bd26-98cb85859073" />

Paso 3: Iniciamos metasploit junto con su consola

<img width="1278" height="693" alt="Captura de pantalla_2026-08-10_15-11-46" src="https://github.com/user-attachments/assets/bb7e3f8d-9161-4ceb-8500-804b3f53a067" />

Paso 4: Buscamos el exploit de inflitracion (eternalblue)

<img width="1277" height="765" alt="Captura de pantalla_2026-08-10_15-12-03" src="https://github.com/user-attachments/assets/907bb8ea-70a8-48f1-8a01-202528195775" />

Paso 5: Seleccionamos el exploit de la lista que queramos usar, fijamos nuestro payload: la ip de nuestra victima (windows), la ip del dispositivo atacante (Kali), el puerto objetivo
y ejecutamos el "ataque" y esperamos a que resulte

#Si no funciona deberemos volver a ejecutar el comando run hasta que resulte

<img width="1278" height="765" alt="Captura de pantalla_2026-08-10_15-12-18" src="https://github.com/user-attachments/assets/0d36a149-1de5-452d-b84e-569140eb3815" />

Paso 6: Deberemos mantener la conexion y "privilegios" para seguir "explorando el dispositivo en la sesion que nos encontremos

<img width="1280" height="696" alt="Captura de pantalla_2026-08-10_15-12-38" src="https://github.com/user-attachments/assets/84348db0-5676-423e-9aa9-5ad13b5f1cbe" />

Paso 7: Cargar el programa de post-explotacion (kiwi de mimikatz) para tomar todas las credenciales que esten el el dispositivo (windows)

<img width="1279" height="763" alt="Captura de pantalla_2026-08-10_15-12-55" src="https://github.com/user-attachments/assets/6913342d-98ad-4fca-afe5-c49a10321738" />

Paso 8: Tomamos capturas de pantalla del dispositivo victima (windows), hacemos una grabacion en vivo de la pantalla (streaming) y revisamos los procesos que esten ejecutandose

<img width="1278" height="765" alt="Captura de pantalla_2026-08-10_15-13-35" src="https://github.com/user-attachments/assets/98768a68-f277-407f-825d-61ff765b90c8" />

Captura de pantalla:

<img width="800" height="600" alt="ORBnIcXA" src="https://github.com/user-attachments/assets/a87c3a35-6168-4431-b6c9-450f6991392c" />

Streaming:

<img width="1861" height="1048" alt="Captura desde 2026-08-10 15-03-12" src="https://github.com/user-attachments/assets/250df227-c8d7-42c7-8807-868fce30c305" />

Paso 9: De la lista de procesos elegimos uno (en mi caso 2044) y lo monitoreamos en tiempo real (guardandolo todo en un archivo de texto), luego abrimos el terminal de windows

<img width="1277" height="565" alt="Captura de pantalla_2026-08-10_15-13-49" src="https://github.com/user-attachments/assets/2f2152ef-c4c7-44bd-9e4e-025dc8f074fe" />

Paso 10: Revisamos la informacion en la terminal de windows desde kali

<img width="1276" height="468" alt="Captura de pantalla_2026-08-10_15-14-05" src="https://github.com/user-attachments/assets/6a76a54c-ad98-4efe-bd56-3e231cb10472" />

<img width="1278" height="799" alt="Captura de pantalla_2026-08-10_15-14-17" src="https://github.com/user-attachments/assets/3910101d-5362-4fe4-b4d3-828303378125" />
