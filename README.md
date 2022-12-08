# ia-manual
Manual de prácticas para inteligencia artificial

Para compilar se require clonar a un lado el paquete:
https://github.com/computacion-ciencias/Estilos

Utilizar el comando ```pdflatex``` con la bandera ```--shell-escape```.  Completo es:
```
pdflatex --shell-escape Laboratorio_IA.tex
```

Si se utiliza Kile, configurar ```Preferencias -> Configurar Kile... -> Tools -> Build -> PDFLaTeX -> General -> Options:```
Debe quedar:
```
-interaction=nonstopmode --shell-escape %source
```

