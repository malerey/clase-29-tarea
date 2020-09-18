# clase 29 - Ejercitación

En tu HTML, copia y pega el siguiente código:

```html
<div class="container">
  
  <div class="card">
    <img src="http://www.placekitten.com/200">
    <div class="title">
      <h4>Artilugia</h4>
    </div>
  </div>
  
    <div class="card">
    <img src="http://www.placekitten.com/300">
    <div class="title">
      <h4>Boris</h4>
    </div>
  </div>
  
    <div class="card">
    <img src="http://www.placekitten.com/400">
    <div class="title">
      <h4>Pippin</h4>
    </div>
  </div>
  
</div>
```

En tu CSS, copia y pega el siguiente codigo:

```css 
.container {
  display: flex;
}

.card {
  font-family: Verdana;
  width: 200px;
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
  margin: 20px;
}

.card > img {
  width: 100%;
}

.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}

.title {
  padding: 2px 16px;
}
```

### 1. 

Agregale a cada tarjeta la siguiente `data` (inventada)
- nombre
- sexo
- color

### 2. 

Agrega un <form> a tu web con:
- Un input type="text" con el label "Nombre"
- Un <select> con el label "Colores" y como opciones, colores habituales de gatos. 
- Tres input type="radio" con el label "Sexo" y como opciones "hembra", "macho" e "indistinto". 
  
### 3. 

Hacé cada uno de estos ejercicios en orden. No avances al siguiente hasta que el primero este funcionando. 
Usa `console.log` a cada momento para revisar que hayas seleccionado los elementos correctos, y que la data que estes usando sea la correcta. 

Al escribir en el input, deben aparecer solo las tarjetas en donde el nombre del gato coincida con lo escrito. 

Al seleccionar un color, deben aparecer solo los gatos del color seleccionado. 

Al seleccionar un sexo, deben aparecer solo los gatos del sexo seleccionado. 
