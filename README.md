js-Snow  // Script que simula la caida de nieve.

Version principal creada por Ivan Lazarevic (http://workshop.rs) el año 2012.

Modificaciones hechas:
  - Se aplico css para cambiar de color el copo de nieve. 
  - Sus valores se pueden modificar de forma mas sencilla (minSize, maxSize, newOn). 
  - Funcionando con las ultimas versiones de jQuery (2.1.1 y 1.11.1). 

======= Significado de sus variables

- minSize = Tamaño minimo del copo.
- maxSize = Tamaño maximo del copo.
- newOn = Frecuencia con la que aparece cada copo en milisegundos.

======= Aplicacion del script

1. Se recomienda usar la ultima version de jQuery, aunque si tiene algun tipo de conflicto por otro script 
no deberia haber problema en utilizar una version inferior. 
2. Agregar el archivo jquery.snow.min.1.0.js a la pagina donde se utilizara. 
3. Aplicar el estilo entre las etiquetas <head></head>.  
	`<style type="text/css">`  
		`#flake {`  
		`color: #FFFFFF;` 
		`}`  
	`</style>`  
4. Codigo para inicializar el script.  
`<script>`  
			`$(document).ready( function(){`  
	       `$.fn.snow({`  
		        	`minSize: 10,`  
		        	`maxSize: 20, `  
		        	`newOn: 200});`  
		`});`  
`</script>`  



