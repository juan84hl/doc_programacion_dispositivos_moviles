# doc_programacion_dispositivos_moviles

Redux:

Redux es una biblioteca de manejo de estado para JavaScript, ampliamente utilizada con React. Se basa en el patrón de diseño Flux y se enfoca en mantener un único estado global para toda la aplicación.
Redux proporciona un flujo de datos unidireccional, lo que significa que los cambios en el estado son predecibles y se actualizan de manera coherente en toda la aplicación.

Principios clave de Redux:

Store: El estado de la aplicación se almacena en un objeto central llamado store. El store es inmutable y solo se puede modificar a través de acciones.

Acciones: Son objetos planos que describen un cambio en el estado de la aplicación. Las acciones se envían al store para realizar modificaciones en el estado.

Reducers: Son funciones puras que especifican cómo se actualiza el estado en respuesta a una acción. Los reducers toman el estado actual y una acción, y devuelven un nuevo estado actualizado.

Dispatch: Es el método utilizado para enviar una acción al store y desencadenar la actualización del estado.

Suscripción: Los componentes pueden suscribirse al store para recibir actualizaciones automáticas cada vez que el estado cambie.

El uso de Redux puede ser beneficioso en aplicaciones complejas con un flujo de datos complejo y donde se requiere un manejo avanzado del estado. Sin embargo, puede resultar más verboso en comparación con otras soluciones más livianas como el Context de React.
