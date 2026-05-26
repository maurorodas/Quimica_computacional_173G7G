# 📊 Presentación: Dinámica Molecular

<div align="center">

**Universidad de Caldas - Departamento de Química**  
*Introducción a la Química Computacional (173G7G)*  
**Profesor:** José Mauricio Rodas Rodríguez

</div>

---

## Descripción

Presentación en LaTeX/Beamer sobre **Dinámica Molecular**: principios teóricos, métodos computacionales y aplicaciones en química computacional. Diseño moderno con colores pastel, nivel universitario.

## Contenido

| Sección | Descripción |
|---------|-------------|
| 1. Fundamentos | Ecuaciones de Newton, campo de fuerzas, potencial LJ, Maxwell-Boltzmann |
| 2. Algoritmos de integración | Verlet, Velocity-Verlet, Leap-Frog — matemática y comparación |
| 3. Condiciones de contorno | PBC, convención de imagen mínima, tipos de caja |
| 4. Ensambles estadísticos | NVE, NVT, NPT — fundamentos termodinámicos |
| 5. Termostatos y barostatos | Berendsen, v-rescale, Nosé-Hoover, Parrinello-Rahman |
| 6. Preparación de sistemas | Protocolo completo: PDB → solvatar → iones → minimizar → equilibrar |
| 7. Modelos de agua | SPC/E, TIP3P, TIP4P/2005, OPC — comparación |
| 8. Campos de fuerzas | AMBER, CHARMM, OPLS, GROMOS, OpenFF |
| 9. Análisis de trayectorias | RMSD, RMSF, Rg, RDF, puentes de H, coeficiente de difusión |
| 10. Comparación de programas | GROMACS vs OpenMM vs NAMD vs AMBER |
| 11. Ecosistema de herramientas | Preparación → Simulación → Análisis → Visualización |
| 12. Protocolo proteínas | Ejemplo completo con parámetros GROMACS |
| 13. Técnicas avanzadas | FEP, metadinámica, umbrella sampling, REMD, ML-MD |
| 14. Ejercicios | 5 ejercicios: teórico, computacional y avanzado |
| 15. Resumen y perspectivas | Tendencias 2024–2025 y recursos recomendados |

## Compilación

### Requisitos
- LaTeX con distribución **TeX Live** o **MiKTeX**
- Paquetes: `beamer`, `tikz`, `pgfplots`, `tcolorbox`, `fontawesome5`, `chemformula`, `physics`

### Compilar (Linux/Mac)
```bash
cd presentacion_MD
pdflatex presentacion_DM.tex
pdflatex presentacion_DM.tex   # Segunda pasada para referencias
```

### Compilar (Windows)
```powershell
cd presentacion_MD
pdflatex presentacion_DM.tex
pdflatex presentacion_DM.tex
```

### Con latexmk (recomendado)
```bash
latexmk -pdf presentacion_DM.tex
```

## Características del diseño

- **Tema base**: Beamer Madrid con paleta personalizada
- **Paleta pastel**: azul, verde, lila, naranja, teal, rojo-rosa, amarillo
- **Diagramas**: TikZ inline (flujo de trabajo MD, ecosistema herramientas, partículas)
- **Gráficas**: pgfplots (potencial LJ, distribución Maxwell-Boltzmann)
- **Cajas**: tcolorbox con estilos temáticos (fórmula, definición, advertencia, ejercicio)
- **Tipografía**: LM Roman con microtype

## Archivos

```
presentacion_MD/
├── presentacion_DM.tex    # Archivo principal LaTeX/Beamer
└── README.md              # Este archivo
```

---

📚 **[Volver al Módulo 5](../modulo_05_dinamica_molecular/README.md)** | 🏠 **[Inicio del Curso](../README.md)**

---

**Universidad de Caldas - Departamento de Química**  
*Química Computacional 173G7G*
