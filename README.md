Proyecto_Estadistica_Econometria/
│
├── main.tex                            # Archivo maestro (configuración y llamado de módulos)
│
├── Figuras_Estadistica/                # Carpeta central para todas las gráficas de estadística
│   ├── Cap0a_buffonDG/
│   ├── Cap0b_probaDG/
│   ├── Cap0c_LGNyTLC/
│   ├── Cap0d_EstimPuntDG/
│   └── Cap0e_PruHipotDG/
│
├── Figuras_Econometria/                # Carpeta central para todas las gráficas de econometría
│   ├── Introduccion/
│   ├── Cap1_MCO/
│   ├── Cap2_propiedades/
│   ├── Cap2BIS_MiscelMCO/
│   ├── Cap3_inferenciaMCO/
│   ├── Cap4_autoco_heterosc/
│   ├── capitulo4/
│   ├── Cap5_MCOnonormal/
│   ├── capitulo6/
│   └── Pendientes/
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

## Nomenclatura de Imágenes

Todos los archivos de figura siguen el estándar: `[ID]_[desc]_[tip].eps`

### Estructura del Nombre
- **[ID]** - Módulo + Capítulo (3 caracteres máx)
  - `S` = Estadística, `E` = Econometría, `A` = Apéndices
  - Ejemplo: `S0a`, `E1`, `A2B`
  
- **[desc]** - Descriptor corto (3-5 caracteres, minúsculas, sin acentos)
  - Ejemplo: `plano`, `densx`, `error`, `resid`
  
- **[tip]** - Tipo de gráfico
  - `plt` = Plot (funciones, distribuciones)
  - `dgm` = Diagrama (esquemas conceptuales)
  - `sct` = Scatter (dispersión de datos)

### Ejemplo de Ruta y Nombre
- `Figuras_Estadistica/Cap0a_buffonDG/S0a_aguja_dgm.eps`
- `Figuras_Econometria/Cap1_MCO/E1_resid_sct.eps`
