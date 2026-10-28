# Arqueologia_IA_Generativa
Repo personal del taller de Arqueología de la IA generativa
# Arqueología de la IA generativa

Repositorio personal del taller **MUTAR**: cuatro sesiones para explorar modelos de imagen y movimiento anteriores al auge de la difusión y los grandes modelos de lenguaje.

El recorrido propone trabajar con sus alucinaciones, híbridos y transformaciones como material creativo. Partimos de una fotografía, exploramos imágenes generadas y terminamos conectando los resultados en piezas audiovisuales.

## Las sesiones

| Sesión | Herramienta | Qué exploramos | Abrir en Colab |
| --- | --- | --- | --- |
| **1 · La red que alucina** | DeepDream · 2015 | Texturas y formas sobre una fotografía, capas de InceptionV3, octavas, alta resolución y video. | [Sesión 1](https://colab.research.google.com/github/caramos84/Arqueologia_IA_Generativa/blob/main/Sesion1_DeepDream_v2.ipynb) |
| **2 · El zoológico de clases** | BigGAN · 2018 | Generación por categorías, semillas, truncación, híbridos y viajes entre clases. | [Sesión 2](https://colab.research.google.com/github/caramos84/Arqueologia_IA_Generativa/blob/main/Sesion2_BigGAN_v2%20%281%29.ipynb) |
| **3 · El espacio abstracto** | Projected GAN · 2021 | Exploración de semillas y sus vecindarios, disolución, lienzo expandido y recorridos animados. | [Sesión 3](https://colab.research.google.com/github/caramos84/Arqueologia_IA_Generativa/blob/main/Sesion3_ProjectedGAN_v3%20%281%29.ipynb) |
| **4 · Entre imágenes** | FILM · 2022 | Interpolación de imágenes y videos, transiciones, zoom infinito y cámara lenta. | [Sesión 4](https://colab.research.google.com/github/caramos84/Arqueologia_IA_Generativa/blob/main/Sesion4_FILM%20%281%29.ipynb) |

Cada notebook combina explicaciones conceptuales, instrucciones paso a paso y formularios para experimentar sin tener que modificar el código.

## Cómo empezar

1. Abre una sesión desde los enlaces de la tabla. Se recomienda seguir el orden del taller.
2. En Colab, selecciona **Archivo → Guardar una copia en Drive** para conservar tus cambios.
3. Activa una GPU en **Entorno de ejecución → Cambiar tipo de entorno de ejecución → T4 GPU**, si está disponible.
4. Ejecuta las celdas en orden, de arriba hacia abajo. Las primeras preparan el entorno y descargan los modelos necesarios.
5. Cambia los parámetros de los formularios y vuelve a ejecutar la celda correspondiente para explorar otras variantes.
6. Guarda o descarga tus resultados antes de cerrar la sesión.

## Qué necesitas

- Una cuenta de Google para trabajar en Colab y guardar tus copias.
- Conexión a internet para descargar las bibliotecas y los pesos de los modelos.
- Una GPU de Colab para los ejercicios más exigentes. Su disponibilidad y los límites de uso dependen de tu cuenta.
- Una fotografía propia para experimentar con DeepDream. El notebook también ofrece una imagen de ejemplo.
- Imágenes o videos para la sesión de FILM; puedes utilizar los resultados de las sesiones anteriores.

Los notebooks están preparados para **Google Colab**: usan rutas como `/content`, formularios e integración con Google Drive. Ejecutarlos en otro entorno requiere adaptar esas partes y preparar las dependencias.

## Guardar los resultados

Los notebooks permiten guardar en Google Drive y descargar los resultados en un archivo ZIP. La estructura propuesta para conectar el trabajo de las cuatro sesiones es:

```text
Mi unidad/
└── Taller_MUTAR/
    ├── sesion1/   # DeepDream
    ├── sesion2/   # BigGAN
    ├── sesion3/   # Projected GAN
    └── sesion4/   # FILM
```

En la sesión 1, la opción de guardar directamente en Drive aparece en la sección de video; en las sesiones 2, 3 y 4, la conexión se ofrece al inicio. Revisa la ruta indicada por cada notebook.

**Los archivos guardados únicamente en `/content` son temporales** y pueden perderse cuando Colab elimina el entorno de ejecución. Guarda en Drive o descarga lo que quieras conservar.

FILM puede recorrer las carpetas del taller para construir un catálogo de imágenes y videos y combinarlos en una nueva pieza. También permite subir material desde tu computador.

## Archivos del repositorio

- [Sesión 1 · DeepDream](Sesion1_DeepDream_v2.ipynb)
- [Sesión 2 · BigGAN](Sesion2_BigGAN_v2%20%281%29.ipynb)
- [Sesión 3 · Projected GAN](Sesion3_ProjectedGAN_v3%20%281%29.ipynb)
- [Sesión 4 · FILM](Sesion4_FILM%20%281%29.ipynb)

Algunos notebooks incluyen salidas de ejecuciones anteriores. Esas salidas sirven como referencia; para generar tus propias piezas, ejecuta las celdas en tu entorno de Colab.

## Referencias y créditos

El taller utiliza modelos y bibliotecas de sus respectivos autores. Cada notebook incluye explicaciones y referencias para profundizar.

- **DeepDream / InceptionV3:** implementación del ejercicio con TensorFlow.
- **BigGAN:** carga de modelos mediante `pytorch-pretrained-biggan`.
- **Projected GAN:** código y modelos del proyecto `autonomousvision/projected_gan`.
- **FILM:** modelo de Google distribuido a través de TensorFlow Hub.

Consulta las licencias y condiciones de los proyectos y modelos originales antes de reutilizarlos fuera del taller.
