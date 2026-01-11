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

### Módulo 1: Introducción a la Química Computacional
1. Uso de consolas
2. Herramientas básicas para la edición de texto plano
3. Scripting básico
4. Uso de programas de manipulación y graficado de datos
5. Superficies de energía potencial
6. Estructuras
7. Mecánica estadística y teoría del estado de transición

### Módulo 2: Mecánica Molecular
1. Campos de fuerza
2. Energía y termodinámica
3. Optimización de geometrías
4. Frecuencias

### Módulo 3: Introducción a la Mecánica Cuántica
1. Función de onda
2. Operador hamiltoniano
3. Aproximación de Born-Oppenheimer
4. Teoría de Hückel
5. Método de Hartree-Fock

### Módulo 4: Métodos Semiempíricos
1. NDDO
2. INDO
3. CNDO
4. AM1
5. PM3, PM5
6. Teoría de Hückel extendida

### Módulo 5: Métodos Ab-initio
1. Filosofía Ab-initio
2. Set de bases
3. Convergencia SCF
4. Simetría
5. Sistemas de capa abierta


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
Introduccion_Computacional/
├── README.md
├── requirements.txt
├── modulo_01_introduccion/
│   ├── README.md
│   ├── 01_uso_consolas.ipynb
│   ├── 02_edicion_texto.ipynb
│   ├── 03_scripting_basico.ipynb
│   ├── 04_manipulacion_datos.ipynb
│   ├── 05_superficies_energia.ipynb
│   ├── 06_estructuras.ipynb
│   └── 07_mecanica_estadistica.ipynb
├── modulo_02_mecanica_molecular/
│   ├── README.md
│   ├── 01_campos_fuerza.ipynb
│   ├── 02_energia_termodinamica.ipynb
│   ├── 03_optimizacion_geometrias.ipynb
│   └── 04_frecuencias.ipynb
├── modulo_03_mecanica_cuantica/
│   ├── README.md
│   ├── 01_funcion_onda.ipynb
│   ├── 02_hamiltoniano.ipynb
│   ├── 03_born_oppenheimer.ipynb
│   ├── 04_teoria_huckel.ipynb
│   └── 05_hartree_fock.ipynb
├── modulo_04_metodos_semiempiricos/
│   ├── README.md
│   ├── 01_nddo.ipynb
│   ├── 02_indo.ipynb
│   ├── 03_cndo.ipynb
│   ├── 04_am1.ipynb
│   ├── 05_pm3_pm5.ipynb
│   └── 06_huckel_extendida.ipynb
├── modulo_05_metodos_ab_initio/
│   ├── README.md
│   ├── 01_filosofia_ab_initio.ipynb
│   ├── 02_set_bases.ipynb
│   ├── 03_convergencia_scf.ipynb
│   ├── 04_simetria.ipynb
│   └── 05_sistemas_capa_abierta.ipynb
└── recursos/
    ├── datos/
    └── imagenes/
```


## 🛠️ Software y Herramientas

Este curso utiliza exclusivamente **software libre y de código abierto**:

### Lenguajes de Programación
- ![Python](https://img.shields.io/badge/Python-3.8+-3776AB?logo=python&logoColor=white) - Lenguaje principal
- ![Bash](https://img.shields.io/badge/Bash-4EAA25?logo=gnu-bash&logoColor=white) - Scripts de automatización

### Librerías Científicas Python
| Librería | Propósito | Instalación |
|----------|-----------|-------------|
| **NumPy** | Cálculos numéricos | `pip install numpy` |
| **Matplotlib** | Visualización de datos | `pip install matplotlib` |
| **SciPy** | Algoritmos científicos | `pip install scipy` |
| **Pandas** | Manipulación de datos | `pip install pandas` |
| **RDKit** | Química computacional | `pip install rdkit` |
| **ASE** | Simulación atómica | `pip install ase` |
| **Psi4** | Cálculos cuánticos | `conda install psi4` |
| **OpenBabel** | Conversión de formatos | `pip install openbabel` |

### Software de Simulación
- **ORCA** - Cálculos de química cuántica (gratuito para académicos)
- **GAMESS** - Cálculos ab-initio (código abierto)
- **NWChem** - Química computacional escalable (open source)

### Herramientas de Visualización
- **PyMOL** - Visualización molecular (versión open-source)
- **VMD** - Visual Molecular Dynamics (gratuito)
- **Avogadro** - Editor y visualizador molecular (open source)


## 📝 Contribuciones y Retroalimentación

¿Encontraste un error o tienes una sugerencia para mejorar el material? 

- 📧 Abre un **Issue** en GitHub
- 🔧 Envía un **Pull Request** con tus mejoras
- 💬 Comparte tu experiencia y sugerencias

Todas las contribuciones son bienvenidas y ayudan a mejorar este curso para futuros estudiantes.

---

## 📄 Licencia

<div align="center">

**Material Educativo - Universidad de Caldas**

Este material está diseñado con fines educativos y de investigación.  
Se permite su uso, modificación y distribución con propósitos académicos,  
siempre que se cite apropiadamente la fuente.

📚 **Curso:** Introducción a la Química Computacional (173G7G)  
🏛️ **Institución:** Universidad de Caldas  
📅 **Año:** 2026

</div>

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

**[📖 Comenzar con el Módulo 1](modulo_01_introduccion/)**

---

*Desarrollado con ❤️ para estudiantes de Química Computacional*  
*Universidad de Caldas - 2026*

</div>
