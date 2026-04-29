# 🧬 Módulo 4: Modelado de Proteínas y Docking Molecular

<div align="center">

**Universidad de Caldas - Departamento de Química**  
*Introducción a la Química Computacional (173G7G)*  
**Profesor:** José Mauricio Rodas Rodríguez

---

</div>

## 📋 Descripción del Módulo

Este módulo te introduce a las técnicas modernas de modelado de proteínas y docking molecular. Aprenderás desde métodos clásicos de modelado por homología hasta técnicas de vanguardia basadas en inteligencia artificial como AlphaFold2 y ESMFold. Dominarás el docking molecular para estudiar interacciones proteína-ligando y proteína-proteína, herramientas esenciales en el diseño racional de fármacos y la biología estructural computacional.

## 🎯 Objetivos de Aprendizaje

Al completar este módulo, serás capaz de:

- ✅ Comprender y analizar estructuras de proteínas desde bases de datos
- ✅ Construir modelos proteicos por homología con SWISS-MODEL y MODELLER
- ✅ Utilizar herramientas de IA (AlphaFold, ESMFold) para predicción estructural
- ✅ Preparar estructuras de proteínas para estudios de docking
- ✅ Realizar docking molecular ligando-proteína y proteína-proteína
- ✅ Analizar y validar resultados de docking
- ✅ Ejecutar campañas de cribado virtual (virtual screening)
- ✅ Aplicar estas técnicas al diseño racional de fármacos

## 📚 Contenido del Módulo

### Actividades

| # | Actividad | Descripción | Duración |
|---|-----------|-------------|----------|
| **4.1** | [Fundamentos de Estructura de Proteínas](01_fundamentos_estructura_proteinas.ipynb) | PDB, AlphaFold DB, visualización y análisis básico | 2-3 horas |
| **4.2** | [Modelado por Homología](02_modelado_homologia.ipynb) | BLAST, SWISS-MODEL, validación con Ramachandran | 3-4 horas |
| **4.3** | [AlphaFold y ESMFold](03_alphafold_esmfold.ipynb) | ColabFold, predicción con IA, métricas de confianza | 3-4 horas |
| **4.4** | [Preparación de Proteínas](04_preparacion_proteinas.ipynb) | Limpieza, adición de H, asignación de cargas | 2-3 horas |
| **4.5** | [Fundamentos de Docking](05_docking_fundamentos.ipynb) | Teoría, sampling, funciones de scoring | 2-3 horas |
| **4.6** | [Docking Ligando-Proteína](06_docking_ligando_proteina.ipynb) | AutoDock Vina, análisis de poses y energías | 3-4 horas |
| **4.7** | [Docking Proteína-Proteína](07_docking_proteina_proteina.ipynb) | HADDOCK, ClusPro, análisis de interfaces | 3-4 horas |
| **4.8** | [Cribado Virtual](08_virtual_screening.ipynb) | Virtual screening, filtros ADME, priorización | 3-4 horas |

**Duración total estimada:** 21-29 horas

## 🚀 Cómo Usar Este Módulo

### Requisitos Previos

- ✅ **Módulo 1 completado** - Fundamentos computacionales
- ✅ **Módulo 2 completado** - Representación molecular
- ✅ **Módulo 3 completado** - Mecánica molecular
- ✅ Python 3.8+ instalado
- ✅ Jupyter Notebook o Google Colab
- ✅ Conocimientos básicos de bioquímica de proteínas

### Orden Recomendado

Las actividades están diseñadas para seguirse **secuencialmente**:

```
4.1 → 4.2 → 4.3 → 4.4 → 4.5 → 4.6 → 4.7 → 4.8
```

### Instalación de Dependencias

Para trabajar localmente, instala las bibliotecas necesarias:

```bash
# Opción 1: Conda (Recomendado)
conda create -n modulo4_proteinas python=3.11
conda activate modulo4_proteinas
conda install -c conda-forge rdkit openbabel biopython
pip install py3Dmol nglview ProLIF mdanalysis

# Para AutoDock Vina
conda install -c conda-forge vina

# Opción 2: pip
pip install biopython py3Dmol rdkit-pypi requests numpy pandas matplotlib
```

**Nota:** AlphaFold y ESMFold requieren recursos computacionales significativos. Se recomienda usar Google Colab o servidores web especializados.

