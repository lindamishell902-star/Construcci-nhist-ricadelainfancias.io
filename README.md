# Construcción histórica de las infancias

Página web colaborativa del curso **Infancias: Historias y Perspectivas** (código 514517) de la **Universidad Nacional Abierta y a Distancia (UNAD)**, Escuela de Ciencias de la Educación.

El sitio documenta el análisis del grupo sobre las transformaciones históricas, sociales y culturales que han moldeado la manera de comprender a los niños, las niñas y las infancias. Se construye de forma progresiva: en cada reto del curso se incorporan nuevas evidencias y reflexiones.

🔗 **Sitio publicado:** `https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/`

---

## Contenido

La página se organiza en cuatro pestañas, una por reto:

| Pestaña | Título | Estado |
|---|---|---|
| I | Construcción histórica de las infancias | ✅ Disponible |
| II | Infancias en perspectiva | ✅ Disponible |
| III | Comprendiendo las realidades y desafíos de las infancias | 🚧 Reto 4 (pendiente) |
| IV | Voces para la transformación de las infancias | 🚧 Reto 5 (pendiente) |

### Reto 2: línea de tiempo interactiva

Recorre tres periodos históricos. Cada uno incluye contexto social, contexto cultural, concepciones de niño, niña y niñez, autores y aportes, hitos relevantes y una reflexión crítica:

- **Edad Antigua** (siglo VIII a.C. – 476 d.C.)
- **Edad Media** (476 – 1453 d.C.)
- **Edad Moderna** (siglos XV – XVIII)

La pestaña termina con una conclusión y las referencias bibliográficas en formato APA.

### Reto 3: matriz de análisis

La pestaña II, *Infancias en perspectiva*, presenta la matriz de análisis del grupo. Cada integrante analiza los autores que seleccionó, organizados en tarjetas con:

- Principales aportes
- Aporte al concepto de niño/niña
- Aporte a la construcción del concepto de infancia
- Incidencia en los contextos educativos y sociales
- ¿Cómo entiende el autor las infancias?

| Integrante | Autores seleccionados |
|---|---|
| Linda Michel Amaris Reales | Gómez-Mendoza y Alzate-Piedrahíta (2014); Enesco (2010) |
| Kelly Johana Mier Vega | Chica y Rosero Prado (2012); Gaitán (2010); Pollock (1983); deMause (1974) |
| Esilda Rosa Rincón Montero | Amador Baquiro (2012); Rodríguez Bernal (2022); Diker (2008); Carli (comp.) (2006) |

La pestaña incluye cinco conclusiones (comprensión de las infancias contemporáneas; niños y niñas como sujetos de derechos; diversidad, inclusión y equidad; contextos educativos y sociales; aprendizajes del grupo) y sus referencias bibliográficas en formato APA.

### Integrantes

La sección de equipo muestra una tarjeta por integrante. Al pulsar el rol se abre una ventana con su foto, nombre completo y descripción personal:

| Integrante | Rol |
|---|---|
| Esilda Rosa Rincón Montero | Dinamizadora del proceso y Evaluadora |
| Linda Michel Amaris Reales | Relator |
| Kelly Johana Mier Vega | Veedor de la autenticidad |

Los datos y las fotos están escritos directamente en `index.html`, por lo que se ven igual desde cualquier dispositivo o navegador.

---

## Estructura del repositorio

```
.
├── index.html   # Página completa (HTML, CSS y JavaScript en un solo archivo)
└── README.md    # Este archivo
```

No requiere instalación, compilación ni dependencias. La única conexión externa es la carga de las tipografías **Cormorant Garamond** y **Karla** desde Google Fonts.

## Uso local

1. Descarga o clona el repositorio.
2. Abre `index.html` con doble clic en cualquier navegador moderno.

```bash
git clone https://github.com/TU-USUARIO/NOMBRE-DEL-REPOSITORIO.git
cd NOMBRE-DEL-REPOSITORIO
```

---

## Modo de edición

La página incluye un editor integrado, accesible desde la barra inferior:

- **✎ Editar página:** activa la edición directa de cualquier texto, incluidos nombres, roles, descripciones y referencias. En la lista de referencias, `Enter` añade una nueva.
- **Foto de integrante:** en modo edición, el botón ✎ sobre cada avatar permite subir una imagen (se recorta y comprime automáticamente).
- **💾 Guardar borrador:** guarda los cambios en el navegador (`localStorage`).
- **⬇ Descargar página final:** genera un HTML limpio, sin modo edición, con todos los cambios incluidos.
- **Salir sin guardar:** cierra el modo edición.

