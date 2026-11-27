# Calculadora JavaFX

Calculadora de escritorio desarrollada en **Java** con **JavaFX**, con la interfaz diseñada en **FXML** mediante Scene Builder. Ejercicio del ciclo de Desarrollo de Aplicaciones Multiplataforma (DAM).

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaFX](https://img.shields.io/badge/JavaFX-2c5364?style=flat-square)
![FXML](https://img.shields.io/badge/FXML-Scene_Builder-7aa2f7?style=flat-square)

## Funcionalidades

- Pantalla de resultado alineada a la derecha y no editable.
- Teclado numérico del 0 al 9.
- Operaciones de suma, resta, multiplicación y división.
- Botón **C** para borrar y **=** para calcular el resultado.

## Interfaz

La ventana está construida con un `VBox` que contiene el visor (`TextField`) y un `GridPane` de 4x4 con los botones. Cada grupo de botones llama a su manejador en el controlador:

| Botones | Método del controlador |
|---|---|
| 0–9 | `pulsarNumero` |
| + − × ÷ | `pulsarOperacion` |
| C | `pulsarBorrar` |
| = | `pulsarIgual` |

## Estructura del repositorio

```
CalculadoraJavafx/
├── calculadora pro.fxml      # Vista de la calculadora (Scene Builder)
├── Calculadora - copia.zip   # Proyecto completo de IntelliJ IDEA
└── README.md
```

## Cómo ejecutarlo

1. Descarga y descomprime `Calculadora - copia.zip`.
2. Ábrelo con **IntelliJ IDEA** (File → Open).
3. Asegúrate de tener configurado un JDK y JavaFX.
4. Ejecuta la clase principal de la aplicación.

## Autor

**Carlos Valadés Fernández** · Estudiante de DAM en el IES Donoso Cortés
[GitHub](https://github.com/carlosvf19) · [LinkedIn](https://www.linkedin.com/in/carlosvaladesfernandez)
