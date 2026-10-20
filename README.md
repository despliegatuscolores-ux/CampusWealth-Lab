# 🎓 CampusWealth Lab | Behavioral Finance 101

El cerebro humano está programado evolutivamente para sobrevivir, no para invertir. **CampusWealth Lab** es una Single Page Application (SPA) educativa diseñada para enseñar a jóvenes universitarios y nuevos inversores cómo su propio cerebro ("Sistema 1", según Daniel Kahneman) les hace perder dinero mediante heurísticas y sesgos cognitivos.

Esta herramienta evalúa la propensión al riesgo y los atajos mentales del usuario, generando un mapa de vulnerabilidades clínico y recomendando estrategias mecánicas de mitigación.

🔗 **[Prueba la aplicación en vivo aquí] (AQUÍ_PON_TU_ENLACE_DE_GITHUB_PAGES)**

---

## ✨ Características Principales

*   🧠 **Diagnóstico Cognitivo (Test):** 12 preguntas situacionales (basadas en directrices de entidades reguladoras) que evalúan sesgos como el FOMO (Efecto Manada), Aversión a las Pérdidas, Exceso de Confianza o la Falacia del Costo Hundido.
*   📊 **Radiografía de Sesgos (Dashboard):** Visualización en tiempo real mediante un gráfico de radar que mapea las debilidades conductuales del usuario.
*   🛠️ **Apuntes de Mitigación (Toolkit):** Frameworks prácticos (Estandarización, Automatización, Test del Abogado del Diablo) para forzar el pensamiento analítico ("Sistema 2").
*   🕹️ **Simulador de Presión:** Escenarios de estrés de mercado interactivos que califican al usuario basándose en su radiografía cognitiva previa.
*   📝 **Tesis de Graduación Exportable:** Generador de reglas de inversión inquebrantables que el usuario puede descargar como un archivo de texto (`.txt`).

---

## 🛠️ Stack Tecnológico y Arquitectura

Esta aplicación ha sido diseñada con una arquitectura **Zero-Build** y **Privacy-First**. No requiere compilación, ni bases de datos, ni servidores externos.

*   **Estructura:** Un único archivo `index.html` autoconteido.
*   **Estilos:** [Tailwind CSS](https://tailwindcss.com/) (vía CDN) con soporte nativo para Modo Oscuro/Claro.
*   **Reactividad:** [Alpine.js](https://alpinejs.dev/) para la gestión del estado y la interfaz reactiva sin la sobrecarga de un Virtual DOM.
*   **Data Viz:** [Chart.js](https://www.chartjs.org/) para el mapeo poligonal de sesgos.
*   **Privacidad:** 100% Client-Side. Todos los datos de las evaluaciones se almacenan exclusivamente en el `localStorage` del navegador del usuario.

---

## 🚀 Despliegue e Instalación

Al ser una aplicación estática, el despliegue es inmediato.

**Opción A: Ejecución Local**
1. Clona este repositorio o descarga el archivo `index.html`.
2. Haz doble clic en el archivo para abrirlo en cualquier navegador web moderno. ¡Eso es todo!

**Opción B: GitHub Pages (Recomendado)**
1. Ve a la pestaña `Settings` de tu repositorio.
2. En el menú lateral, selecciona `Pages`.
3. Bajo "Build and deployment", selecciona la rama `main` y guarda. En 2 minutos tu aplicación estará pública en internet.

---

## 📚 Base Teórica

Este proyecto traduce conceptos académicos de la Economía Conductual a situaciones prácticas de la Generación Z. Está fundamentado en:
*   *Pensar rápido, pensar despacio* (Daniel Kahneman).
*   *Misbehaving* (Richard Thaler).
*   Guías de prevención de sesgos cognitivos para inversores minoristas (CNMV, SEC).
