# doc_programacion_dispositivos_moviles

<<<<< hook-vs-hoc
Hooks:

Los Hooks son una característica introducida en React a partir de la versión 16.8. Los Hooks son funciones especiales que te permiten utilizar el estado y otras características de React en componentes de función sin necesidad de escribir una clase. Algunos de los Hooks más comunes son useState, useEffect, useContext, entre otros. Los Hooks ofrecen una forma más sencilla y concisa de manejar el estado y el ciclo de vida en los componentes de función.

HOC (Higher-Order Component):

Los Higher-Order Components (Componentes de Orden Superior) son funciones que toman un componente como argumento y retornan un nuevo componente mejorado. Los HOC permiten reutilizar lógica entre componentes de manera eficiente. Se utilizan para agregar funcionalidad adicional a los componentes existentes mediante la composición de componentes.
=======
TypeScript es un lenguaje de programación que se basa en JavaScript y agrega características adicionales de tipado estático:

1. Tipado estático: TypeScript permite declarar y especificar tipos de datos para variables, parámetros de funciones, propiedades de objetos, etc. Esto ayuda a detectar errores de tipo durante la compilación en lugar de tiempo de ejecución.

Ejemplo:

```typescript
let nombre: string = "Juan";
let edad: number = 25;
let esEstudiante: boolean = true;

function saludar(nombre: string): void {
  console.log(`¡Hola, ${nombre}!`);
}

saludar(nombre);
```

2. Inferencia de tipos: TypeScript puede inferir automáticamente el tipo de una variable en función del valor asignado. Esto evita la necesidad de especificar explícitamente el tipo en algunas ocasiones.

Ejemplo:

```typescript
let mensaje = "Hola, TypeScript"; // TypeScript infiere que 'mensaje' es de tipo string

console.log(mensaje);
```

3. Interfaces: Las interfaces en TypeScript permiten definir la estructura de un objeto, especificando los nombres y tipos de sus propiedades y métodos. Ayudan a garantizar la consistencia y compatibilidad en el uso de objetos.

Ejemplo:

```typescript
interface Persona {
  nombre: string;
  edad: number;
  saludar(): void;
}

let persona: Persona = {
  nombre: "Ana",
  edad: 30,
  saludar() {
    console.log(`¡Hola, soy ${this.nombre} y tengo ${this.edad} años!`);
  },
};

persona.saludar();
```

4. Clases: TypeScript admite la programación orientada a objetos mediante la definición de clases. Las clases pueden tener propiedades, métodos, constructores y herencia.

Ejemplo:

```typescript
class Animal {
  nombre: string;

  constructor(nombre: string) {
    this.nombre = nombre;
  }

  emitirSonido() {
    console.log("¡Haciendo sonidos!");
  }
}

class Perro extends Animal {
  raza: string;

  constructor(nombre: string, raza: string) {
    super(nombre);
    this.raza = raza;
  }

  emitirSonido() {
    console.log("¡Guau, guau!");
  }
}

let miPerro = new Perro("Bobby", "Labrador");
miPerro.emitirSonido();
```

5. Módulos y importaciones: TypeScript permite organizar el código en módulos, lo que facilita la reutilización y la organización del código en partes separadas. Se pueden importar y exportar módulos para utilizar sus funcionalidades en otros archivos.

Ejemplo:
Archivo "math.ts":

```typescript
export function sumar(a: number, b: number): number {
  return a + b;
}

export function restar(a: number, b: number): number {
  return a - b;
}
```

Archivo "main.ts":

```typescript
import { sumar, restar } from "./math";

console.log(sumar(5, 3));
console.log(restar(10, 4));
```

Estos son solo algunos aspectos básicos de TypeScript. El lenguaje ofrece muchas más características, como tipos avanzados, genéricos, decoradores, entre otros. Con TypeScript, puedes escribir código más robusto, legible y mantenible al tiempo que aprovechas el ecosistema de JavaScript.
>>>>main
