# Proyecto de Estadística y Econometría en LaTeX

Este repositorio contiene el código fuente y la estructura modular del documento académico. El proyecto está diseñado con una arquitectura de directorios encapsulada por capítulos, separando los recursos gráficos temáticamente en Estadística y Econometría.

## Arquitectura del Proyecto

```text
Proyecto_Estadistica_Econometria/
│
├── main.tex                            # Archivo maestro (configuración y llamado de módulos)
│
├── Figuras_Estadistica/                # Carpeta central para todas las gráficas de estadística
│
├── Figuras_Econometria/                # Carpeta central para todas las gráficas de econometría
│
├── 1_Preliminares/                     # Secciones iniciales
│   └── Prologo.tex
│
├── 2_Estadistica_para_legos/           # Primera parte del documento
│   ├── Cap0a_buffonDG.tex
│   ├── Cap0b_probaDG.tex
│   ├── Cap0c_LGNyTLC.tex               
│   ├── Cap0d_EstimPuntDG.tex
│   └── Cap0e_PruHipotDG.tex
│
├── 3_Econometria_para_primiparos/      # Núcleo del trabajo analítico
│   ├── Introduccion.tex
│   ├── Cap1_MCO.tex
│   ├── Cap2_propiedades.tex
│   ├── Cap2BIS_MiscelMCO.tex
│   ├── Cap3_inferenciaMCO.tex
│   ├── Cap4_autoco_heterosc.tex        
│   ├── capitulo4.tex                   
│   ├── Cap5_MCOnonormal.tex
│   ├── capitulo6.tex
│   └── Pendientes.tex
│
└── 4_Apendices/                        # Complementos y código matemático adicional
    ├── ApendiceRegresionLinealSimple.tex
    ├── ApendiceMatrices.tex
    ├── ApendiceConvergencia.tex
    ├── ApendiceBorelCantelli.tex
    ├── ApendiceLGNseriesdeTiempo.tex
    ├── AppMaxVeroRegLineal.tex
    ├── AppEcuacionesEnDif.tex          
    ├── AppLGNniid.tex
    ├── ApendiceProbabilidad.tex        
    └── Cuadros_Distribuciones.tex
