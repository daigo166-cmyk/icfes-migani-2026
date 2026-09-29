# 🎓 Portal Institucional Saber 11 (ICFES)
### **Institución Educativa Juan Bautista Migani – Jornada Mañana**
*Florencia, Caquetá, Colombia · DANE: 183001001598 · Código ICFES: 019158*

![Licencia](https://img.shields.io/badge/Licencia-Uso_Educativo_Gratuito-emerald?style=for-the-badge)
![Acceso](https://img.shields.io/badge/Acceso-Docentes_y_Directivos-amber?style=for-the-badge)
![ICFES Récord](https://img.shields.io/badge/Récord_Histórico-404_Puntos-blue?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-TailwindCSS-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Producción-success?style=for-the-badge)

Plataforma web interactiva para la visualización, caracterización diagnóstica, cuadro de honor con fotografías oficiales y comparativa histórica (2025 vs 2026) de los resultados institucionales de las Pruebas de Estado Saber 11 (ICFES).

> **🔒 Control de Acceso Institucional**: Sistema protegido con contraseña de uso exclusivo para el cuerpo docente y equipo directivo de la institución educativa.

---

## 👨‍💻 Autoría y Créditos
* **Software Creado por**: **Ing. Drigoberto Parra Sierra**
* **Dependencia**: Área de Apoyo de Sistemas e Informática
* **Institución**: Institución Educativa Juan Bautista Migani
* **Propósito**: Herramienta de apoyo pedagógico y toma de decisiones para directivos y docentes.
* **Licencia**: **Uso Educativo Gratuito** sin fines de lucro.

---

## 🌟 Características Principales

1. **Directorio Visual de Estudiantes con Fotografías Oficiales**:
   - Tarjetas individuales de los 79 estudiantes evaluados con su fotografía, puesto institucional (#1 a #79), salón (11-1, 11-2, 11-3), puntaje global y desglose por asignatura.
   - **Visor de Foto Ampliada (Lightbox)**: Al hacer clic en la foto, se despliega en pantalla completa en alta resolución.
   - **Gestión Dinámica de Fotos**: Botón exclusivo `📷 Foto` para cambiar o asignar nuevas fotografías con persistencia en el navegador.

2. **Salón de la Excelencia y Podio Olímpico 3D**:
   - 🥇 **1° Lugar**: **Jeremy Joel Moreno Gualdron** (11-3) – **404 / 500** *(Puntaje Histórico Institucional: 100/100 en Lectura, 100/100 en Inglés, Decil 100 Nacional)*.
   - 🥈 **2° Lugar**: **Manuela Portilla Ballesteros** (11-1) – **350 / 500**.
   - 🥉 **3° Lugar**: **Juan Angel Guerrero Cardenas** (11-2) – **338 / 500**.
   - Cuadro con los estudiantes más sobresalientes por cada asignatura.

3. **Comparativa Histórica 2025 vs 2026**:
   - Gráficos interactivos de barras comparando las 5 áreas entre ambos años.
   - Matriz de variación: Lectura Crítica (54.08 vs 53.49), Matemáticas (51.94 vs 50.51), Sociales (50.35 vs 49.05), Ciencias Naturales (51.13 vs 50.04) e Inglés (52.04 vs 52.23).

4. **Analítica Curricular y Gráficos (Chart.js)**:
   - Comparativo de salones 11-1 (263.3), 11-2 (249.9) y 11-3 (248.7).
   - Semáforo de distribución en niveles de desempeño (Nivel 1 a 4).
   - Análisis de brecha de género (masculino vs femenino).

5. **Plan de Refuerzo Prioritario y Control SIMAT**:
   - Seguimiento nominal a los 17 estudiantes que requieren acompañamiento pedagógico intensivo.
   - Control de asistencia sobre los 11 alumnos matriculados sin registro en la prueba.

---

## 🚀 Cómo Publicar este Proyecto en GitHub Pages (Ver en Línea)

Para que cualquier persona pueda abrir y ver esta página en internet de forma gratuita:

1. Crea un repositorio en [GitHub.com](https://github.com/) (por ejemplo: `icfes-migani-2026`).
2. Sube todos los archivos de esta carpeta al repositorio (arrastrando los archivos a la interfaz web o mediante `git push`).
3. En tu repositorio de GitHub, dirígete a:
   **Settings (Configuración)** → en el menú lateral izquierdo haz clic en **Pages**.
4. En **Build and deployment** → **Branch**:
   - Selecciona la rama `main` (o `master`).
   - Deja la carpeta en `/ (root)`.
   - Haz clic en **Save (Guardar)**.
5. Espera 1 minuto y GitHub te dará el enlace público gratuito (ejemplo: `https://tu-usuario.github.io/icfes-migani-2026/`).

---

## 📁 Estructura del Repositorio

```text
├── index.html                           <- Aplicación web interactiva optimizada
├── README.md                            <- Documentación oficial para GitHub
├── INFORME_INSTITUCIONAL.md             <- Informe técnico y pedagógico detallado
├── analisis_detallado_icfes_2026.xlsx   <- Libro Excel con hoja comparativa y datos
├── estudiantes_data.json                <- Base de datos estructurada
├── .gitignore                           <- Filtro de archivos temporales
└── fotos/                               <- Banco de imágenes optimizadas
    ├── logo.png                         <- Escudo oficial de la I.E.
    ├── desarrollador.jpg                <- Fotografía Ing. Drigoberto Parra Sierra
    └── [num_id].jpg                     <- Fotos individuales de los estudiantes
```

---

© 2026 · **Institución Educativa Juan Bautista Migani** · *Área de Apoyo de Sistemas e Informática*
