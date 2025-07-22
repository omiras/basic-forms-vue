# Ejercicios con forumularios y Vue


Abre con Live Server cada uno de los ficheros index.html del ejercicio a ralizar

En alguno de ellos tendrás que [configurar el HTML](https://vuejs.org/guide/quick-start.html#using-the-global-build) para quea gobernado por Vue 


## ¿Algo va mal?


0. Intenta no pedir la solución directa a la IA.
1. Asegurate de que has hecho bien el [setup]((https://vuejs.org/guide/quick-start.html#using-the-global-build)) , engoblado todo el HTML por un contenedor `<div id="app"></div>` 
2. Echa un vistazo a la consola del navegador. Normalmente sucede que nos olvidamos importar algo o hay un error de sintaxis
<img src="https://oscarm.tinytake.com/media/17910d3?filename=1753086794204_TinyTake21-07-2025-10-33-00_638886835924646084.png&sub_type=thumbnail_preview&type=attachment&width=615&height=486" title="Powered by TinyTake Screen Capture"/>


### 1-real-time-character-counter

- Haz que tu ejercicio funcione exactamente como [esta demo](https://demo.100jsprojects.com/real-time-character-counter)
- Usa la directiva v-model adecuadamene. Mira este [ejemplo](https://vuejs.org/guide/essentials/forms.html#basic-usage) . Puedes hacer click en "Try it the Playground" para ver cómo funciona
- Solo necesitas una variable de estado 

### 2-weight-convertir

Convierte de _pounds_ a kilos

- Haz que tu ejercicio funcione exactamente como [esta demo](https://demo.100jsprojects.com/weight-converter)
- Muy parecido al ejercicio anterior: solo necesitas una variable de estado
- _Puede_ que necesites indicar a la directiva v-model que quieres convertir la información del input [en un number](https://vuejs.org/guide/essentials/forms.html#number)


### 3-loan-calculator

Este formulario permite calcular cuanto tienes que pagar al mes para una hipoteca, dado los meses a pagar y los intereses 

- Haz que tu ejercicio funcione lo más parecido posible a [esta demo](https://demo.100jsprojects.com/loan-calculator)
- Necesitamos 3 variables de estado
- Recuerda que entre `{{ }}` puedes poner cualquier expresión o cálculo JavaScript

### 4-tip-calculator

¿Cuánta propina se deja en tu país de origen en un restaurante?

- Haz que tu ejercicio funciona lo más parecido posible a [esta demo](https://demo.100jsprojects.com/tip-calculator)
- Necesitarás 3 variables de estado. 
<details>
  <summary>¿Qué variables - Clic para ayuda?</summary>
  <pre>
        const bill = ref(0);
        const tip = ref(0);
        const total = ref('');
  </pre>
</details

Fíjate que hasta que no hacemos clic en el botón _Calculate_ no se muestra el resultado. Vas a necesitar usar la directiva [v-on:click](https://vuejs.org/guide/essentials/event-handling.html#method-handlers)
