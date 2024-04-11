# Enunciado 1: Calculadora Simple
## Objetivo: Desarrollar una interfaz gráfica para una calculadora simple
utilizando `GridLayout` para organizar los botones numéricos y las
operaciones básicas (suma, resta, multiplicación, división), `BorderLayout`
para distribuir los componentes principales, y `BoxLayout` para alinear los
botones de operaciones especiales (como limpiar y calcular).
Requisitos:
1. Diseño General: Utiliza `BorderLayout` para estructurar la ventana principal
   de la calculadora. El área central (`CENTER`) debe contener los botones
   numéricos y de operaciones básicas organizados mediante un `GridLayout`.
2. Botones Numéricos y de Operaciones Básicas: Coloca un `JPanel` en el
   centro con un `GridLayout` de 4x4, donde cada celda tendrá un botón
   correspondiente a un número o una operación básica.
3. Pantalla de la Calculadora: Ubica un `JTextField` en la parte superior
   (`NORTH`) del `BorderLayout` para mostrar los números ingresados y el
   resultado de las operaciones.
   Programación - DANIEL CASTELAO
4. Botones de Operaciones Especiales: Añade un `JPanel` en el lado este
   (`EAST`) utilizando `BoxLayout` para colocar verticalmente los botones de
   operaciones especiales.
5. Interactividad: Implementa manejadores de eventos mínimos para que los
   botones numéricos actualicen el `JTextField`.