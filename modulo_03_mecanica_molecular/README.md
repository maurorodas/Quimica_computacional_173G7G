# ⚛️ Módulo 3: Mecánica Molecular y Campos de Fuerza

<div align="center">

**Universidad de Caldas - Departamento de Química**  
*Introducción a la Química Computacional (173G7G)*  
**Profesor:** José Mauricio Rodas Rodríguez

---

</div>

## 📋 Descripción del Módulo

Este módulo te introduce al mundo de la mecánica molecular, una de las herramientas fundamentales en la química computacional. Aprenderás los fundamentos teóricos de los campos de fuerza, cómo se modelan las interacciones moleculares usando mecánica clásica, y cómo realizar optimizaciones de geometría y análisis conformacional. Dominarás el uso de software especializado para realizar cálculos de mecánica molecular en una amplia variedad de sistemas químicos.

## 🎯 Objetivos de Aprendizaje

Al completar este módulo, serás capaz de:

- ✅ Comprender los fundamentos teóricos de la mecánica molecular
- ✅ Conocer los principales campos de fuerza y sus aplicaciones
- ✅ Realizar optimizaciones de geometría molecular
- ✅ Analizar superficies de energía potencial
- ✅ Realizar análisis conformacional sistemático
- ✅ Calcular propiedades termodinámicas básicas
- ✅ Usar software de mecánica molecular (OpenBabel, RDKit, Avogadro)
- ✅ Validar y evaluar resultados de cálculos MM

## 📚 Contenido del Módulo

### Actividades

| # | Actividad | Descripción | Duración |
|---|-----------|-------------|----------|
| **3.1** | [Fundamentos de Mecánica Molecular](01_fundamentos_mecanica_molecular.ipynb) | Teoría, ecuaciones, aproximaciones y limitaciones | 2-3 horas |
| **3.2** | Campos de Fuerza | MM2, MM3, MMFF, UFF, GAFF - Características y aplicaciones | 3-4 horas |
| **3.3** | Optimización de Geometrías | Métodos de minimización, criterios de convergencia | 3-4 horas |
| **3.4** | Superficies de Energía Potencial | PES, puntos estacionarios, caminos de reacción | 3-4 horas |
| **3.5** | Análisis Conformacional | Búsqueda sistemática, métodos estocásticos | 3-4 horas |
| **3.6** | Cálculos de Propiedades | Energías, momentos dipolares, frecuencias | 2-3 horas |
| **3.7** | Software Especializado | OpenBabel, RDKit, Avogadro, PyMOL | 2-3 horas |
| **3.8** | Validación de Resultados | Comparación con datos experimentales y QM | 2-3 horas |

**Duración total estimada:** 20-28 horas

## 🚀 Cómo Usar Este Módulo

### Requisitos Previos

- ✅ **Módulo 1 completado** - Fundamentos computacionales
- ✅ **Módulo 2 completado** - Representación molecular
- ✅ Python 3.8+ instalado
- ✅ Jupyter Notebook o Google Colab
- ✅ Conocimientos de química física (enlace químico, termodinámica)

### Orden Recomendado

Las actividades están diseñadas para seguirse **secuencialmente**:

```
3.1 → 3.2 → 3.3 → 3.4 → 3.5 → 3.6 → 3.7 → 3.8
```

### Instalación de Dependencias

Para trabajar localmente, instala las bibliotecas necesarias:

```bash
# Opción 1: Conda (Recomendado)
conda create -n modulo3_mm python=3.11
conda activate modulo3_mm
conda install -c conda-forge rdkit openbabel py3dmol
pip install ase pyscf scipy matplotlib numpy pandas

# Opción 2: pip
pip install rdkit-pypi openbabel-wheel py3dmol ase pyscf scipy matplotlib numpy pandas
# Nota: RDKit y OpenBabel funcionan mejor con conda
```

## 📊 Estructura de las Actividades

Cada actividad incluye:

1. **Introducción Teórica** - Fundamentos y ecuaciones relevantes
2. **Conceptos Clave** - Explicación detallada con visualizaciones
3. **Ejemplos Prácticos** - Implementación con código ejecutable
4. **Casos de Estudio** - Aplicaciones a sistemas químicos reales
5. **Ejercicios Progresivos** - Básico → Intermedio → Avanzado
6. **Recursos Adicionales** - Referencias y material complementario

## 🛠️ Herramientas que Aprenderás

### Bibliotecas Python

- **RDKit** - Minimización con campos de fuerza
  - Implementación de MMFF94, UFF
  - Optimización de geometrías
  - Generación de conformaciones
  - Cálculo de energías
  
- **OpenBabel** - Conversión y optimización molecular
  - Soporte para múltiples campos de fuerza
  - Generación de coordenadas 3D
  - Cálculo de propiedades
  - Asignación de tipos de átomo
  
- **ASE** (Atomic Simulation Environment)
  - Interfaz unificada para cálculos
  - Optimización de geometrías
  - Análisis de modos normales
  - Visualización de trayectorias
  
- **PySCF** - Cálculos de química cuántica para comparación
  - Validación de resultados MM
  - Generación de datos de referencia

### Software Externo

- **Avogadro** - Construcción y visualización molecular
  - Editor molecular gráfico
  - Optimización interactiva
  - Análisis de propiedades
  
- **PyMOL** - Visualización avanzada
  - Análisis estructural
  - Generación de imágenes de calidad
  
- **VMD** - Visualización y análisis
  - Análisis de trayectorias
  - Cálculo de descriptores estructurales

## 🎓 Aplicaciones en Química

### Química Orgánica
- Predicción de conformaciones de menor energía
- Análisis de isómeros conformacionales
- Diseño de catalizadores organometálicos

### Química Farmacéutica
- Optimización de geometrías de fármacos
- Análisis de flexibilidad molecular
- Cribado virtual de bibliotecas

### Química Supramolecular
- Ensamblajes moleculares
- Complejos huésped-hospedador
- Estructuras de coordinación

### Ciencia de Materiales
- Polímeros y macromoléculas
- Cristales moleculares
- Interfases y superficies

## 💡 Consejos para el Éxito

1. **Comprende las Limitaciones** - MM no describe ruptura/formación de enlaces
2. **Valida tus Resultados** - Compara con datos experimentales o QM
3. **Elige el Campo Apropiado** - No todos los campos funcionan igual para todos los sistemas
4. **Visualiza las Estructuras** - Siempre revisa visualmente las geometrías optimizadas
5. **Analiza la Convergencia** - Verifica que las optimizaciones converjan apropiadamente
6. **Documenta Parámetros** - Registra qué campo de fuerza y opciones usaste

## 📖 Recursos Complementarios

### Documentación Oficial
- [RDKit Force Fields](https://www.rdkit.org/docs/RDKit_Book.html#force-fields)
- [OpenBabel Force Fields](https://openbabel.org/docs/dev/Forcefields/Overview.html)
- [ASE Documentation](https://wiki.fysik.dtu.dk/ase/)
- [Avogadro Manual](https://avogadro.cc/docs/)

### Tutoriales Especializados
- [Molecular Mechanics Tutorial](https://www.ch.ic.ac.uk/vchemlib/course/mm_workshop/)
- [Force Field Parameters Guide](https://ambermd.org/tutorials/)
- [Conformational Analysis Methods](https://www.sciencedirect.com/topics/chemistry/conformational-analysis)

### Libros de Referencia
- *Molecular Modeling: Principles and Applications* - Andrew R. Leach
- *Computational Chemistry: Introduction to the Theory and Applications* - Errol G. Lewars
- *Molecular Mechanics* - Ulrich Burkert, Norman L. Allinger
- *Force Fields for Protein Simulations* - A. D. MacKerell Jr.

### Artículos Clásicos
- Allinger, N. L. (1977). *J. Am. Chem. Soc.* - Campo de fuerza MM2
- Halgren, T. A. (1996). *J. Comput. Chem.* - Campo de fuerza MMFF94
- Rappé, A. K. et al. (1992). *J. Am. Chem. Soc.* - Universal Force Field (UFF)

## 🆘 Soporte y Ayuda

### Problemas Técnicos
- Revisa la sección de **Troubleshooting** en cada actividad
- Consulta los **Issues** en el repositorio de GitHub
- Contacta al profesor: mauricio.rodas@ucaldas.edu.co

### Errores Comunes

#### Optimización no converge
**Solución:** 
- Verifica la geometría inicial
- Reduce el tamaño de paso
- Usa un algoritmo diferente (Steepest Descent → Conjugate Gradient)

#### Energías muy altas o negativas inusuales
**Solución:**
- Revisa colisiones atómicas en la estructura inicial
- Verifica la asignación correcta de tipos de átomo
- Comprueba que el campo de fuerza sea apropiado

#### Conformaciones irreales
**Solución:**
- Aumenta el número de optimizaciones
- Usa restricciones en grados de libertad relevantes
- Valida con cálculos de mayor nivel

## 🔬 Proyecto del Módulo

Al finalizar este módulo, completarás un proyecto integrador:

**"Análisis Conformacional y Energético de un Sistema Molecular"**

Incluirá:
- Construcción de la estructura molecular
- Selección y justificación del campo de fuerza
- Optimización de geometría
- Búsqueda conformacional sistemática
- Análisis de la superficie de energía potencial
- Cálculo de propiedades moleculares
- Comparación con datos experimentales o teóricos
- Visualización de resultados

## ⚠️ Consideraciones Importantes

### Cuándo Usar Mecánica Molecular
- ✅ Sistemas grandes (>100 átomos)
- ✅ Análisis conformacional extensivo
- ✅ Cribado rápido de estructuras
- ✅ Dinámica molecular preliminar

### Cuándo NO Usar Mecánica Molecular
- ❌ Reacciones químicas
- ❌ Estados de transición
- ❌ Propiedades electrónicas
- ❌ Sistemas con enlaces múltiples cambiantes
- ❌ Iones metálicos en entornos no parametrizados

## 🔄 Actualizaciones

Este módulo se actualiza periódicamente. Última actualización: **Enero 2026**

## 📝 Licencia

Este material educativo está disponible bajo licencia [GNU General Public License v3.0 (GPL-3.0)](../LICENSE).

---

## 🎯 Próximos Pasos

Una vez completado el Módulo 3, estarás listo para:

- **Módulo 4:** Dinámica Molecular
- **Módulo 5:** Mecánica Cuántica Computacional
- **Módulo 6:** Métodos Semiempíricos
- **Módulo 7:** Métodos Ab Initio y DFT

---

<div align="center">

📚 **[← Módulo 2: Representación Molecular](../modulo_02_representacion_molecular/)** | **[Inicio del Curso →](../README.md)**

**Universidad de Caldas - Departamento de Química**  
*Química Computacional 173G7G*

</div>
