# doc_programacion_dispositivos_moviles

Context:

El Context de React es una característica incorporada en React que permite compartir datos entre componentes sin necesidad de pasar props manualmente a través de múltiples niveles de componentes. Context proporciona una forma de crear un estado global que se puede acceder desde cualquier componente en el árbol de componentes.

El Context consta de dos partes principales:

Provider: El componente Provider es responsable de proporcionar los datos o estado global a los componentes descendientes.

Consumer: El componente Consumer es utilizado por los componentes que necesitan acceder a los datos o estado proporcionados por el Provider.

El uso de Context es adecuado cuando se necesita compartir datos a través de múltiples niveles de componentes, evitando la propagación de props a través de componentes intermedios. Sin embargo, a medida que la aplicación crece en tamaño y complejidad, el uso exclusivo de Context puede volverse complicado de mantener y puede llevar a problemas de rendimiento.
