# markDown_guia
<!-- Con Ctrl + Shift + P  buscamos el previsualizador de MarkDown open preview -->

<!-- Cabeceras -->
# Tipos de títulos
# Título H1
## Título H2
### Título H3
#### Título H4
##### Título H5
###### Título H6
___

# Tipos de letras
<!-- italic-->
Texto en *italic*

<!-- negrita -->
Texto en **negrita**

<!-- tachado -->
Texto ~~tachado~~

# Listas
<!-- Listas desordenadas -->
## Lista desordenada
* manzana
    * golden
    * roja
* naranja
* pera

<!-- Listas ordenada -->
## Lista ordenada
1. manazana
    1. golden
    2. roja
2. naranja
3. pera

<!-- Enlaces url -->
# Enlaces URL
[google.com](http://www.google.com "custom title")

<!-- Citas -->
# Citas
> Esto es una cita

<!-- Lineas de separación -->
# Lineas de separación
---
___

<!-- Lineas de código -->
# Lineas de código
`console.log('Prueba')`

<!-- Bloques de código -->
# Bloques de código
## Código javascript
```javascript 
  scrollFrom() {
    let scrollBodyTable = document.getElementById('bodyTable');
    if (this._utils.isExplorer()) {
      scrollBodyTable.scrollTop = 3500;
    } else {
      scrollBodyTable.scrollTo(0, 500);
    }
  }
```
## Código java
```java
	private void altaRegistroSGP(String idFichero, String resultOper, String tipoReg, String nomTabla, String indSol,DatosUsuario datosUsuario) {
		String descrip = idFichero + "," + tipoReg + "," + datosUsuario.getUsuLogin() + "," + indSol;
		RegistroSGP registroSGP = commonHelperService.crearRegistroSGP(datosUsuario.getUid(),   tipoReg, nomTabla, idFichero, datosUsuario.getClieNom(), descrip, "ARC");
		registroSGP.setResulOpe(resultOper);
		commonHelperService.altaRegistroSGP(registroSGP);
	}
```
<!-- Tablas -->
# Tablas
| Tables    | Are           | Cool  |
|-----------|:--------------|:------|
| col 3 is  | right-aligned | $1600 |
| col 2 is  | centered      |   $12 |
| zebra     | are neat      |    $1 |

<!-- Imagnes -->
# Imagenes
![visual studio code logo](visual-studio-code7642.jpg "vsCode tootip")

<!-- Codigo que se visualiza solo en gitHub -->
# Código para gitHub
## Checkbox
* [x] Tarea 1
* [ ] Tarea 2
* [ ] Tarea 3
* [x] Tarea 4

## Emojis
@david :smiley: :+1:
