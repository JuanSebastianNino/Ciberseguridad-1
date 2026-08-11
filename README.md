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

