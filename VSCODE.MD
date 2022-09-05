# CURSO DE VISUAL ESTUDIO CODE
- [CURSO DE VISUAL ESTUDIO CODE](#curso-de-visual-estudio-code)
  - [Movimintos de lineas](#movimintos-de-lineas)
  - [Movimintos de 2 o mas lineas](#movimintos-de-2-o-mas-lineas)
  - [Comentarios](#comentarios)
  - [Nuevo archivo](#nuevo-archivo)
  - [Ir a la definicion](#ir-a-la-definicion)
  - [Borrar lineas](#borrar-lineas)
  - [Deshacer - Rehacer](#deshacer---rehacer)
  - [Modo zen](#modo-zen)
  - [Terminal](#terminal)
  - [Crear Shortcuts](#crear-shortcuts)
  - [Emment-wrap](#emment-wrap)
  - [Ventanas cerrar abrir](#ventanas-cerrar-abrir)
  - [**Multi cursor**](#multi-cursor)
  - [Clonar lineas](#clonar-lineas)
  - [Crear cursores arriba y abajo](#crear-cursores-arriba-y-abajo)
  - [Multi cursor **Copy**](#multi-cursor-copy)
## Movimintos de lineas

Atajo:
        ⌥ ↓ / ⌥ ↑
        Alt + ↑ / ↓

``` html
<ul>
  <li>Línea 1</li>
  <li>Línea 2</li>
  <li>Línea 3</li>
  <li>Línea 4</li>
  <li>Línea 5</li>
  <li>Línea 6</li>
  <li>Línea 7</li>
</ul>
```

## Movimintos de 2 o mas lineas 

    Tips:
   1. Selccionamos las lineas que queremos mover.
        ⌥ ↓ / ⌥ ↑
        Alt + ↑ / ↓


``` html
<ul>
  <li>
      <span>línea 1</span>
      <span>Nada importante 1</span>
  </li>
    <li>
      <span>línea 4</span>
        <span>Nada importante 4</span>
    </li>
    <li>
      <span>línea 3</span>
        <span>Nada - [CURSO DE VISUAL ESTUDIO CODE](#curso-de-visual-estudio-code)
  - [Movimintos de lineas](#movimintos-de-lineas)
  - [Movimintos de 2 o mas lineas](#movimintos-de-2-o-mas-lineas)importante 3</span>
    </li>
    <li>
      <span>línea 2</span>
        <span>Nada importante 2</span>
    </li>
</ul>
```
## Comentarios

Colocar el cursor en la linea a comentar


``` js
    Tips:
        ⌘ /
        Ctrl + /
*/

const a = 10;
const b = 20;
const c = { a, b };


const a = 30;
const b = 40;
const c = { a, b };


console.log( a, b, c );

// Resultado final
// Sólo dejar un bloque comentado
```

    Tips:
        ⌘ /
        ⇧ ⌥ A
        Ctrl + /
        Shift + Alt + A
-->

<div>
    <span>Hola</span>
    <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
        Eum maiores nostrum cum quasi totam.
    </p>
</div>

<h1>Objetivo final</h1>

<div>
    <span>Hola</span>
    <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
        Eum maiores nostrum cum quasi totam.
    </p>
</div>

## Nuevo archivo

    Tips:
        ⌥ click derecho
        Ctrl + click derecho
-->

<script src="assets/js/app.js"></script>


## Ir a la definicion

    Tips:
        Ojear definición   ⌥ F12
        Ir a la definición F12

        Ojear definición   Alt + F12
        Ir a la definición F12
*/

``` js
import { saludar } from './extra/funciones';

const saludo = saludar( 'Thanos' );

console.log(saludo);
```

## Borrar lineas

    Tips:
        ⇧ ⌘ K
        Ctrl + Shift + K

    PRO:
        Seleccionar todas las ocurrencias de la selección
        ⇧ ⌘ L
        Ctrl + Shift + L
*/

``` js
let NoMeBorres = ':)';
let Borrame = ':(';

NoMeBorres = '1';
Borrame    = 'a';
NoMeBorres = '1';
Borrame    = 'a';
```


// Resultado final (sin los comentarios claro.)

// let NoMeBorres = ':)';

// NoMeBorres = '1';
// NoMeBorres = '1';


## Deshacer - Rehacer

    Tips:
        ⌘ Z
        ⌘ ⇧ Z
        Ctrl +Z
        Ctrl + Shift + Z

*/

``` js
function holamundo() {
  return 'Saludos a todos';
}
```

## Modo zen

```
    Objetivo:
        Cero distracciones
        Ocultar Mostrar sidebar
    
    tips:
        ⌘ B
        Ctrl + B

        ⌘ K Z
        Ctrl + K Z
```

## Terminal

    tips:
        ⌃ `
        Ctrl + `
 -->


<p>
    Ejecutar el comando
    ng serve
</p>

## Crear Shortcuts

1.  menu code o click en las 3 lineas
2.  File
3.  preferences
4.  keyboard shorcuts

Atajo: Ctrl + k Ctrl + s

Buscamos el comando y dar doble click y escribir el atajo y enter.


## Emment-wrap

  tips:
        ⇧ ⌘ P
        Ctrl + SHIFT + P
        shorcut personalizado: Ctrl + a

        Buscar: Wrap with abbreviation
                debe de quedar el ng serve así
                <code>ng serve</code>



<p>
    Ejecutar el comando
    ng serve
</p>


## Ventanas cerrar abrir

    tips:
        ⌘ W      Cerrar tab  / Cerrar aplicación
        ⌘ K ⌘ W  Cerrar todas
        ⇧ ⌘ T    Reabrir anterior
        ⌃ TAB    Cambiar de tab

        Ctrl + W            Cerrar tab
        Ctrl + K  Ctrl + W  Cerrar todas
        Ctrl + Shift + T    Reabrir anterior
        Ctrl + TAB          Cambiar de tab
 -->

 <h1>
     Abramos muchos tabs para probar
 </h1>

## **Multi cursor**

## Clonar lineas

    Tips:
        * Puede cambiar, revisar los shortcuts

        ⇧ ⌥ D
        Shift + Alt + flecha hacia abajo
    Pro: (Revisar shortcuts)
        Copy line down
        ⌘ K ⌘ S 
        Ctrl + K Ctrl + S
        
-->

<span>Hola</span>



<!-- Objetivo -->

<span>Hola</span>
<span>Hola</span>
<span>Hola</span>
<span>Hola</span>
<span>Hola</span>


## Crear cursores arriba y abajo

    Tips:
        ⇧ ⌥ ↑ / ↓
        Ctrl + Alt+ ↑ / ↓
       
-->

<!-- Desde aquí -->




<!-- Hasta aquí -->



<!-- Objetivo -->

<li>Hola Mundo</li>
<li>Hola Mundo</li>
<li>Hola Mundo</li>
<li>Hola Mundo</li>
<li>Hola Mundo</li>
<li>Hola Mundo</li>


## Multi cursor **Copy**
