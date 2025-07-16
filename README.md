# DECBioInfer

Repositorio del tutoriales interactivos en learnr de inferencia estadística del curso Introdución a la Bioestadística, Maestría en Epidemiología Clínica.
Departamento de Epidemiología Clínica y Bioestadística, Facultad de Medicina, Pontifica Universidad Javeriana.

## Instalación

Para instalar este paquete se debe tener instalado el paquete `remotes`, si no lo tiene, instálelo con:

  
```r
install.packages("remotes")
```

y luego usar el siguiente código para instalar el tutorial:

```r
remotes::install_github("DepEpiClinBios/DECBioInfer")
```

## Uso

Si no dispone de la versión de Rstudio 1.4 o superior, debe instalar el paquete `learnr` con:

```r
install.packages("learnr")
```

Luego, para iniciar el tutorial, use el siguiente código:

```r
learnr::run_tutorial("AnalisisVarianza", package = "DECBioInfer")
```

## Contribuciones

Si desea contribuir al desarrollo de este paquete, por favor lea las [contribuciones](CONTRIBUTING.md) y el [código de conducta](CODE_OF_CONDUCT.md).

## Licencia
Este paquete está licenciado bajo la Licencia Pública General de GNU v3.0. Consulte el archivo [LICENSE](LICENSE) para obtener más detalles.

## Contacto
Para cualquier duda o sugerencia, por favor contacte a los autores del paquete:

- fgil@javeriana.edu.co

- martin.rondon@javeriana.edu.co

- erika.cantor@javeriana.edu.co


