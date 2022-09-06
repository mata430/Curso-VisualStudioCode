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
  - [Volver a seleccionar](#volver-a-seleccionar)
  - [Crear cursores arriba y abajo](#crear-cursores-arriba-y-abajo)
  - [Seleccionar toda la linea](#seleccionar-toda-la-linea)
  - [Multi cursor en lineas no censcutivas](#multi-cursor-en-lineas-no-censcutivas)
  - [Comparar codigo de forma rapida y automatica](#comparar-codigo-de-forma-rapida-y-automatica)
  - [Multi cursor **Copy**](#multi-cursor-copy)
  - [Multi cursor para formato](#multi-cursor-para-formato)
  - [Multi cursor Lowercase y Uppercase](#multi-cursor-lowercase-y-uppercase)
  - [Multiples cursores en posiciones especificas](#multiples-cursores-en-posiciones-especificas)
  - [Siguiente ocurrencia](#siguiente-ocurrencia)
  - [Creacion de un arreglo de dias](#creacion-de-un-arreglo-de-dias)
  - [clases y definiciones](#clases-y-definiciones)
  - [Ir a una linea](#ir-a-una-linea)
  - [Previsualizar Markdown](#previsualizar-markdown)
  - [Replace Symbol](#replace-symbol)
  - [Snippets basicos](#snippets-basicos)
  - [Extencion TODO](#extencion-todo)
  - [Extencion Bookmarks](#extencion-bookmarks)

## Movimintos de lineas

Atajo:
⌥ ↓ / ⌥ ↑
Alt + ↑ / ↓

```html
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

1.  Selccionamos las lineas que queremos mover.
    ⌥ ↓ / ⌥ ↑
    Alt + ↑ / ↓

```html
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
    <span
      >Nada - [CURSO DE VISUAL ESTUDIO CODE](#curso-de-visual-estudio-code) -
      [Movimintos de lineas](#movimintos-de-lineas) - [Movimintos de 2 o mas
      lineas](#movimintos-de-2-o-mas-lineas)importante 3</span
    >
  </li>
  <li>
    <span>línea 2</span>
    <span>Nada importante 2</span>
  </li>
</ul>
```

## Comentarios

Colocar el cursor en la linea a comentar


    Tips:
        ⌘ /
        ⇧ ⌥ A
        Ctrl + ,

Selecionar el bloque a comentar

        Ctrl + .


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

\*/

```js
import { saludar } from "./extra/funciones";

const saludo = saludar("Thanos");

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

\*/

```js
let NoMeBorres = ":)";
let Borrame = ":(";

NoMeBorres = "1";
Borrame = "a";
NoMeBorres = "1";
Borrame = "a";
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

\*/

```js
function holamundo() {
  return "Saludos a todos";
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
shorcut personalizado: Alt + a

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
        Shift + Alt + ⬇️
        Alt + d

## Volver a seleccionar

    Tips:
        Ctrl + u

## Crear cursores arriba y abajo

    Tips:
        ⇧ ⌥ ↑ / ↓
        Ctrl + Alt+ ↑ / ↓

## Seleccionar toda la linea

    Tips:
        Cmd + l
        Ctrl + l

## Multi cursor en lineas no censcutivas

    Tips:
        option presionado y click donde queremos el cursor
        Alt presionado y click donde queremos el cursor
        para deseleccionar solo manten precionado alt y vuelve a dar click

## Comparar codigo de forma rapida y automatica

1. Elegir los dos archivos a comparar
2. Shift + Ctrl + p
3. Escribimos compare Active File With...
4. Elejimos con que archivo lo queremos comprarar





## Multi cursor **Copy**

    Tips:
        ⇧ ⌥ ↑ / ↓
        Ctrl + Alt+ ↑ / ↓

-->

<span class="amarillo">amarillo</span>
<span class="rojo">rojo</span>
<span class="verde">verde</span>
<span class="naranja">naranja</span>
<span class="morado">morado</span>
<span class="negro">negro</span>
<span class="blanco">blanco</span>

<!-- Objetivo final -->

<span class="amarillo">amarillo</span>
<span class="rojo">rojo</span>
<span class="verde">verde</span>
<span class="naranja">naranja</span>
<span class="morado">morado</span>
<span class="negro">negro</span>
<span class="blanco">blanco</span>

## Multi cursor para formato

    Tips:
        ⇧ ⌥ ↑ / ↓
        Ctrl + Alt+ ↑ / ↓

```js
const hulk = "brouce banner";
const Hawkeye = "cinton francis";
const ironman = "tony stark";
const spiderman = "peter parker";
const viudaNegra = "natalia romanova";
```

// Objetivo final (sin los comentarios)
// const hulk = 'brouce banner';
// const Hawkeye = 'cinton francis';
// const ironman = 'tony stark';
// const spiderman = 'peter parker';
// const viudaNegra = 'natalia romanova';

## Multi cursor Lowercase y Uppercase

    Tips:
        ⇧ ⌥ ↑ / ↓
        ⌃ ⇧ U
        ⌃ ⇧ L

        Ctrl + Alt+ ↑ / ↓
        Shift + flecha derecha
        Ctrl + Alt + U
        Ctrl + Alt + L
        Ctrl + flecha derecha
        Shift + flecha derecha
        Ctrl + Alt + U
        Ctrl + Alt + L

    Pro:
        Mostrar la paleta de comandos
        ⇧ ⌘ P, F1
        Ctrl + Shift + P, F1

\*/

function capitalizados() {

    const hulk       = 'brouce Banner';
    const Hawkeye    = 'cinton Francis';
    const ironman    = 'tony Stark';
    const spiderman  = 'peter Parker';
    const viudaNegra = 'natalia Romanova';

}

function minusculas() {

    const hulk       = 'brouce banner';
    const hawkeye    = 'cinton francis';
    const ironman    = 'tony stark';
    const spiderman  = 'peter parker';
    const viudanegra = 'natalia romanova';

}

// Objetivo final (sin los comentarios)

function capitalizadosDemo() {

    const hulk       = 'Brouce Banner';
    const Hawkeye    = 'Cinton Francis';
    const ironman    = 'Tony Stark';
    const spiderman  = 'Peter Parker';
    const viudaNegra = 'Natalia Romanova';

}

function minusculasDemo() {

    const hulk       = 'brouce banner';
    const hawkeye    = 'cinton francis';
    const ironman    = 'tony stark';
    const spiderman  = 'peter parker';
    const viudanegra = 'natalia romanova';

}

## Multiples cursores en posiciones especificas

    Tip:
        Mantener ⌘ + Doble click
        Mantener ⌘ + Seleccionar

        Mantener Alt + Doble click
        Mantener Alt + Seleccionar

-->

<span class="amarillo">amarillo</span>

<p class="rojo">rojo</p>
<div-personalizado class="verde">verde</div-personalizado>
<bold class="naranja">naranja</bold>
<otro-div-complejo class="naranja-azul">naranja-azul</otro-div-complejo>

<!-- Objetivo final -->

<span class="amarillo">amarillo</span>

<p class="rojo">rojo</p>
<div-personalizado class="verde">verde</div-personalizado>
<bold class="naranja">naranja</bold>
<otro-div-complejo class="naranja-azul">naranja-azul</otro-div-complejo>

## Siguiente ocurrencia

    Tip:
        ⌘ + D

        Ctrl + D

-->

<li>
  <li>Uno</li>
  <li>Dos</li>
  <li>Cuarenta y cinco</li>
  <li>Un millón, ciento cincuenta mil</li>
</li>

<!-- Objetivo final -->
<ul>
    <li>Uno</li>
    <li>Dos</li>
    <li>Cuarenta y cinco</li>
    <li>Un millón, ciento cincuenta mil</li>
</ul>

## Creacion de un arreglo de dias

    Tips:
        ⇧ ⌥ ↑ / ↓
        Ctrl + Alt+ ↑ / ↓

\*/

// Crear un arreglo con los días de la semana

// Objetivo final

```js
const diasDemo = [
  "lunes",
  "martes",
  "miércoles",
  "jueves",
  "viernes",
  "sábado",
  "domingo",
];
```

## clases y definiciones

    Tips:
        ⌘ P => luego escribir la @
        ⇧ ⌘ O

        Ctrl + P => luego escribir la @
        Ctrl + Shift = O

        Se pueden agrupar si después de la @, se escriben :

\*/

class SuperHeroe {

    nombre: string;
    poder: string;
    edad: number;
    pasatiempo: string;

    // tslint:disable-next-line:variable-name
    private _nombreSecreto: string;

    constructor() { }

    usarPoder() {}

    volar() {}

    correr() {}

    caminar() {}

    revivir() {}

    // Sólo para demostración
    // tslint:disable-next-line:member-ordering
    nombre2: string;
    // tslint:disable-next-line:member-ordering
    poder2: string;
    // tslint:disable-next-line:member-ordering
    edad2: number;
    // tslint:disable-next-line:member-ordering
    pasatiempo3: string;

    set nombreSecreto(nombre) {
        this._nombreSecreto = nombre;
    }

    get nombreSecreto() {
        return this._nombreSecreto;
    }

}

## Ir a una linea

    Tips:
        ⌃ G
        ⌘ P => luego escribir :

        Ctrl + G
        Ctrl + P => luego escribir la :

    Tarea:
        Borrar la clase en la línea 7798

\*/

## Previsualizar Markdown

command + P : Markdown Open Preview
command + P : Markdown Open Preview to the side

Ctrl + P : > Markdown Open Preview
Ctrl + P : > Markdown Open Preview to the side

## Replace Symbol

    Tips:
        Replace Symbol
        F2

\*/

```js
const wolverine = new SuperHeroe();
const ironman = new SuperHeroe();
const spiderman = new SuperHeroe();

function saludar() {
  return "El SuperHeroe Wolverine es genial!";
}

function gritar() {
  return "El SuperHeroe en este string no se debe de cambiar";
}
```

## Snippets basicos

## Extencion TODO

//FIXME: EJEMPLO 2
// TODO: EJEMPLO

##  Extencion Bookmarks

Ctrl + Alt + k