> ⚠️ **Importante:** el borrador se guarda solo en el navegador de quien edita, no en el repositorio. Los cambios hechos desde el editor **no se ven en otros dispositivos**. Para que se vean en el sitio publicado, hay que **descargar la página final** y reemplazar el `index.html` del repositorio.

## Publicar en GitHub Pages

1. **Renombra el archivo.** Cambia `Construcción_histórica_de_las_infancias.html` por **`index.html`** (en minúsculas, sin tildes ni espacios). GitHub Pages busca ese nombre para mostrar la página principal.
2. **Crea un repositorio** en GitHub (por ejemplo, `infancias-historia`) y déjalo como **Public**.
3. **Sube los archivos** `index.html` y `README.md`, desde el botón *Add file → Upload files* o con Git:
   ```bash
   git init
   git add index.html README.md
   git commit -m "Publicación inicial del sitio"
   git branch -M main
   git remote add origin https://github.com/TU-USUARIO/NOMBRE-DEL-REPOSITORIO.git
   git push -u origin main
   ```
4. Ve a **Settings → Pages**.
5. En *Build and deployment*, elige **Source: Deploy from a branch**, selecciona la rama **main** y la carpeta **/ (root)**, y pulsa **Save**.
6. Espera uno o dos minutos. El sitio quedará disponible en:
   `https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/`

### Actualizar el sitio

Cada vez que tengas una versión nueva (por ejemplo, al completar el Reto 4), descarga la página final desde el editor, renómbrala a `index.html` y súbela al repositorio reemplazando la anterior. GitHub Pages se actualiza solo.

---

## Tecnologías

- HTML5, CSS3 y JavaScript vanilla
- Google Fonts (Cormorant Garamond y Karla)
- GitHub Pages para el alojamiento

## Referencias principales

- Ariès, P. (1987). *El niño y la vida familiar en el Antiguo Régimen*. Taurus.
- Benchimol, K., et al. (2023). *Infancias en plural*. Universidad Nacional General de Sarmiento.
- Amador Baquiro, J. C. (2012). Condición infantil contemporánea: Hacia una epistemología de las infancias. *Pedagogía y Saberes*, (37), 73–87.
- Carli, S. (Comp.). (2006). *La cuestión de la infancia: Entre la escuela, la calle y el shopping*. Paidós.
- Chica, F., & Rasero, L. (2012). Construcción social de la infancia y el reconocimiento de sus competencias. *Itinerario Educativo*, 26(60), 75–96.
- deMause, L. (Ed.). (1974). *The history of childhood*. Psychohistory Press.
- Diker, G. (2008). *¿Qué hay de nuevo en las nuevas infancias?* Universidad Nacional de General Sarmiento.
- Enesco, I. (2010). *El concepto de infancia a lo largo de la historia*. Repositorio Institucional UNAD.
- Gómez-Mendoza, M. A., & Alzate-Piedrahíta, M. V. (2014). La infancia contemporánea. *Revista Latinoamericana de Ciencias Sociales, Niñez y Juventud*, 12(1), 77–89.
- Locke, J. (1990). *Pensamientos sobre la educación*. Akal. (Obra original de 1693).
- Pedraza Ramírez, C. E., et al. (2022). *Representaciones sobre la educación infantil: Infancias en contingencia*. Sello Editorial UNAD.
- Pollock, L. A. (1983). *Forgotten children: Parent–child relations from 1500 to 1900*. Cambridge University Press.
- Rodríguez Bernal, Y. (2022). *Representaciones sociales: Infancias y contextos*. Sello Editorial UNAD.
- Rousseau, J. J. (1990). *Emilio, o de la educación*. Alianza Editorial. (Obra original de 1762).

La lista completa con enlaces está en las pestañas I y II del sitio.

## Autores

Grupo colaborativo del curso *Infancias: Historias y Perspectivas*, UNAD.

- Esilda Rosa Rincón Montero: Dinamizadora del proceso y Evaluadora
- Linda Michel Amaris Reales: Relator
- Kelly Johana Mier Vega: Veedor de la autenticidad

## Nota académica

Este sitio es un producto académico elaborado con fines educativos en el marco del curso 514517 de la UNAD.
