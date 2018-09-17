## el link es de markdown
https://guides.github.com/features/mastering-markdown/ 

## instalar scss preprocesador css

```
npm install -g sass
```
## o
```
npm install -g node-sass
```
## compilar automaticamente scss a css
```
sass --watch estilos.scss estilos.css
```
## importar otros archivos.scss a un archivo scss y solo compilar el ultimo archico
```
sass -w carpeta_scss -o carpeta_css
```

## instalar style/stylus preprocesador css
```
npm -g install stylus
```
## compilar automaticamente a archivo
```
stylus estilos.styl -c -w
```
## compilar automaticamente a carpeta 
```
stylus estilos.styl -c -w --out carpeta
```
