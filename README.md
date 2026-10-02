# Sistema experto: perfil del inversionista

Primera entrega del proyecto: base de conocimientos, motor de inferencia e interfaz de usuario.

## Archivos

- [Presentación para clase](index.html): 12 diapositivas en estilo Blockframe. Incluye teoría, reglas, un ejemplo y notas para exponer.
- [Cuaderno de la primera entrega](Primera_Entrega_Sistema_Experto.ipynb): las 14 preguntas, reglas de puntuación, perfiles y cuestionario interactivo.

## Presentación

Descarga `index.html` y ábrelo en un navegador. Las fuentes están incorporadas y funciona sin conexión.

- Flechas o barra espaciadora: navegar.
- **F**: pantalla completa.
- **N**: notas para el expositor (también se muestran al público si se proyecta esa pantalla).
- **E**: editar textos. Los cambios se guardan localmente en ese navegador.
- **Ctrl+S**: descargar una copia con los textos editados. Para actualizar la versión publicada, hay que subir esa copia al repositorio como `index.html`.

## Cuaderno

GitHub permite consultar su contenido y descargar el archivo; no ejecuta el cuestionario interactivo.

Para utilizarlo, ábrelo en Jupyter Notebook, JupyterLab o VS Code con soporte de notebooks. Requiere Python 3.10 o posterior, IPython e ipywidgets. Ejecuta las celdas en orden, responde las 14 preguntas y pulsa **Evaluar perfil**.

El cuaderno no utiliza Pandas, NumPy ni gráficas. El perfil y la explicación se obtienen con reglas de Python.

## Publicar la presentación en Vercel

Importa este repositorio desde tu cuenta de Vercel y utiliza:

- **Framework Preset:** Other.
- **Root Directory:** la raíz del repositorio.
- **Build Command:** vacío (sin compilación).
- **Output Directory:** `.`.

`index.html` es la página inicial de la presentación. El archivo `.ipynb` se mantiene en el mismo repositorio para consultar o descargar el trabajo práctico; Vercel no ejecuta Python ni sus widgets.

Proyecto académico basado en las reglas del cuestionario original. La respuesta de la pregunta 12 es una declaración del usuario; el programa no comprueba documentación financiera.
