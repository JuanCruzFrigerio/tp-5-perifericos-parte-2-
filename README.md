# tp-5-perifericos-parte-2-


Descripción del proyecto

Este proyecto implementa una interfaz gráfica en Processing para el control y monitoreo de entradas y salidas digitales de Arduino, cumpliendo con los requisitos del Trabajo Práctico de Periféricos – Parte 2.

El sistema permite:

Visualizar en tiempo real el estado de las entradas digitales (pulsadores).

Visualizar el estado de las salidas digitales (LEDs).

Activar y desactivar los LEDs desde la interfaz gráfica utilizando el mouse.

Mantener una comunicación bidireccional entre Arduino y la PC mediante puerto serie.

Funcionalidades principales

📥 Entradas

Dos pulsadores conectados a Arduino.

El estado (ALTO / BAJO) se muestra en Processing mediante colores.

📤 Salidas

Dos LEDs conectados a Arduino.

Pueden activarse:

Desde los pulsadores físicos.

Desde la interfaz gráfica en Processing.

🔁 Comunicación bidireccional

Arduino envía continuamente el estado de las entradas.

Processing envía comandos para encender/apagar los LEDs.
