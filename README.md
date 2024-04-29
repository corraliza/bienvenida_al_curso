# IV Curso de Bioinformática (CIBEREHD)

Este es el repositorio para el IV Curso de Bioinformática del CIBEREHD, impartido por Marta Coronado y Ana Maria Corraliza.

## Descripción del Curso

En este curso, presentaremos *R* y *RStudio* como herramientas para el análisis de datos. R es un lenguaje de programación especialmente diseñado para el análisis estadístico de datos y la creación de gráficos. RStudio es un entorno de desarrollo integrado (IDE) para R, que permite utilizarlo de una manera más cómoda y eficaz.

## Preparación

Antes de comenzar el curso, se recomienda instalar R y RStudio en tu ordenador. Hazlo con tiempo, y si tienes problemas al hacerlo, ponte en contacto con nosotras con antelación.

### Instalación de R y RStudio

- R se puede descargar desde [CRAN](https://cran.rediris.es). Debes elegir la versión adecuada para tu sistema operativo.
- RStudio está disponible de forma gratuita en [RStudio Desktop](https://posit.co/download/rstudio-desktop/). La página detectará automáticamente tu sistema operativo y te ofrecerá el instalador correspondiente.

Consulta los siguientes tutoriales para obtener ayuda específica según tu sistema operativo:
- Windows: [Instalación de R y RStudio en Windows](https://datacritica.org/2021/03/18/instalacion-de-r-y-rstudio-en-windows)
- Linux: [Cómo instalar R en Ubuntu 20.04](https://linuxize.com/post/how-to-install-r-on-ubuntu-20-04)
- MacOS: [Instalación de R y RStudio en MacOS](https://datacritica.org/2021/03/19/instalacion-de-r-y-rstudio-en-macos)

## Organización del Curso

El curso constará de tres sesiones teórico-prácticas online (6 horas) y una sesión totalmente práctica en formato asincrónico. En las sesiones online utilizaremos la herramienta RStudio en la nube, *Posit Cloud*, para realizar demostraciones y proporcionar materiales.

### Inscripción en Posit Cloud

Para utilizar Posit Cloud, ve a la web [posit.cloud](https://posit.cloud/) y regístrate en la opción *Cloud Free*. Una vez registrado, podrás acceder a RStudio. Pronto te proporcionaremos un enlace con el material del curso, para que puedas acceder a los materiales y ejecutar los códigos en la misma plataforma.

## Paquetes de R

Durante el curso utilizaremos diferentes paquetes de R. Estos paquetes contienen funciones que nos permiten realizar tareas específicas. A continuación se detallan los paquetes que se utilizarán:

- BiocManager
- utils
- readr
- learnr
- readxl
- ggplot2
- ggpubr
- car
- limma
- DESeq2
- clusterProfiler

Se recomienda instalar estos paquetes antes de comenzar el curso. Para hacerlo, abre RStudio una vez instalados R y RStudio, y ejecuta las siguientes líneas en la consola:

```R
install.packages(c("BiocManager", "utils", "readr", "learnr", 
                   "readxl", "ggplot2", "ggpubr", "car"))

BiocManager::install(c("limma","DESeq2", "clusterProfiler"))
```