## � Estructura de las Actividades

Cada actividad incluye:

1. **Introducción** - Contexto y relevancia en biología estructural
2. **Conceptos Fundamentales** - Teoría esencial de modelado y docking
3. **Ejemplos Prácticos** - Código ejecutable con proteínas reales
4. **Casos de Uso** - Aplicaciones en diseño de fármacos
5. **Ejercicios Progresivos** - Básico → Intermedio → Avanzado
6. **Recursos Adicionales** - Documentación y tutoriales

## 🛠️ Herramientas que Aprenderás

### Modelado de Proteínas

- **AlphaFold2 / ColabFold** - Predicción de estructuras con IA
  - Implementación optimizada para Google Colab
  - Métricas de confianza (pLDDT, PAE)
  - Predicción de complejos
  
- **ESMFold** - Predicción ultra-rápida basada en transformers
  - Predicción sin MSA (Multiple Sequence Alignment)
  - API pública para uso sencillo
  
- **SWISS-MODEL** - Servidor web para modelado por homología
  - Búsqueda automática de templates
  - Validación de modelos
  
- **MODELLER** - Modelado comparativo avanzado
  - Control detallado del proceso
  - Refinamiento de loops

### Docking Molecular

- **AutoDock Vina** - El estándar en docking ligando-proteína
  - Algoritmo de búsqueda eficiente
  - Función de scoring empírica
  - Soporte para flexibilidad del ligando
  
- **HADDOCK** - Docking proteína-proteína guiado por datos
  - Incorporación de información experimental
  - Refinamiento en solvente
  
- **ClusPro** - Servidor web para docking proteína-proteína
  - Algoritmo FFT para búsqueda rápida
  - Múltiples funciones de scoring

### Visualización y Análisis

- **PyMOL** - Visualización profesional de proteínas
  - Representaciones de alta calidad
  - Análisis de interacciones
  
- **Py3Dmol** - Visualización interactiva en notebooks
  - Coloreado por pLDDT
  - Animaciones de modelos
  
- **ProLIF** - Análisis de interacciones proteína-ligando
  - Fingerprints de interacción
  - Visualización de diagramas 2D

### Python Libraries

- **BioPython** - Manipulación de estructuras PDB
  - Parser de archivos PDB
  - Análisis de estructura secundaria
  - Cálculo de RMSD
  
- **RDKit** - Preparación de ligandos
  - Generación de conformaciones
  - Cálculo de propiedades ADME
  
- **MDAnalysis** - Análisis de estructuras y trayectorias
  - Selección avanzada de átomos
  - Cálculos geométricos

## 🎓 Aplicaciones en Biología y Química

### Diseño Racional de Fármacos
- Identificación de cavidades de unión en proteínas diana
- Optimización de compuestos líder mediante docking
- Predicción de afinidad de unión
- Cribado virtual de bibliotecas moleculares

### Biología Estructural
- Predicción de estructuras de proteínas sin homólogos conocidos
- Estudio de interacciones proteína-proteína
- Análisis de mecanismos de señalización celular
- Diseño de proteínas terapéuticas

### Química Medicinal
- Análisis de relaciones estructura-actividad (SAR)
- Optimización de propiedades ADME
- Predicción de selectividad entre targets
- Desarrollo de inhibidores específicos

### Bioquímica Computacional
- Estudio de sitios activos enzimáticos
- Predicción de efectos de mutaciones
- Análisis de evolución estructural
- Diseño de experimentos de cristalografía

## 💡 Consejos para el Éxito

1. **Entiende la Biología** - El modelado es más efectivo cuando comprendes el sistema
2. **Valida Siempre** - Usa múltiples métricas para evaluar modelos y docking
3. **Visualiza en 3D** - La intuición espacial es crucial en biología estructural
4. **Compara Métodos** - AlphaFold vs homología, diferentes funciones de scoring
5. **Documenta Parámetros** - Registra configuraciones para reproducibilidad
6. **Itera y Refina** - Los primeros resultados raramente son los finales

## 📖 Recursos Complementarios

