
# Proyecto 1 - Machine Learning
## 1. Descripción
Este proyecto muestra de forma visual e interactiva cómo funcionan la regresión lineal y no lineal utilizando animaciones generadas con Manim y Python.

## 2. Requerimientos del Software
### 2.1. Opción recomendada (con Docker)
Solo necesitas instalar:
- **Docker Desktop** o **Docker Engine**

No requiere instalar Python ni dependencias adicionales en el sistema.

### 2.2. Opción alternativa (sin Docker)
Requiere instalar manualmente:
- Python 3.10
- FFmpeg
- Cairo + Pango
- Jupyter Notebook o JupyterLab
- Dependencias listadas en `requirements.txt`

No se recomienda debido a la cantidad de dependencias.

## 3. Como construir y correr el proyeto

### 3.1. Clonar el repositorio

git clone https://github.com/usuario/ML-Project1.git
cd ML-Project1

### 3.2. Construir la imagen

Si usas Docker:

docker build -t ml-project .


O si usas Docker Compose:

docker compose build

### 3.3. Ejecutar el contenedor

Con Docker:

docker run -p 8888:8888 -v $(pwd):/app ml-project


Con Docker Compose:

docker compose up

### 3.4. Abrir el notebook

La terminal mostrará una URL tipo:

http://127.0.0.1:8888/lab?token=xxxxxxxxx


Ábrela en el navegador.

### 3.5. Entrar al notebook principal

Una vez dentro, abrir:

animations/ML-Project1.ipynb

## 4. Autores
- Luis Huapaya
- Grace Inga
- Aaron Rojas
