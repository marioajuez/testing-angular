## Curso de Angular: Unit Testing para Formularios
<hr>

## Repositorio - GITHUB
https://github.com/platzi/curso-angular-unit-testing-forms

### contenido 

- [Test components](#2)
- [test servicios](#3)
- [Test forms](#3)

## <a id="3"></a> TEST FORMS

  ### ***TESTING HELPERS --- UTENSILIOS REUTILIZA FUNCIONES***

   - ## Async data
   - ## Finders
   - ## GetText
   - ## Click


## <a id="2"></a>Problema

  Los problemas estan relacionados a los distintos ecosistemas o frameworks (React, Angular, Vue), puesto que que estos no pueden coexistir entre sí, por lo que los Web Components al estar fundamentados en JavaScript puro, brinda más compatabilidad.

- El desarrollo web se hace más complicado
  - Actualmente se tiene un ecosistema gigante de JavaScript
    - Varias tecnologías no pueden co existir en un mismo proyecto a la vez, como ser angular con react
  - Entonces debemos elegir bien un stack de tecnologías
 - Para solucionar este problema existen Web Components:
    - Usan estándares web, para conseguir el mismo resultado e incluso mejor
    - No necesitamos cargar ninguna librería para obtener una arquitectura más escalable
[Mas información](https://developer.mozilla.org/es/docs/Web/Web_Components)
## <a id="3"></a>¿Que son los componentes web?

 El desarrollo web actualmente se está volviendo complicado debido a que existen muchas tecnologías que si bien facilitan el desarrollo no están dejando usar otras para un mismo proyecto, es ahi donde entran los webs components para obtener el mismo resultado con web api’s

  **constructor**: Directamente desde el JavaScript Engine, el constructor nos servirá para definir y cargar todas las variables en memoria que necesitemos, es mala práctica pintar el componente aquí.

  **connectedCallback**: Cuando el componente ya está pintado dentro del DOM ypodemos hacer uso de él.

  **attributeChangedCallback**: Cuando un atributo de nuestro componente cambia.

  **disconnectedCallback**: Cuando el componente se “destruye” o se quita del DOM.

  **adoptedCallback**: Cuando el componente es movido a un nuevo DOM, básicamente cuando es pintado desde un iframe por ejemplo 😄.

  Más información sobre este lifecycle aquí (en español):

  - [Mas información](https://developer.mozilla.org/es/docs/Web/Web_Components/Using_custom_elements#usando_callbacks_de_ciclo_de_vida)

<p align="center">
    <img src="./source\life-cicle-web-components.jpg" width="500" title="Ciclo de vida"/>
</p>

## <a id="6"></a>  Slots
  - ### <a id="6.1"></a> Content slots
  - ### <a id="6.2"></a> Multi content slots
  - ### <a id="6.3"></a> Atributos

## <a id="7"></a>  Estilos en components
  - ### <a id="6.1"></a> :host
  - ### <a id="6.2"></a> ::slotted
  - ### <a id="6.3"></a> CSS custom propierties

## <a id="8"></a>  Integrar componentes de terceros
## <a id="9"></a>  Proyectos


  

  ```text
folder1/
└── folder2/
    ├── folder3/
    │   ├── file1
    │   └── file2
    └── folder4/
        ├── file3
        └── file4
```


``` javascript
const prueba = '';
```







