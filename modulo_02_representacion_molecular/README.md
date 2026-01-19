# 🧬 Módulo 2: Representación y Visualización Molecular

<div align="center">

**Universidad de Caldas - Departamento de Química**  
*Introducción a la Química Computacional (173G7G)*  
**Profesor:** José Mauricio Rodas Rodríguez

---

</div>

## 📋 Descripción del Módulo

Este módulo te introduce al mundo de la representación computacional de moléculas. Aprenderás a leer, escribir, manipular y visualizar estructuras moleculares utilizando diversos formatos y herramientas computacionales. Dominarás las bibliotecas fundamentales de química computacional (RDKit y OpenBabel) y serás capaz de generar, analizar y visualizar moléculas en 2D y 3D.

## 🎯 Objetivos de Aprendizaje

Al completar este módulo, serás capaz de:

- ✅ Comprender y trabajar con diferentes formatos de archivos moleculares
- ✅ Usar notaciones químicas (SMILES, InChI, SMARTS) para representar moléculas
- ✅ Manipular estructuras moleculares con RDKit y OpenBabel
- ✅ Crear visualizaciones interactivas 3D de moléculas
- ✅ Generar y analizar conformaciones moleculares
- ✅ Calcular descriptores y propiedades moleculares
- ✅ Acceder y descargar estructuras desde bases de datos químicas

## 📚 Contenido del Módulo

### Actividades

| # | Actividad | Descripción | Duración |
|---|-----------|-------------|----------|
| **2.1** | [Formatos de Archivos Moleculares](01_formatos_moleculares.ipynb) | XYZ, PDB, MOL2, SDF - Lectura y escritura | 2-3 horas |
| **2.2** | [Notaciones Químicas](02_notaciones_quimicas.ipynb) | SMILES, InChI, SMARTS - Representación textual | 2-3 horas |
| **2.3** | [RDKit y OpenBabel](03_rdkit_openbabel.ipynb) | Bibliotecas esenciales de química computacional | 3-4 horas |
| **2.4** | [Visualización 3D](04_visualizacion_3d.ipynb) | Py3Dmol, NGLView - Visualización interactiva | 2-3 horas |
| **2.5** | [Generación de Conformaciones](05_conformaciones.ipynb) | Búsqueda conformacional y análisis energético | 3-4 horas |
| **2.6** | [Descriptores Moleculares](06_descriptores_moleculares.ipynb) | Propiedades calculadas y caracterización molecular | 3-4 horas |
| **2.7** | [Bases de Datos Químicas](07_bases_datos_quimicas.ipynb) | PubChem, PDB - Búsqueda y descarga de estructuras | 2-3 horas |

**Duración total estimada:** 17-24 horas

## 🚀 Cómo Usar Este Módulo

### Requisitos Previos

- ✅ **Módulo 1 completado** - Fundamentos computacionales
- ✅ Python 3.8+ instalado
- ✅ Jupyter Notebook o Google Colab
- ✅ Conocimientos básicos de química orgánica

### Orden Recomendado

Las actividades están diseñadas para seguirse **secuencialmente**:

```
2.1 → 2.2 → 2.3 → 2.4 → 2.5 → 2.6 → 2.7
```

### Instalación de Dependencias

Para trabajar localmente, instala las bibliotecas necesarias:

```bash
# Opción 1: Conda (Recomendado)
conda create -n modulo2_quimica python=3.11
conda activate modulo2_quimica
conda install -c conda-forge rdkit openbabel py3dmol
pip install nglview biopython requests

# Opción 2: pip (algunas limitaciones)
pip install py3dmol nglview biopython requests
# Nota: RDKit y OpenBabel se instalan mejor con conda
```

## 📊 Estructura de las Actividades

Cada actividad incluye:

1. **Introducción** - Contexto y relevancia del tema
2. **Conceptos Fundamentales** - Teoría esencial
3. **Ejemplos Prácticos** - Código ejecutable con moléculas reales
4. **Casos de Uso en Química** - Aplicaciones concretas
5. **Ejercicios Progresivos** - Básico → Intermedio → Avanzado
6. **Recursos Adicionales** - Documentación y material complementario

## 🛠️ Herramientas que Aprenderás

### Bibliotecas Python

- **RDKit** - La biblioteca más completa para química computacional
  - Lectura/escritura de formatos moleculares
  - Generación de conformaciones
  - Cálculo de descriptores
  - Búsqueda de subestructuras
  
- **OpenBabel** - Conversión entre formatos y análisis molecular
  - Conversión de ~100 formatos químicos
  - Optimización de geometrías
  - Generación de coordenadas 3D
  
- **Py3Dmol** - Visualización 3D interactiva en notebooks
  - Modelos CPK, stick, cartoon, surface
  - Coloreado por propiedades
  - Animaciones de conformaciones
  
- **NGLView** - Visualizador molecular avanzado
  - Compatible con trayectorias MD
  - Representaciones múltiples
  - Exportación de imágenes

### Formatos de Archivos

| Formato | Uso Principal | Información |
|---------|---------------|-------------|
| **XYZ** | Geometrías simples | Coordenadas atómicas básicas |
| **PDB** | Biomoléculas | Proteínas, ácidos nucleicos |
| **MOL/MOL2** | Moléculas orgánicas | Incluye conectividad y tipos de átomo |
| **SDF** | Bases de datos | Múltiples moléculas con propiedades |
| **CIF** | Cristalografía | Datos cristalográficos |

