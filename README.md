# Sistema web para deteccion de dermatitis canina con Deep Learning

Este proyecto presenta la base de una interfaz web enfocada en la deteccion temprana de dermatitis canina mediante tecnicas de deep learning.  
Actualmente incluye la pantalla inicial de acceso (login), que forma parte del flujo principal de una plataforma orientada al apoyo veterinario.

## Contexto del proyecto

La dermatitis canina es una afeccion frecuente en perros y su identificacion oportuna puede mejorar el tratamiento y el bienestar animal.  
El objetivo de este sistema web es servir como soporte digital para:

- Cargar y visualizar imagenes dermatologicas de pacientes caninos.
- Aplicar un modelo de deep learning para apoyar la deteccion de posibles lesiones.
- Centralizar la informacion de usuarios y resultados dentro de una experiencia web simple.

## Estado actual

En esta version se encuentra implementada la base visual de la pagina de inicio de sesion:

- Interfaz principal en `pgc.html`.
- Uso de recursos graficos referenciados en la carpeta `images/`.
- Estilos integrados en el mismo archivo HTML.

## Estructura del proyecto

```text
proyecto_vision/
|- pgc.html
|- README.md
`- images/           # Recursos graficos usados por la interfaz
```

> Nota: `pgc.html` hace referencia a imagenes como `images/logo.png`, `images/fondo.png`, etc.  
> Asegurate de mantener esa carpeta y nombres de archivos para que la vista cargue correctamente.

## Tecnologias usadas

- HTML5
- CSS3
- Bootstrap 5 (CDN)
- Google Fonts (CDN)

## Como ejecutar el proyecto

Este proyecto corre de forma local sin servidor.

1. Ubica el archivo `pgc.html`.
2. Haz doble clic sobre `pgc.html`.
3. Se abrira automaticamente en tu navegador predeterminado.

## Proximos pasos sugeridos

- Conectar el formulario de login con logica real de autenticacion.
- Integrar el modulo de carga y analisis de imagenes.
- Enlazar un modelo de deep learning entrenado para clasificacion de dermatitis canina.
- Agregar una vista de resultados y recomendaciones para apoyo al diagnostico veterinario.
