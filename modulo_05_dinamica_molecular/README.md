# ⚛️ Módulo 5: Dinámica Molecular

<div align="center">

**Universidad de Caldas - Departamento de Química**  
*Introducción a la Química Computacional (173G7G)*  
**Profesor:** José Mauricio Rodas Rodríguez

---

</div>

## 📋 Descripción del Módulo

Este módulo te introduce a la **dinámica molecular (DM)**, la técnica computacional que permite simular el movimiento de átomos y moléculas en función del tiempo. Aprenderás desde los fundamentos físicos de la integración numérica de las ecuaciones de Newton hasta la ejecución de simulaciones completas de proteínas en agua usando GROMACS y OpenMM. Dominarás el análisis de trayectorias para extraer información estructural y termodinámica de las simulaciones.

## 🎯 Objetivos de Aprendizaje

Al completar este módulo, serás capaz de:

- ✅ Comprender las bases físicas de la dinámica molecular y las ecuaciones de movimiento
- ✅ Implementar y comparar integradores numéricos (Verlet, Velocity-Verlet, Leap-Frog)
- ✅ Aplicar condiciones de contorno periódicas y diferentes ensambles estadísticos
- ✅ Configurar termostatos y barostatos para controlar temperatura y presión
- ✅ Preparar sistemas biomoleculares completos para simulación (solvatación, iones)
- ✅ Ejecutar simulaciones de proteínas con GROMACS y OpenMM
- ✅ Analizar trayectorias calculando RMSD, RMSF, radio de giro y puentes de hidrógeno
- ✅ Integrar todo el flujo de trabajo en un proyecto completo de DM

## 📚 Contenido del Módulo

### Actividades

| # | Actividad | Descripción | Duración |
|---|-----------|-------------|----------|
| **5.1** | [Fundamentos de Dinámica Molecular](01_fundamentos_dinamica_molecular.ipynb) | Ecuaciones de Newton, potencial LJ, Maxwell-Boltzmann, ensambles | 2-3 horas |
| **5.2** | [Integradores y Algoritmos](02_integradores_algoritmos.ipynb) | Verlet, Velocity-Verlet, Leap-Frog, RK4 y conservación de energía | 2-3 horas |
| **5.3** | [Condiciones de Contorno y Ensamble](03_condiciones_contorno_ensemble.ipynb) | PBC, imagen mínima, tipos de caja, NVE/NVT/NPT | 2-3 horas |
| **5.4** | [Termostatos y Barostatos](04_termostatos_barostatos.ipynb) | v-rescale, Nosé-Hoover, Parrinello-Rahman, archivos .mdp | 3-4 horas |
| **5.5** | [Preparación de Sistemas](05_preparacion_sistemas.ipynb) | Solvatación, modelos de agua, adición de iones, GROMACS y OpenMM | 3-4 horas |
| **5.6** | [Simulación de Proteínas](06_simulacion_proteinas.ipynb) | Campos de fuerza, protocolo completo, script de GROMACS | 3-4 horas |
| **5.7** | [Análisis de Trayectorias](07_analisis_trayectorias.ipynb) | RMSD, RMSF, radio de giro, puentes de H, MDAnalysis | 3-4 horas |
| **5.8** | [Práctica con GROMACS y OpenMM](08_practica_gromacs_openmm.ipynb) | Simulación completa integrada de ubiquitina, informe final | 4-5 horas |

**Duración total estimada:** 22-30 horas

## 🚀 Cómo Usar Este Módulo

### Requisitos Previos

- ✅ **Módulo 1 completado** - Fundamentos computacionales y Python
- ✅ **Módulo 2 completado** - Representación molecular y formatos de archivo
- ✅ **Módulo 3 completado** - Mecánica molecular y campos de fuerza
- ✅ **Módulo 4 completado** - Modelado de proteínas y estructuras PDB
- ✅ Python 3.8+ instalado
- ✅ Jupyter Notebook o Google Colab
- ✅ Conocimientos básicos de termodinámica estadística

### Orden Recomendado

Las actividades están diseñadas para seguirse **secuencialmente**:

```
5.1 → 5.2 → 5.3 → 5.4 → 5.5 → 5.6 → 5.7 → 5.8
```

Las actividades 5.1–5.3 son teóricas/algorítmicas y no requieren GROMACS ni OpenMM instalados.  
Las actividades 5.4–5.8 requieren al menos uno de los dos softwares.

### Instalación de Dependencias

Para trabajar localmente, crea un entorno dedicado:

