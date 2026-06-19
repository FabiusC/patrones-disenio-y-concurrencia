# Recuperación de Diseño de Software para 23 Patrones de Diseño y 4 Patrones de Concurrencia

## Autor

Fabio Andres Hurtado Cardona

## Descripción del Proyecto

A partir de una serie de programas ejemplo desarrollados en Java o Python se hizo un ejercicio de ingeniería inversa para recuperar el diseño arquitectónico de los aplicativos, puntualmente diagramas de casos de uso, diagramas de secuencia para cada caso de uso, y diagramas de clases. Estos diseños se encuentran en los archivos de Enterprise Architect (`.qea` y `.eapx`) y se recomienda la versión 17 para abrirlos.

## Estructura del Repositorio

El repositorio está organizado en las siguientes categorías, y para cada patrón se incluye el **código fuente** y el archivo de **Enterprise Architect**:

### 1. Patrones de Diseño DASP

Contiene clasificaciones clásicas de los patrones de diseño aplicados:

- **Creacionales:** Builder, Abstract Factory, Factory Method, Prototype y Singleton.
- **Tratamiento de Colecciones:** Composite, Iterator, Flyweight, Visitor (y un Ejercicio práctico integrador de Visitador).
- **Estructurales:** Adapter, Bridge, Chain of Responsibility, Decorator, Facade y Proxy.
- **Comportamentales:** Command, State, Interpreter, Mediator, Memento, Template Method, Observer y Strategy.

### 2. Patrones de Concurrencia

Contiene ejercicios y proyectos relacionados con programación concurrente y el hilo de ejecución:

- Sección Crítica (Fiabilidad de Hilos e Inicialización Temprana).
- Suspensión Condicionada.
- Bloqueo - Cierre de Lectura/Escritura.
- Orden de Bloqueo - Cierre Consistente.
