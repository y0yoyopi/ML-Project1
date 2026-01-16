
# Proyecto 1 - Machine Learning

## Como construir y correr el proyeto

### 1. Clonar el repositorio

git clone https://github.com/usuario/ML-Project1.git
cd ML-Project1

### 2. Construir la imagen

Si usas Docker:

docker build -t ml-project .


O si usas Docker Compose:

docker compose build

### 3. Ejecutar el contenedor

Con Docker:

docker run -p 8888:8888 -v $(pwd):/app ml-project


Con Docker Compose:

docker compose up

### 4. Abrir el notebook

La terminal mostrará una URL tipo:

http://127.0.0.1:8888/lab?token=xxxxxxxxx


Ábrela en el navegador.

### 5. Entrar al notebook principal

Una vez dentro, abrir:

animations/ML-Project1.ipynb