```bash
# Entorno completo para el Módulo 5
conda create -n dm_env python=3.11
conda activate dm_env

# Software de dinámica molecular
conda install -c conda-forge gromacs openmm

# Análisis y visualización
conda install -c conda-forge mdanalysis biopython numpy matplotlib pandas scipy seaborn

# Extras útiles
pip install py3Dmol requests
```

**Nota:** GROMACS requiere Linux o macOS para su funcionamiento completo. En Windows se recomienda WSL2 o Google Colab.

## 📂 Estructura de las Actividades

Cada actividad incluye:

1. **Introducción** — Motivación y contexto físico/biológico
2. **Fundamentos Teóricos** — Ecuaciones y conceptos clave con notación matemática
3. **Implementación en Python** — Código ejecutable con visualizaciones
4. **Comandos de Software** — GROMACS CLI y/o API Python de OpenMM
5. **Análisis e Interpretación** — Gráficas y criterios de evaluación de resultados
6. **Ejercicios Progresivos** — Básico → Intermedio → Avanzado
7. **Recursos Adicionales** — Manuales, tutoriales y referencias

## 🛠️ Herramientas que Aprenderás

### Software de Dinámica Molecular

- **GROMACS** — Motor de DM de alto rendimiento para HPC
  - Preparación de topologías y parámetros
  - Flujo completo: `pdb2gmx → editconf → solvate → genion → grompp → mdrun`
  - Suite completa de herramientas de análisis (`gmx rms`, `gmx rmsf`, `gmx gyrate`, etc.)
  - Soporte para campos de fuerza AMBER, CHARMM, GROMOS, OPLS-AA

- **OpenMM** — Simulación de alto rendimiento en Python
  - API Python intuitiva y flexible
  - Integración directa con NumPy y MDAnalysis
  - Soporte GPU mediante CUDA y OpenCL
  - Campos de fuerza AMBER14, CHARMM36

### Análisis de Trayectorias

- **MDAnalysis** — Biblioteca Python para análisis de trayectorias
  - RMSD, RMSF, radio de giro
  - Análisis de puentes de hidrógeno
  - Lecturas de formatos XTC, DCD, TRR, PDB

### Visualización

- **VMD** — Visualización interactiva de trayectorias moleculares
- **PyMOL** — Generación de figuras de alta calidad

### Bibliotecas Python

- **NumPy / SciPy** — Cálculos numéricos e integradores
- **Matplotlib / Seaborn** — Visualización científica
- **BioPython** — Manipulación de estructuras PDB

## 🎓 Aplicaciones en Ciencias Moleculares

### Biología Estructural
- Estudio de fluctuaciones conformacionales de proteínas
- Análisis de mecanismos de plegamiento
- Simulación de interacciones proteína-ligando en dinámica
- Caracterización de regiones flexibles y rígidas

### Química Farmacéutica
- Refinamiento de poses de docking mediante DM
- Cálculo de energías de unión relativas (MM-GBSA, FEP)
- Predicción de rutas de acceso de ligandos

### Ciencia de Materiales
- Simulación de polímeros y materiales blandos
- Propiedades de membranas lipídicas
- Difusión y transporte en nanomateriales

## 📊 Métricas y Criterios de Calidad

Para evaluar si una simulación es de buena calidad, verifica:

| Propiedad | Criterio aceptable |
|-----------|-------------------|
| Temperatura | T objetivo ± 5 K |
| Presión (NPT) | P objetivo ± 50 bar |
| Densidad (agua) | 0.990–1.005 g/mL a 300 K |
| RMSD proteína | < 3 Å para equilibrio |
| Energía total | Fluctuaciones < 1% |
| Conservación del hamiltoniano (NVE) | Δ E/E < 0.01% |

## 📖 Referencias Fundamentales

1. **Van Der Spoel et al.** (2005) GROMACS: Fast, flexible, and free. *J. Comput. Chem.*, 26, 1701–1718.
2. **Eastman et al.** (2017) OpenMM 7: Rapid development of high performance algorithms for molecular dynamics. *PLOS Comput. Biol.*, 13, e1005659.
3. **Michaud-Agrawal et al.** (2011) MDAnalysis: A toolkit for the analysis of molecular dynamics simulations. *J. Comput. Chem.*, 32, 2319–2327.
4. **Frenkel & Smit** (2002) *Understanding Molecular Simulation: From Algorithms to Applications*. Academic Press.
5. **Allen & Tildesley** (2017) *Computer Simulation of Liquids* (2ª ed.). Oxford University Press.
