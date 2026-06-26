# 🛠️ Habilidades Demandadas por Empresas Tech en Costa Rica

![Estado](https://img.shields.io/badge/Estado-En%20progreso-yellow)
![Proyecto](https://img.shields.io/badge/Portafolio-Proyecto%203%20de%204-purple)
![Licencia](https://img.shields.io/badge/Licencia-MIT-green)

> **Proyecto 3 de 4** de la serie
> [Radiografía de Empleabilidad STEAM en Costa Rica](https://github.com/RDRamosU/data-portfolio)

---

## 🔍 Pregunta central

**¿Qué habilidades demandan las empresas tech en Costa Rica
y dónde están las principales brechas de talento?**

---

## 📌 Preguntas de análisis

1. ¿Cuáles son las ocupaciones tech más demandadas en CR?
2. ¿Qué habilidades técnicas son más requeridas por puesto?
3. ¿Qué nivel de inglés exige el mercado tech costarricense?
4. ¿Cuáles son las brechas entre lo que el mercado demanda
   y lo que los graduados ofrecen?
5. ¿Qué competencias valoran más los empleadores de graduados
   universitarios en áreas STEM?

---

## 🎯 Hallazgo anticipado

El mercado tech costarricense presenta tres brechas estructurales
de talento que el sistema educativo no cubre completamente:

1. **Inglés insuficiente** — requisito en todos los perfiles tech,
   especialmente B1-C1 para posiciones en Zona Franca
2. **Frameworks modernos** — escasez de Angular, React, .NET Core,
   Flutter, AWS y Azure
3. **Certificaciones internacionales** — ITIL, CCNA, Scrum, AWS
   muy demandadas pero escasas entre graduados locales

---

## 📂 Fuentes de datos

| Fuente | Institución | Datos clave | Periodo |
|--------|------------|-------------|---------|
| Resumen de ocupaciones de más alta demanda | MTSS — OML | Perfiles tech · habilidades · regiones · brechas | 2025 |
| Estudio del sector empleador | CONARE-OPES | Competencias valoradas · inserción STEM · género | 2023 |

> ⚠️ **Política de datos:** Todos los datasets son de acceso público,
> no contienen PII y provienen de fuentes institucionales oficiales.

---

## 🗂️ Estructura del proyecto

```
cr-habilidades-demanda-tech/
├── README.md
├── requirements.txt
├── .gitignore
├── data/
│   ├── raw/                          # Datos originales sin modificar
│   └── processed/                    # Datos limpios para análisis
├── notebooks/
│   ├── 01_definicion_problema.ipynb
│   ├── 02_exploracion_datos.ipynb
│   ├── 03_limpieza_preparacion.ipynb
│   └── 04_visualizaciones_hallazgos.ipynb
└── assets/
    └── graficas/                     # Visualizaciones exportadas
```

---

## 📓 Notebooks

| Notebook | Descripción | Estado |
|----------|-------------|--------|
| [01 — Definición del problema](notebooks/01_definicion_problema.ipynb) | Contexto, preguntas, fuentes y brechas anticipadas | 🟢 Completado |
| [02 — Exploración de datos](notebooks/02_exploracion_datos.ipynb) | Extracción de perfiles y habilidades del MTSS y CONARE | 🟢 Completado |
| [03 — Limpieza y preparación](notebooks/03_limpieza_preparacion.ipynb) | Consolidación y dataset de habilidades final | 🟢 Completado |
| [04 — Visualizaciones y hallazgos](notebooks/04_visualizaciones_hallazgos.ipynb) | Gráficas de demanda · brechas · conclusiones | 🟢 Completado |

---

## 📊 Variables clave del análisis

| Variable | Fuente | Tipo |
|----------|--------|------|
| Ocupaciones tech más demandadas | MTSS OML 2025 | Categórica |
| Habilidades técnicas por puesto | MTSS OML 2025 | Categórica / nivel |
| Nivel de inglés requerido | MTSS OML 2025 | Ordinal (A1-C1) |
| Región de mayor demanda | MTSS OML 2025 | Categórica |
| Competencias valoradas por empleadores | CONARE 2023 | Escala 1-5 |
| Brecha género en inserción STEM | CONARE 2023 | % |

---

## 🔧 Cómo ejecutar este proyecto

```bash
git clone https://github.com/RDRamosU/cr-habilidades-demanda-tech.git
cd cr-habilidades-demanda-tech
pip install -r requirements.txt
jupyter notebook
```

> También puede ejecutarse en **Google Colab** sin instalación local.

---

## 🛠️ Tecnologías

`Python 3.11+` `pandas` `NumPy` `Matplotlib` `Seaborn` `pdfplumber` `Jupyter`

---

## 📎 Parte de la serie

| # | Proyecto | Estado |
|---|----------|--------|
| 1 | [Graduados STEAM en CR 2014–2022](https://github.com/RDRamosU/cr-graduados-steam-analisis) | [🟢 Completado](https://www.linkedin.com/pulse/graduados-steam-de-las-universidades-estatales-costa-rica-zaj4e) |
| 2 | [Mercado laboral tech en CR](https://github.com/RDRamosU/mercado-laboral-steam-cr) | [🟢 Completado](https://www.linkedin.com/posts/ruben-ramos_github-rdramosumercado-laboral-steam-cr-share-7474864458662715392-I-1o/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAChGLMoBf7GYJaNtqlgpzhtt9Jr9qJkG8zc) |
| **3** | **Habilidades demandadas tech CR** ← estás aquí | [🟢 Completado](https://www.linkedin.com/posts/ruben-ramos_anaerlisisdedatos-steam-costarica-share-7475270119057805328-ASBm/) |
| 4 | [CR vs Latinoamérica en STEAM](https://github.com/RDRamosU/cr-steam-comparativa-regional) | 🟢 Completado |

---

## 📰 Artículo publicado

Análisis completo publicado en LinkedIn:  
[Habilidades Demandadas por Empresas Tech en Costa Rica]( https://www.linkedin.com/posts/ruben-ramos_anaerlisisdedatos-steam-costarica-share-7475270119057805328-ASBm/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAChGLMoBf7GYJaNtqlgpzhtt9Jr9qJkG8zc) 

---
## 👤 Autor

**Ruben Dario Ramos Ulate**
🌐 [rubendario.dev](https://rubendario.dev) · 💼 [LinkedIn](https://www.linkedin.com/in/ruben-ramos) · 🐙 [GitHub](https://github.com/RDRamosU)
