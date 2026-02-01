<table width="100%">
<tr>
<td width="15%">
  <img src="recursos/imagenes/ucaldas_logo.png" alt="Universidad de Caldas" width="120"/>
</td>
<td width="85%">
  
# Introducción a la Química Computacional
### Código: 173G7G

**Universidad de Caldas**  
*Facultad de Ciencias Exactas y Naturales - Departamento de Química*

</td>
</tr>
</table>

<div align="center">
  
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)
![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![License](https://img.shields.io/badge/License-Educational-green.svg)
![Status](https://img.shields.io/badge/Status-Active-success.svg)

</div>

---

## 📚 Descripción del Curso

Este repositorio contiene el **material práctico completo** del curso de Introducción a la Química Computacional. Todos los ejercicios y actividades están diseñados para ejecutarse en **Google Colab** o localmente con **Jupyter Notebooks**, utilizando exclusivamente **software libre y de código abierto**.

### 🎯 Objetivos del Curso
- Comprender los fundamentos teóricos de la química computacional
- Aplicar métodos computacionales para resolver problemas químicos
- Desarrollar habilidades en programación científica con Python
- Utilizar herramientas de simulación molecular modernas
- Interpretar y visualizar resultados de cálculos computacionales

## 📋 Contenido del Curso

El curso está diseñado con un **aprendizaje secuencial progresivo**, donde cada módulo construye sobre los conocimientos del anterior.

### Módulo 1: Fundamentos Computacionales
**Objetivo:** Dominar las herramientas básicas de trabajo computacional
1. [Uso de consolas y línea de comandos](modulo_01_fundamentos/01_uso_consolas.ipynb)
2. [Editores de texto plano (nano, vim, VSCode)](modulo_01_fundamentos/02_editores_texto.ipynb)
3. [Python para química computacional](modulo_01_fundamentos/03_python_quimica.ipynb)
4. [Scripting básico en Bash y Python](modulo_01_fundamentos/04_scripting_basico.ipynb)
5. [Control de versiones con Git y GitHub](modulo_01_fundamentos/05_control_versiones.ipynb)
6. [Manipulación de datos con pandas y numpy](modulo_01_fundamentos/06_pandas_numpy.ipynb)
7. [Visualización de datos científicos (matplotlib, plotly)](modulo_01_fundamentos/07_visualizacion_datos.ipynb)
8. [Entornos virtuales y reproducibilidad científica (conda, venv)](modulo_01_fundamentos/08_entornos_virtuales.ipynb)

### Módulo 2: Representación y Visualización Molecular
**Objetivo:** Comprender cómo representar y visualizar moléculas computacionalmente
1. [Formatos de archivos moleculares (XYZ, PDB, MOL2, SDF)](modulo_02_representacion_molecular/01_formatos_moleculares.ipynb)
2. [Notaciones químicas (SMILES, InChI, SMARTS)](modulo_02_representacion_molecular/02_notaciones_quimicas.ipynb)
3. [Bibliotecas de química computacional (RDKit, Open Babel)](modulo_02_representacion_molecular/03_rdkit_openbabel.ipynb)
4. [Visualización 3D de moléculas (Py3Dmol, NGLView, Avogadro, Chimera)](modulo_02_representacion_molecular/04_visualizacion_3d.ipynb)
5. [Generación de conformaciones moleculares](modulo_02_representacion_molecular/05_conformaciones.ipynb)
6. [Descriptores moleculares y propiedades calculadas](modulo_02_representacion_molecular/06_descriptores.ipynb)
7. [Búsqueda y descarga de estructuras (PubChem, PDB)](modulo_02_representacion_molecular/07_bases_datos.ipynb)

### Módulo 3: Mecánica Molecular
**Objetivo:** Entender y aplicar métodos clásicos de simulación molecular
1. [Fundamentos de Mecánica Molecular](modulo_03_mecanica_molecular/01_fundamentos_mecanica_molecular.ipynb)
2. [Campos de fuerza en la práctica](modulo_03_mecanica_molecular/02_campos_fuerza_practica.ipynb)
3. [Optimización de geometrías moleculares](modulo_03_mecanica_molecular/03_optimizacion_geometrias.ipynb)
4. Superficies de energía potencial
5. Análisis conformacional
6. Cálculo de propiedades moleculares
7. Software especializado (OpenBabel, RDKit, Avogadro)
8. Validación de resultados

### Módulo 4: Modelado de Proteínas y Docking Molecular
**Objetivo:** Aplicar técnicas modernas de modelado de proteínas y docking molecular
1. [Fundamentos de estructura de proteínas](modulo_04_modelado_proteinas_docking/01_fundamentos_estructura_proteinas.ipynb)
2. [Modelado por homología (MODELLER, SWISS-MODEL)](modulo_04_modelado_proteinas_docking/02_modelado_homologia.ipynb)
3. [Predicción con IA: AlphaFold2 y ESMFold](modulo_04_modelado_proteinas_docking/03_alphafold_esmfold.ipynb)
4. Preparación de proteínas para docking
5. Fundamentos de docking molecular
6. Docking ligando-proteína (AutoDock Vina)
7. Docking proteína-proteína
8. Cribado virtual y análisis de resultados

### Módulo 5: Dinámica Molecular
**Objetivo:** Simular el movimiento de moléculas en el tiempo
1. Fundamentos de dinámica molecular
2. Integradores y algoritmos (Verlet, Leap-Frog)
3. Condiciones de contorno y ensemble
4. Termostatos y barostatos (NVE, NVT, NPT)
5. Preparación de sistemas (solvatación, iones)
6. Simulación de proteínas y biomoléculas
7. Análisis de trayectorias (RMSD, RMSF, energías)
8. Práctica con GROMACS y/o OpenMM

### Módulo 6: Mecánica Cuántica Computacional
**Objetivo:** Fundamentos teóricos de métodos cuánticos
1. Ecuación de Schrödinger y función de onda
2. Operador hamiltoniano y observables
3. Aproximación de Born-Oppenheimer
4. Orbitales atómicos y moleculares
5. Teoría de Hückel para sistemas π
6. Implementación computacional de Hückel
7. Visualización de orbitales moleculares

### Módulo 7: Métodos Semiempíricos
**Objetivo:** Aplicar métodos cuánticos aproximados eficientes
1. Filosofía de los métodos semiempíricos
2. Aproximaciones NDDO, INDO, CNDO
3. Métodos modernos: AM1, PM3, PM6, PM7
4. Aplicaciones: moléculas orgánicas y biológicas
5. Cálculos con MOPAC
6. Ventajas y limitaciones
7. Casos de estudio comparativos

### Módulo 8: Métodos Ab-initio y DFT
**Objetivo:** Realizar cálculos cuánticos de alta precisión
1. Filosofía Ab-initio
2. Método de Hartree-Fock (HF)
3. Conjuntos de funciones base (STO, GTO, bases mínimas y extendidas)
4. Convergencia SCF y técnicas de aceleración
5. Teoría del Funcional de la Densidad (DFT)
6. Funcionales de intercambio-correlación (LDA, GGA, híbridos)
7. Métodos post-HF: teoría de perturbaciones (MP2)
8. Coupled Cluster (CCSD, CCSD(T))
9. Sistemas de capa abierta y multiplicidades
10. Cálculos con Psi4, ORCA o Gaussian
11. Análisis de resultados y propiedades moleculares

### Módulo 9: Temas Avanzados (Opcional)
**Objetivo:** Explorar aplicaciones especializadas
1. Cálculo de estados excitados (TD-DFT, CIS)
2. Modelos de solvatación (implícitos y explícitos)
3. Análisis topológico de la densidad electrónica (QTAIM)
4. Orbitales naturales de enlace (NBO)
5. Espectroscopía computacional (IR, UV-Vis, NMR)
6. Cálculo de constantes de velocidad
7. Estudios de mecanismos de reacción
8. Proyecto integrador final


## 🚀 Cómo Usar Este Repositorio

### ☁️ Opción 1: Ejecutar en Google Colab (Recomendado)
La forma más sencilla de trabajar con estos materiales es usar Google Colab:
1. Navega a la carpeta del módulo que deseas estudiar
2. Haz clic en el botón **"Open in Colab"** en cada notebook
3. El notebook se abrirá directamente en tu navegador
4. ¡Listo para ejecutar! No requiere instalación

### 💻 Opción 2: Ejecutar localmente
Si prefieres trabajar en tu computadora:
1. **Clona este repositorio:**
   ```bash
   git clone https://github.com/maurorodas/Quimica_computacional_173G7G.git
   cd Quimica_computacional_173G7G
   ```
2. **Instala las dependencias:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Inicia Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

### 🐧 Opción 3: Usando scripts de Bash
Para algunas actividades de línea de comandos:
```bash
bash scripts/nombre_del_script.sh
```

## 📁 Estructura del Repositorio

```
Quimica_Computacional_173G7G/
├── README.md
├── requirements.txt
├── LICENSE
│
├── modulo_01_fundamentos/
│   ├── README.md
│   ├── 01_uso_consolas.ipynb
│   ├── 02_editores_texto.ipynb
│   ├── 03_python_quimica.ipynb
│   ├── 04_scripting_basico.ipynb
│   ├── 05_control_versiones.ipynb
│   ├── 06_pandas_numpy.ipynb
│   └── 07_visualizacion_datos.ipynb
│
├── modulo_02_representacion_molecular/
│   ├── README.md
│   ├── 01_formatos_moleculares.ipynb
│   ├── 02_notaciones_quimicas.ipynb
│   ├── 03_rdkit_openbabel.ipynb
│   ├── 04_visualizacion_3d.ipynb
│   ├── 05_conformaciones.ipynb
│   ├── 06_descriptores_moleculares.ipynb
│   └── 07_bases_datos_quimicas.ipynb
│
├── modulo_03_mecanica_molecular/
│   ├── README.md
│   ├── 01_introduccion_campos_fuerza.ipynb
│   ├── 02_componentes_energia.ipynb
│   ├── 03_campos_fuerza_comunes.ipynb
│   ├── 04_optimizacion_geometrias.ipynb
│   ├── 05_analisis_conformacional.ipynb
│   ├── 06_frecuencias_vibraciones.ipynb
│   └── 07_termodinamica_estadistica.ipynb
│
├── modulo_04_modelado_proteinas_docking/
│   ├── README.md
│   ├── 01_fundamentos_estructura_proteinas.ipynb
│   ├── 02_modelado_homologia.ipynb
│   ├── 03_alphafold_esmfold.ipynb
│   ├── 04_preparacion_proteinas.ipynb
│   ├── 05_docking_fundamentos.ipynb
│   ├── 06_docking_ligando_proteina.ipynb
│   ├── 07_docking_proteina_proteina.ipynb
│   └── 08_virtual_screening.ipynb
│
├── modulo_05_dinamica_molecular/
│   ├── README.md
│   ├── 01_fundamentos_md.ipynb
│   ├── 02_integradores_algoritmos.ipynb
│   ├── 03_condiciones_ensemble.ipynb
│   ├── 04_termostatos_barostatos.ipynb
│   ├── 05_preparacion_sistemas.ipynb
│   ├── 06_simulacion_biomoleculas.ipynb
│   ├── 07_analisis_trayectorias.ipynb
│   └── 08_practica_gromacs_openmm.ipynb
│
├── modulo_06_mecanica_cuantica/
│   ├── README.md
│   ├── 01_ecuacion_schrodinger.ipynb
│   ├── 02_hamiltoniano_observables.ipynb
│   ├── 03_born_oppenheimer.ipynb
│   ├── 04_orbitales_atomicos_moleculares.ipynb
│   ├── 05_teoria_huckel.ipynb
│   ├── 06_implementacion_huckel.ipynb
│   └── 07_visualizacion_orbitales.ipynb
│
├── modulo_07_metodos_semiempiricos/
│   ├── README.md
│   ├── 01_introduccion_semiempiricos.ipynb
│   ├── 02_aproximaciones_nddo.ipynb
│   ├── 03_metodos_modernos.ipynb
│   ├── 04_aplicaciones_organicas.ipynb
│   ├── 05_calculos_mopac.ipynb
│   ├── 06_ventajas_limitaciones.ipynb
│   └── 07_casos_estudio.ipynb
│
├── modulo_08_abinitio_dft/
│   ├── README.md
│   ├── 01_filosofia_abinitio.ipynb
│   ├── 02_hartree_fock.ipynb
│   ├── 03_funciones_base.ipynb
│   ├── 04_convergencia_scf.ipynb
│   ├── 05_introduccion_dft.ipynb
│   ├── 06_funcionales_dft.ipynb
│   ├── 07_metodos_post_hf.ipynb
│   ├── 08_coupled_cluster.ipynb
│   ├── 09_sistemas_capa_abierta.ipynb
│   ├── 10_calculos_psi4_orca.ipynb
│   └── 11_analisis_propiedades.ipynb
│
├── modulo_09_temas_avanzados/
│   ├── README.md
│   ├── 01_estados_excitados.ipynb
│   ├── 02_modelos_solvatacion.ipynb
│   ├── 03_qtaim.ipynb
│   ├── 04_analisis_nbo.ipynb
│   ├── 05_espectroscopia_computacional.ipynb
│   ├── 06_constantes_velocidad.ipynb
│   ├── 07_mecanismos_reaccion.ipynb
│   └── 08_proyecto_integrador.ipynb
│
└── recursos/
    ├── datos/
    │   ├── moleculas/
    │   ├── trayectorias/
    │   └── espectros/
    ├── imagenes/
    ├── scripts/
    └── referencias/
```


## 🛠️ Software y Herramientas

Este curso utiliza exclusivamente **software libre y de código abierto**:

### Lenguajes de Programación
- ![Python](https://img.shields.io/badge/Python-3.8+-3776AB?logo=python&logoColor=white) - Lenguaje principal
- ![Bash](https://img.shields.io/badge/Bash-4EAA25?logo=gnu-bash&logoColor=white) - Scripts de automatización

### Librerías Científicas Python
| Librería | Propósito | Instalación |
|----------|-----------|-------------|
| **NumPy** | Cálculos numéricos y arrays | `pip install numpy` |
| **SciPy** | Algoritmos científicos avanzados | `pip install scipy` |
| **Matplotlib** | Visualización 2D de datos | `pip install matplotlib` |
| **Plotly** | Visualización interactiva | `pip install plotly` |
| **Pandas** | Manipulación y análisis de datos | `pip install pandas` |
| **Jupyter** | Notebooks interactivos | `pip install jupyter` |

### Química Computacional
| Librería | Propósito | Instalación |
|----------|-----------|-------------|
| **RDKit** | Química e informática molecular | `conda install -c conda-forge rdkit` |
| **Open Babel** | Conversión de formatos moleculares | `conda install -c conda-forge openbabel` |
| **ASE** | Atomic Simulation Environment | `pip install ase` |
| **Py3Dmol** | Visualización 3D en notebooks | `pip install py3dmol` |
| **MDAnalysis** | Análisis de dinámica molecular | `pip install MDAnalysis` |
| **ProDy** | Análisis de proteínas | `pip install ProDy` |

### Software de Cálculo Cuántico
| Software | Propósito | Instalación |
|----------|-----------|-------------|
| **Psi4** | Cálculos ab-initio y DFT | `conda install -c psi4 psi4` |
| **PySCF** | Química cuántica en Python | `pip install pyscf` |
| **ORCA** | Cálculos cuánticos (gratuito académico) | [Descarga manual](https://orcaforum.kofo.mpg.de/) |
| **MOPAC** | Métodos semiempíricos | [Descarga manual](http://openmopac.net/) |
| **XTB** | Cálculos tight-binding | `conda install -c conda-forge xtb` |

### Dinámica Molecular
| Software | Propósito | Instalación |
|----------|-----------|-------------|
| **GROMACS** | Simulaciones MD de biomoléculas | Sistema dependiente |
| **OpenMM** | MD en Python con GPU | `conda install -c conda-forge openmm` |
| **LAMMPS** | MD de propósito general | Sistema dependiente |
| **NAMD** | MD de biomoléculas grandes | [Descarga manual](https://www.ks.uiuc.edu/Research/namd/) |

### Visualización Molecular
| Software | Propósito | Acceso |
|----------|-----------|--------|
| **PyMOL** | Visualización avanzada (versión open-source) | `conda install -c conda-forge pymol-open-source` |
| **VMD** | Visual Molecular Dynamics | [Descarga gratuita](https://www.ks.uiuc.edu/Research/vmd/) |
| **Avogadro** | Editor y visualizador molecular | [Descarga gratuita](https://avogadro.cc/) |
| **NGLView** | Visualización en notebooks | `pip install nglview` |


## 📝 Contribuciones y Retroalimentación

¿Encontraste un error o tienes una sugerencia para mejorar el material? 

- 📧 Abre un **Issue** en GitHub
- 🔧 Envía un **Pull Request** con tus mejoras
- 💬 Comparte tu experiencia y sugerencias

Todas las contribuciones son bienvenidas y ayudan a mejorar este curso para futuros estudiantes.

---

## 📄 Licencia

Este material educativo está disponible bajo licencia [GNU General Public License v3.0 (GPL-3.0)](LICENSE).

Se permite su uso, modificación y distribución con propósitos académicos y educativos,  
siempre que se cite apropiadamente la fuente y se mantenga la misma licencia.

📚 **Curso:** Introducción a la Química Computacional (173G7G)  
🏛️ **Institución:** Universidad de Caldas  
📅 **Año:** 2026

---

## 👨‍🏫 Información del Curso

**Profesor:** José Mauricio Rodas Rodríguez  
**Cargo:** Profesor Asociado  
**Departamento:** Departamento de Química, Universidad de Caldas  
**Correo:** mauricio.rodas@ucaldas.edu.co  
**Horario:** Miércoles 2:00 PM - 6:00 PM  
**Aula:** U-102

---

<div align="center">

### 💡 ¿Listo para comenzar?

Explora los módulos en orden secuencial o dirígete directamente al tema de tu interés.  
¡La química computacional te espera!

**[📖 Comenzar con el Módulo 1: Fundamentos Computacionales](modulo_01_fundamentos/)**

**[🧬 Continuar con el Módulo 2: Representación y Visualización Molecular](modulo_02_representacion_molecular/)**

---

### 📊 Ruta de Aprendizaje Sugerida

```
Módulo 1 (Fundamentos) → Módulo 2 (Representación) → Módulo 3 (MM) 
                                                           ↓
Módulo 8 (Avanzados) ← Módulo 7 (Ab-initio/DFT) ← Módulo 6 (Semiempíricos)
                                                           ↑
                                                    Módulo 5 (MC)
                                                           ↑
                                                    Módulo 4 (MD)
```

**Tiempo estimado por módulo:** 2-3 semanas  
**Duración total del curso:** 16-18 semanas (1 semestre)

---

*Universidad de Caldas - 2026*

</div>
