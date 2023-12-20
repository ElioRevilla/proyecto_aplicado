# Proyecto Aplicado - Grupo N°4

## Descripción
Este repositorio contiene todos los materiales y códigos desarrollados por el Grupo N°4 para el curso Proyecto Aplicado I. 

## Configuración y Ejecución en Google Colab

Para ejecutar el código en Google Colab, sigue estos pasos:

### Paso 1: Clonar el Repositorio
Clona el repositorio en tu máquina local. Recomendamos subir la carpeta clonada a Google Drive para un fácil acceso desde Google Colab.

```bash
git clone https://github.com/ElioRevilla/proyecto_aplicado.git
```

### Paso 2: Abrir el Cuaderno de Jupyter
Abre el archivo `Proyecto Aplicado-05.ipynb`. Si has subido la carpeta a Drive, asegúrate de que el cuaderno esté en la misma ubicación.

### Paso 3: Instalar Requerimientos
Ejecuta la sección "Requerimientos" en el cuaderno para instalar todas las dependencias necesarias para el proyecto.

### Paso 4: Configurar Rutas de Modelos
En la sección 6.4. Streamlit del cuaderno, actualiza las rutas de los modelos a las ubicaciones correspondientes en tu Drive. Reemplaza las siguientes líneas con las rutas donde has almacenado los modelos:

```python
model_path_txt = "/content/drive/MyDrive/[Tu ruta]/text_model"
model_path_img = "/content/drive/MyDrive/[Tu ruta]/image_model_ViT"
```

Asegúrate de reemplazar `[Tu ruta]` con la ruta exacta donde están ubicadas tus carpetas de modelo.

## Soporte y Colaboración
Si tienes preguntas o deseas contribuir al proyecto, no dudes en abrir un issue o un pull request. Para obtener más información sobre cómo contribuir, consulta [CONTRIBUTING.md](LINK_A_CONTRIBUTING.md).

## Autores
- Alejandro Sandoval Arellano
- Álvaro Quinteros Aguilera
- Daniel Ortiz Pacheco
- Elio Francisco Revilla Pérez
