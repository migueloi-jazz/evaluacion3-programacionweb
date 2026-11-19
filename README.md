# Evaluación N°3 - Programación Web

Aplicación web con Flask que resuelve dos ejercicios mediante formularios.

## Estructura del proyecto

```
Proyecto/
├── main.py                      # Aplicación Flask: rutas y lógica de los ejercicios
├── requirements.txt             # Dependencias del proyecto
├── templates/
│   ├── index.html               # Menú principal con dos botones
│   ├── ejercicio1.html          # Formulario de notas (Ejercicio 1)
│   └── ejercicio2.html          # Formulario de nombres (Ejercicio 2)
└── static/
    └── estilos.css              # Hoja de estilos
```

## Requisitos

- Python 3.10 o superior
- pip

## Notas

Antes de ejecutar, instala las dependencias:

   ```
   pip install -r requirements.txt
   ```

## Acerca de los ejercicios

- **Ejercicio 1:** Recibe tres notas (10-70) y un porcentaje de asistencia (0-100). Calcula el promedio con un decimal y muestra **APROBADO** si el promedio es superior a 50 y la asistencia a 75%. Si no se cumplen los criterios de aprobación muestra **REPROBADO**.

- **Ejercicio 2:** Recibe tres nombres y muestra cuál de ellos es más largo y cuántas letras tiene.