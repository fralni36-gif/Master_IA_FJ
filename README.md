# 🎓 Masterclass Suite Interactiva & Compendio de Exámenes
## Máster Universitario en Inteligencia Artificial — UNIR

Esta carpeta constituye el **proyecto centralizado y suite integral de estudio** para todas las asignaturas del Máster en Inteligencia Artificial de la UNIR. Reúne el temario completo, simuladores de exámenes, modelos de examen oficiales resueltos paso a paso, ejercicios de cálculo y el catálogo de 86 recursos audiovisuales (videos de clase y podcasts de audio).

----

### 📂 Estructura del Proyecto

```text
Masterclass_Suite_Interactiva_Master_IA/
├── index.html                           # 🌟 Aplicación Web Interactiva Principal (Doble clic para abrir)
├── masterclass_interactiva_master_ia.html # Copia espejo directa de index.html
├── examenes_resueltos_master_ia.pdf     # 📄 Compendio Oficial de Exámenes Resueltos (10 páginas PDF)
├── visor_examenes_resueltos_pdf.html    # 🔍 Visor Interactivo Web del PDF de Exámenes
├── examenes_oficiales_resueltos.html    # Código fuente estructurado de los exámenes resueltos
├── diagramas/                           # 📊 Diagramas conceptuales de alta resolución
├── videos/                              # 🎥 Enlace a videos de lecciones magistrales y multimedia
└── README.md                            # 📖 Este manual de uso y documentación técnica
```

---

### 🚀 Cómo Ejecutar la Suite

1. **Apertura directa:**
   - Haz doble clic sobre **`index.html`** desde el Finder de macOS (o ábrelo con Google Chrome, Safari, Firefox o Edge).
   - No requiere conexión a internet para las funciones nucleares, temas, cálculos o lectura karaoke.

2. **Opcional — Servidor Local HTTP:**
   ```bash
   cd "/Users/franciscoj/Documents/Documentos - MacBook Pro de FJAN/Master IA/Masterclass_Suite_Interactiva_Master_IA"
   python3 -m http.server 8080
   # Abrir en el navegador: http://localhost:8080
   ```

---

### 🎯 Características y Asignaturas Incluidas

Utiliza el selector desplegable en la barra superior (**"Asignatura Activa"**) para alternar instantáneamente entre las 5 asignaturas del máster:

1. **Aprendizaje Automático (TAA · PER 6678):**
   - 11 Temas completos con fórmulas KaTeX y diagramas.
   - 11 Videos de Masterclass de ~4 minutos por tema.
   - Preguntas críticas de examen: Ponderación $\alpha_i$ en AdaBoost, error OOB ($1/e \approx 36.8\%$), criterio Gini vs. Entropía.

2. **Investigación y Gestión de Proyectos en IA (IGP · PER 17322):**
   - 12 Temas del temario oficial.
   - 39 Recursos multimedia (Podcasts oficiales M4A y videos de clase).
   - Exámenes resueltos: Hito Dartmouth 1956, variables experimentales, Horizonte Europa, Scrum, Data Split (Train/Val/Test), encadenamiento hacia adelante/atrás, ACO/PSO y RGPD Art. 22.

3. **Razonamiento y Planificación Automática (RPA · PER 6679):**
   - 10 Temas oficiales.
   - 35 Clases grabadas y audios explicativos.
   - 14 Modelos oficiales de examen resueltos:
     - *Preguntas cortas:* Tablas de verdad de contingencias lógicas, enlaces causales vs. orden temporal en POP.
     - *Caso 1:* Búsqueda $A^*$, demostración de admisibilidad y consistencia, degeneración en Dijkstra ($h=0$).
     - *Caso 2:* Dominio PDDL 1.2 `restaurante2526_q1_E` (Child-Snack con bandejas y alérgenos), árbol de 4 acciones óptimas.

4. **Procesamiento del Lenguaje Natural (PLN · PER 6680):**
   - 11 Temas y preguntas tipo test de examen.
   - Ejercicios de cálculo paso a paso: Viterbi (HMM), Lesk simplificado (WordNet), Perplejidad ($PPL$) con suavizado Laplace ($+1$), parsing CKY en CNF y caracterización 2D de textos (TF-IDF vs. embeddings).

5. **Visión Artificial (VA · PER 6682):**
   - 11 Temas y videos de detección YOLO en tiempo real.
   - Conceptos clave de examen: Arquitecturas 1-stage vs. 2-stage (YOLO vs. Faster R-CNN), transformaciones de Hough, filtros convolucionales espaciales y segmentación semántica.

---

### 🛠️ Herramientas Pedagógicas Incorporadas en la Suite

- **Modo Lectura Guiada Karaoke Zero-Jitter:** Lectura asistida por voz nativa sincronizada línea por línea, con contraste ergonómico WCAG AAA sin saltos de maquetación ni fatiga visual.
- **Laboratorio Feynman:** Explicaciones en lenguaje sencillo, analogías intuitivas y desgloses paso a paso.
- **Flashcards SM-2:** Repaso espaciado con algoritmo SuperMemo-2 y seguimiento de retención a largo plazo.
- **Simulador de Examen & Compendio Oficial:** 4 subpestañas:
  1. *Test Oficial:* Preguntas de opción múltiple con retroalimentación instantánea.
  2. *Cálculos Numéricos:* Ejercicios resueltos paso a paso con fórmulas.
  3. *Casos Prácticos:* Ensayos y desarrollos de ingeniería con criterios de rúbrica.
  4. *Compendio Oficial Resuelto:* Modelos de examen reales con resolución completa.
- **Videoteca y Fonoteca:** Reproductor multimedia compatible con videos MP4 y podcasts de audio M4A locales.