### Notaciones Químicas

- **SMILES** - Simplified Molecular Input Line Entry System
  - Representación lineal de estructuras
  - Fácil de leer y escribir
  
- **InChI** - International Chemical Identifier
  - Identificador único universal
  - Ideal para búsquedas en bases de datos
  
- **SMARTS** - SMiles ARbitrary Target Specification
  - Patrones para búsqueda de subestructuras
  - Filtrado de bibliotecas moleculares

## 🎓 Aplicaciones en Química

### Diseño de Fármacos
- Búsqueda de moléculas similares a un compuesto líder
- Análisis de propiedades ADME
- Filtrado de bibliotecas virtuales

### Química Orgánica
- Visualización de mecanismos de reacción
- Análisis conformacional de productos
- Predicción de propiedades físicas

### Bioquímica
- Análisis de estructuras de proteínas
- Estudio de sitios activos
- Diseño de ligandos

### Química Computacional
- Preparación de geometrías para cálculos
- Análisis de resultados de simulaciones
- Documentación de estudios

## 💡 Consejos para el Éxito

1. **Practica con Moléculas Reales** - Usa ejemplos de tu área de interés
2. **Explora las Bases de Datos** - PubChem y PDB tienen millones de estructuras
3. **Visualiza Frecuentemente** - La intuición 3D es fundamental
4. **Documenta tu Código** - Anota qué hace cada paso
5. **Experimenta con Parámetros** - Cambia valores y observa resultados
6. **Comparte Visualizaciones** - Las imágenes ayudan a entender conceptos

## 📖 Recursos Complementarios

### Documentación Oficial
- [RDKit Documentation](https://www.rdkit.org/docs/)
- [RDKit Cookbook](https://www.rdkit.org/docs/Cookbook.html)
- [OpenBabel Documentation](https://openbabel.org/docs/dev/)
- [Py3Dmol Documentation](https://3dmol.csb.pitt.edu/)
- [NGLView Documentation](http://nglviewer.org/nglview/latest/)

### Bases de Datos Químicas
- [PubChem](https://pubchem.ncbi.nlm.nih.gov/) - Millones de moléculas pequeñas
- [Protein Data Bank (PDB)](https://www.rcsb.org/) - Estructuras de biomoléculas
- [ChEMBL](https://www.ebi.ac.uk/chembl/) - Datos de bioactividad
- [ZINC](https://zinc.docking.org/) - Moléculas comerciales para screening

### Tutoriales Recomendados
- [RDKit Getting Started](https://www.rdkit.org/docs/GettingStartedInPython.html)
- [Molecular Descriptors Tutorial](https://www.rdkit.org/docs/GettingStartedInPython.html#list-of-available-descriptors)
- [SMILES Tutorial](https://www.daylight.com/dayhtml/doc/theory/theory.smiles.html)

### Libros de Referencia
- *Chemoinformatics: A Textbook* - Johann Gasteiger
- *Molecular Modeling: Principles and Applications* - Andrew R. Leach
- *Introduction to Cheminformatics* - A. R. Leach, V. J. Gillet

## 🆘 Soporte y Ayuda

### Problemas Técnicos
- Revisa la sección de **Troubleshooting** en cada actividad
- Consulta los **Issues** en el repositorio de GitHub
- Contacta al profesor: mauricio.rodas@ucaldas.edu.co

### Errores Comunes

#### RDKit no se instala con pip
**Solución:** Usa conda
```bash
conda install -c conda-forge rdkit
```

#### NGLView no muestra moléculas
**Solución:** Habilita las extensiones de Jupyter
```bash
jupyter nbextension enable --py widgetsnbextension
jupyter nbextension enable --py nglview
```

#### Problemas con SMILES inválidos
**Solución:** Verifica la sintaxis en [SMILES Generator](https://www.cheminfo.org/Chemistry/Cheminformatics/FormatConverter/index.html)

## 🔬 Proyecto del Módulo

Al finalizar este módulo, serás capaz de completar un proyecto integrador:

**"Análisis Computacional de una Familia de Compuestos"**

Incluirá:
- Descarga de estructuras desde PubChem
- Conversión entre formatos
- Generación de conformaciones
- Cálculo de descriptores moleculares
- Visualización 3D interactiva
- Análisis de relaciones estructura-propiedad

## 🔄 Actualizaciones

Este módulo se actualiza periódicamente. Última actualización: **Enero 2026**

## 📝 Licencia

Este material educativo está disponible bajo licencia [GNU General Public License v3.0 (GPL-3.0)](../LICENSE).

---

## 🎯 Próximos Pasos

Una vez completado el Módulo 2, estarás listo para:

- **Módulo 3:** Mecánica Molecular y Campos de Fuerza
- **Módulo 4:** Dinámica Molecular
- **Módulo 5:** Mecánica Cuántica Computacional

---

<div align="center">

📚 **[← Módulo 1: Fundamentos](../modulo_01_fundamentos/)** | **[Inicio del Curso →](../README.md)**

**Universidad de Caldas - Departamento de Química**  
*Química Computacional 173G7G*

</div>
