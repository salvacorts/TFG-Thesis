# Trabajo de Fin de Grado: *Metaheurísticas distribuidas usando infraestructura efímera*

### Autor(a): Salvador Corts Sánchez
### Tutor(a)(es): Juan Julián Merelo Guervós
___

## Requirements

- TeXLive: `sudo apt install texlive texlive-fonts-extra`
- [listings-golang](https://github.com/julienc91/listings-golang)

## Compile
La documentación de este proyecto está realizada con `LaTeX`, por lo
tanto para generar el archivo PDF necesitaremos instalar `TeXLive` en
nuestra distribución.

Una vez instalada, tan solo deberemos situarnos en el directorio `doc` y ejecutar:

`
$ pdflatex proyecto.tex
`

Seguido por

    bibtex proyecto
    
y de nuevo

    pdflatex proyecto.tex
