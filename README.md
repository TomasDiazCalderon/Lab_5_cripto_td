# Laboratorio 5 de Criptografía y Seguridad en Redes de Tomás Díaz Calderón

Este repositorio contiene los archivos correspondientes al Laboratorio 5, donde se estudia el protocolo SSH, a fin de poder entender el concepto de criptografía asimétrica y firmas digitales.

Específicamente, el repositorio contiene:

- Dockerfile.c1: Contiene la creación del primer contenedor con Ubuntu 16.10 (C1). Se instala además cliente openssh.
- Dockerfile.c2: Contiene la creación del segundo contenedor con Ubuntu 18.10 (C2). Se instala además cliente openssh.
- Dockerfile.c3: Contiene la creación del tercer contenedor con Ubuntu 20.10 (C3). Se instala además cliente openssh.
- Dockerfile.s1: Contiene la creación del cuarto contenedor con Ubuntu 22.10 (C4). Se instala además el cliente y servidor openssh.
- docker-compose.yml: Sirve para levantar los Dockerfile al mismo tiempo.
- c1.pcapng: Captura de tráfico de C1 a C4.
- c2.pcapng: Captura de tráfico de C2 a C4.
- c3.pcapng: Captura de tráfico de C3 a C4.
- c4.pcapng: Captura de tráfico de C4 a C4.
- key-server-menor.pcapng: Captura de tráfico con tamaño de Key Exchange Init del servidor reducido a menos de 300 bytes.
- replica.pcapng: Réplica del tráfico de la Figura 1 del enunciado.
- Laboratorio5_imagenes.rar: Contiene las imágenes utilizadas en el informe del laboratorio.


# Contacto

Correo: tomas.diaz_c@mail.udp.cl
