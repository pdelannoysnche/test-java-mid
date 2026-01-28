Claro, vamos a poner orden para que mañana tengas todo bajo control. Aquí tienes la hoja de ruta definitiva para montar el reto en GitHub Classroom y las instrucciones que debes enviarle a ella.

1. Configuración de la Tarea (Para ti)
Sigue estos pasos rápidos en GitHub Classroom:

Crea la Tarea: Dale a "Create Assignment".

Nombre: Java-Mid-Level-Challenge.

Deadline: Pon la hora de tu reunión de mañana.

Autograding: Como no eres técnico, no te vuelvas loco con los tests. Añade un "Run Command" con lo siguiente:

Setup command: (vacio)

Run command: javac *.java

Esto al menos te asegura que el código "arranca" y no tiene errores de escritura.

2. Instrucciones para la Desarrolladora (Copia y Pega)
Envía esto por correo o por la plataforma. Es un reto diseñado para que un "Mid-level" demuestre solidez:

🚀 Java Technical Challenge: Multi-Source Data Processor
Objetivo: Implementar un módulo de procesamiento de datos que combine múltiples fuentes de forma eficiente.

Requerimientos Técnicos:

Modelo de Datos: Crea una clase Transaction con id, amount, currency y status.

Java Streams: Dada una lista de transacciones:

Filtra las que tengan un amount superior a 50.

Transforma el status a "PROCESSED" usando .map().

Obtén la suma total de los montos filtrados.

Asincronía (CompletableFuture): Simula una llamada a una API externa para validar cada transacción. Debe ejecutarse de forma no bloqueante (asíncrona) y devolver un mensaje de confirmación al terminar todas.

Patrón de Diseño (Strategy): Implementa el patrón Strategy para calcular diferentes comisiones según la moneda (USD tiene 2%, EUR tiene 1%, otras 5%).

Clean Code: El código debe ser legible, usar nombres de variables claros y manejar posibles excepciones (ej. montos negativos).

Entrega: Realiza los "commits" y "push" necesarios en este repositorio de GitHub Classroom antes de la hora acordada.
