# Juego de la Vida en 3D con TensorFlow y P5

Este es un código de implementación del Juego de la Vida en 3D que utiliza la biblioteca TensorFlow, junto con HTML básico y estilos CSS básicos. El Juego de la Vida es un autómata celular desarrollado por el matemático británico John Horton Conway en 1970. Es un juego de cero jugadores que sigue reglas simples y genera patrones complejos.

## Requisitos

- Navegador web moderno que admita HTML5 y JavaScript.

## TensorFlow

El código utiliza TensorFlow, una biblioteca de código abierto para aprendizaje automático y redes neuronales. TensorFlow ofrece una amplia gama de herramientas y funcionalidades para construir y entrenar modelos de aprendizaje automático.

En este caso, TensorFlow se utiliza para realizar la convolución de la matriz del Juego de la Vida. La convolución es un proceso matemático que combina dos funciones para producir una tercera función que representa cómo una función influye en la otra. En el contexto del Juego de la Vida, la convolución se utiliza para aplicar las reglas del juego y determinar el estado de cada celda en la siguiente generación.

El código utiliza la funcionalidad de convolución de TensorFlow para convolucionar la matriz del Juego de la Vida con un kernel específico. El kernel es una matriz tridimensional que define las reglas de supervivencia y muerte de los cubos en el juego. A través de la convolución, se obtiene una nueva matriz que representa la siguiente generación del juego.

## Cómo ejecutar el juego

1. Descarga todos los archivos y colócalos en una carpeta.
2. Abre el archivo HTML en tu navegador web.
3. El juego se iniciará automáticamente y se mostrará en 3D.

## Controles del juego

- **Espacio (barra espaciadora)**: Genera una nueva matriz aleatoria. Cada celda de la matriz puede estar viva (representada por un cubo) o muerta.
- **C**: Inicia o detiene la actualización automática de la matriz. Cuando está activada, la matriz se actualizará en cada fotograma del juego según las reglas del Juego de la Vida.
- **Mostrar/Ocultar tabla**: Puedes mostrar u ocultar la tabla de kernel haciendo clic en el botón "Mostrar/Ocultar tabla" en la interfaz. La tabla de kernel permite personalizar las reglas del juego.

## Personalización

Puedes personalizar el juego ajustando los siguientes parámetros:

- **matrixSize**: Tamaño de la matriz. Por defecto, el tamaño de la matriz es de 50x50x50 (50 cubos en cada dimensión). Puedes ajustar este valor para cambiar el tamaño de la matriz en el juego.
- **cubeSize**: Tamaño de cada cubo en el juego. Por defecto, el tamaño de cada cubo es de 10 unidades. Puedes ajustar este valor para cambiar el tamaño de los cubos en el juego.
- **maxAliveCubes**: Límite máximo de cubos vivos. Por defecto, el límite máximo es de 1000 cubos vivos. Puedes ajustar este valor para cambiar el número máximo de cubos vivos en el juego. Cuando se alcanza este límite, se generará una nueva matriz aleatoria.
- **providedkernel**: El kernel predeterminado es una matriz tridimensional que contiene las reglas del Juego de la Vida. Puedes ajustar los valores de esta matriz para cambiar las reglas del juego. La tabla en la interfaz te permite editar estos valores de manera más conveniente.

## Créditos

- Este juego de la vida en 3D fue implementado utilizando el lenguaje de programación JavaScript y las bibliotecas p5.js y TensorFlow.
- El Juego de la Vida fue creado por [John Horton Conway](https://en.wikipedia.org/wiki/John_Horton_Conway) en 1970.
- TensorFlow es una biblioteca de aprendizaje automático desarrollada por Google.
- La implementación y el código base fueron creados por el autor original del código.

¡Disfruta jugando al Juego de la Vida en 3D y experimenta con diferentes configuraciones y reglas para crear patrones interesantes utilizando la potencia de TensorFlow!