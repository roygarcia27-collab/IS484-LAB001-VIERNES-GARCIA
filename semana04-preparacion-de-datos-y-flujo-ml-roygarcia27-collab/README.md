<div align="center">

<table style="border: none; border-collapse: collapse;">
<tr>
<td width="220" align="center" style="border: none; padding-right: 20px;">

<img src="assets/logo_vertical_blue.png" alt="UNSCH" width="280">

</td>
<td align="left" style="border: none; vertical-align: middle;">

<span style="font-size: 1.15em; color: #0f2b6a; font-weight: bold; letter-spacing: 0.5px; display: block; margin-bottom: 8px;"><b>ESCUELA PROFESIONAL DE INGENIERÍA DE SISTEMAS</b></span>

<span style="font-size: 2.1em; color: #0f2b6a; font-weight: bold; display: block; margin-bottom: 12px; line-height: 1.1;"><u>IS-484 — INTELIGENCIA ARTIFICIAL I</u></span>

<span style="font-size: 1.3em; color: #333333; display: block; margin-bottom: 8px;"><b><i>Laboratorio Práctico · Semana 04 · Semestre 2026-II</i></b></span>

<span style="font-size: 1.1em; color: #111111; font-weight: bold; display: block;"><i>Ing. Leidy Rosmery Maldonado Chauca</i></span>

</td>
</tr>
</table>

</div>

---

<h2><font color="#0f2b6a">▸ Propósito de este repositorio</font></h2>

Este repositorio corresponde exclusivamente al **desarrollo del laboratorio asignado para la Semana 04: Preparación de Datos y Flujo de Trabajo de Machine Learning**, mediante Classmoji.

Aquí registrarás de forma obligatoria tus avances y la entrega final de **ambas** actividades de esta semana (el Trabajo en Clase y el Ejercicio Práctico) usando confirmaciones de cambios (`git commit`) frecuentes para demostrar la trazabilidad y autoría de tu código.

---

<h2><font color="#0f2b6a">💻 Preparación del Entorno</font></h2>

Para trabajar de manera eficiente y evitar descargas repetitivas, utilizaremos **un único entorno virtual global** durante todo el semestre académico. **No debes crear un entorno nuevo para esta tarea.**

Sigue estrictamente estos pasos en tu terminal cada vez que descargues un nuevo laboratorio:

1. **Abre tu terminal o consola** de comandos.
2. **Navega hasta la carpeta** donde clonaste este repositorio semanal.
3. **Activa tu entorno virtual global** (el que creaste al inicio del ciclo) apuntando a su ruta correspondiente:
   * *En Windows (CMD):* `..\ruta_de_tu_entorno\Scripts\activate`
   * *En Windows (PowerShell):* `..\ruta_de_tu_entorno\Scripts\Activate.ps1`
   * *En Linux/Mac:* `source ../ruta_de_tu_entorno/bin/activate`
4. **Sincroniza las librerías necesarias** para este laboratorio específico ejecutando:
   ```bash
   pip install -r requirements.txt
   ```
   *(Si las librerías ya estaban instaladas de semanas anteriores, el proceso tomará apenas unos segundos).*
5. **Inicia tu entorno de desarrollo** ejecutando:
   ```bash
   jupyter notebook
   ```

---

<h2><font color="#0f2b6a">⚠ Reglas obligatorias de entrega</font></h2>

1. **Uso de la carpeta de entrega (`src/`):**
   Todos los elementos evaluables de **ambas** actividades (los dos cuadernos de notas, los dos datasets, imágenes de resultados) deben organizarse rigurosamente dentro de la carpeta `src/`. La raíz del repositorio debe permanecer limpia.

2. **Dos cuadernos, cada uno con su propio propósito:**
   * `Laboratorio04_Clase.ipynb` — actividades guiadas de la Sección 4 (Trabajo en Clase), sobre `estudiantes_sistemas.csv`.
   * `Laboratorio04_EjercicioPractico.ipynb` — Ejercicio Práctico independiente de la Sección 5 (base de la nota de laboratorio), sobre `practicas_programacion.csv`.

   Son **archivos independientes**: no comparten kernel ni variables entre sí. Todo lo que un cuaderno necesite del otro (por ejemplo, la función `normalizar_texto`) debe escribirse también ahí, aunque ya se haya definido en el primero.

3. **Formato de Notebooks:**
   La entrega debe incluir ambos archivos Jupyter Notebook (`.ipynb`) completamente ejecutados, asegurando que todos los bloques de código, outputs y gráficas sean perfectamente visibles en GitHub.

4. **Uso estricto de Rutas Relativas:**
   Los archivos de datos (`.csv`) deben cargarse obligatoriamente usando rutas relativas apuntando dentro de la misma carpeta `src/` (evita por completo rutas absolutas locales como `C:/Users/...`).

5. **Análisis conceptual en Markdown:**
   Las preguntas teóricas, análisis estadísticos y reflexiones solicitadas en la guía se deben responder directamente dentro del notebook correspondiente, utilizando celdas de tipo Markdown.

6. **Uso de Archivos Temporales (.gitignore):**
   Está estrictamente prohibido remover o ignorar el archivo `.gitignore`. No se deben subir carpetas de entornos virtuales o historiales locales de Jupyter a GitHub.

7. **Trazabilidad de Commits (Evaluado):**
   Se evaluará minuciosamente tu historial de `git commit`. Los mensajes de commit deben describir claramente la actividad realizada (ej. *feat: limpieza de datos del ejercicio practico*). Las entregas con un único commit final tendrán penalización automática.

---

<h2><font color="#0f2b6a">▣ Estructura obligatoria del repositorio</font></h2>

Tu repositorio individual debe lucir limpio y estructurado de la siguiente forma al momento de la entrega final:

```text
[Nombre-del-Repositorio-Asignado]/
│
├── .gitignore
├── README.md
├── requirements.txt
│
├── assets/
│   └── logo_vertical_blue.png
│
└── src/                                   <-- CARPETA OBLIGATORIA DE ENTREGA
    ├── Laboratorio04_Clase.ipynb          <-- Trabajo en Clase (Seccion 4), ejecutado
    ├── Laboratorio04_EjercicioPractico.ipynb  <-- Ejercicio Practico (Seccion 5), ejecutado
    ├── estudiantes_sistemas.csv           <-- Dataset del Trabajo en Clase
    └── practicas_programacion.csv         <-- Dataset del Ejercicio Practico
```