### Documentación Oficial
- [AlphaFold Documentation](https://github.com/deepmind/alphafold)
- [ColabFold](https://github.com/sokrypton/ColabFold)
- [AutoDock Vina Documentation](http://vina.scripps.edu/)
- [BioPython Tutorial](https://biopython.org/wiki/Documentation)
- [PyMOL Wiki](https://pymolwiki.org/)
- [ProLIF Documentation](https://prolif.readthedocs.io/)

### Bases de Datos
- [Protein Data Bank (PDB)](https://www.rcsb.org/) - Estructuras experimentales
- [AlphaFold Database](https://alphafold.ebi.ac.uk/) - Predicciones de AlphaFold
- [PubChem](https://pubchem.ncbi.nlm.nih.gov/) - Moléculas pequeñas
- [ChEMBL](https://www.ebi.ac.uk/chembl/) - Datos de bioactividad
- [ZINC Database](https://zinc.docking.org/) - Compuestos para virtual screening
- [UniProt](https://www.uniprot.org/) - Secuencias de proteínas

### Tutoriales Recomendados
- [ColabFold Tutorial](https://colab.research.google.com/github/sokrypton/ColabFold/blob/main/AlphaFold2.ipynb)
- [AutoDock Vina Tutorial](http://vina.scripps.edu/tutorial.html)
- [PyMOL Tutorials](https://pymolwiki.org/index.php/Practical_Pymol_for_Beginners)
- [HADDOCK Tutorial](https://www.bonvinlab.org/education/HADDOCK24/)

### Artículos Clave
- Jumper et al. (2021). *AlphaFold2*. Nature 596, 583–589
- Lin et al. (2023). *ESMFold*. Science 379, 1123-1130
- Trott & Olson (2010). *AutoDock Vina*. J. Comp. Chem. 31, 455-461
- Waterhouse et al. (2018). *SWISS-MODEL*. Nucleic Acids Research

### Libros de Referencia
- *Protein Structure Prediction* - Mohammed Yakoob Sirajuddin
- *Molecular Docking: From Lock and Key to Combination Lock* - Andrew R. Leach
- *Computational Drug Discovery and Design* - Riccardo Baron

## 🆘 Soporte y Ayuda

### Problemas Técnicos
- Revisa la sección de **Troubleshooting** en cada actividad
- Consulta los **Issues** en el repositorio de GitHub
- Contacta al profesor: mauricio.rodas@ucaldas.edu.co

### Errores Comunes

#### AlphaFold se queda sin memoria en Colab
**Solución:** Usa Colab Pro o reduce el tamaño de la proteína
```python
# Limita el número de secuencias en el MSA
max_msa = "128:256"
```

#### AutoDock Vina no encuentra el sitio activo
**Solución:** Verifica las coordenadas del grid box
```bash
# Usa coordenadas del centro del ligando de referencia
center_x = X, center_y = Y, center_z = Z
size_x = 20, size_y = 20, size_z = 20
```

#### BioPython no lee archivos PDB correctamente
**Solución:** Limpia el archivo PDB primero
```python
from Bio.PDB import PDBParser, PDBIO, Select
# Usa Select para filtrar solo átomos necesarios
```

## 🔬 Proyecto del Módulo

Al finalizar este módulo, serás capaz de completar un proyecto integrador:

**"Diseño Computacional de un Inhibidor Proteico"**

Incluirá:
- Obtención o predicción de estructura de proteína diana
- Preparación de la proteína para docking
- Búsqueda de ligandos en bases de datos
- Campaña de virtual screening
- Análisis de interacciones de los mejores hits
- Propuesta de optimización estructural

## 🔄 Actualizaciones

Este módulo se actualiza periódicamente. Última actualización: **Abril 2026**

## 📝 Licencia

Este material educativo está disponible bajo licencia [GNU General Public License v3.0 (GPL-3.0)](../LICENSE).

---

## 🎯 Próximos Pasos

Una vez completado el Módulo 4, estarás listo para:

- **Módulo 5:** Dinámica Molecular
- **Módulo 6:** Mecánica Cuántica Computacional
- **Módulo 7:** Métodos Semiempíricos

---

<div align="center">

📚 **[← Módulo 3: Mecánica Molecular](../modulo_03_mecanica_molecular/)** | **[Módulo 5: Dinámica Molecular →](../modulo_05_dinamica_molecular/)** | **[Inicio del Curso](../README.md)**

**Universidad de Caldas - Departamento de Química**  
*Química Computacional 173G7G*

</div>
