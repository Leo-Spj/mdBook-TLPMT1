
# Curso - Teoria de Lenguages de Programación y Metodos de Traducción 1

Este repositorio contiene resúmenes estructurados del curso de Teoría de Lenguajes de Programación y Métodos de Traducción 1, realizado como parte del programa académico de la Universidad Tecnológica del Perú, carrera de Ingeniería de Software. 


## Objetivo

El objetivo de este proyecto es proporcionar resúmenes detallados y estructurados de las clases del curso, facilitando así la comprensión y el repaso de los conceptos clave abordados en el mismo.


## Uso

Los resúmenes pueden ser visualizados en línea utilizando mdBook o descargados y ejecutados localmente.

### Visualización en Línea

Puedes acceder a los resúmenes en línea utilizando mdBook. Visita [link al sitio web del libro](https://leo-spj.github.io/mdBook-TLPMT1) para comenzar a explorar.

### Uso Local

Si prefieres trabajar con los resúmenes localmente:

1. Clona este repositorio en tu máquina local.
2. Instala mdBook siguiendo las [instrucciones de instalación](https://github.com/rust-lang/mdBook#installation).
3. Navega al directorio de este proyecto `/mdBook-TLPMT1` y ejecuta el siguiente comando:
    
    ```bash
    mdbook serve
    ```
4. Abre tu navegador web y visita `http://localhost:3000` para ver los resúmenes.

## Funcionalidades Adicionales

Si estás interesado en utilizar gráficos Mermaid en mdBook puedes encontrar instrucciones completas sobre cómo instalar y utilizar esta funcionalidad en la [documentación de mdbook-mermaid](https://github.com/badboy/mdbook-mermaid?tab=readme-ov-file#installation).

Para visualizar correctamente las expresiones matemáticas en mdBook con MathJax, es necesario habilitar el soporte para MathJax en el archivo de configuración de mdBook, `book.toml`. Esto se puede hacer añadiendo la siguiente sección:

```toml
[output.html]
mathjax-support = true
```

Puedes encontrar instrucciones completas sobre la **habilitación** y **uso** en la [documentación de mdBook](https://rust-lang.github.io/mdBook/format/mathjax.html).


## Contribuciones

¡Las contribuciones son bienvenidas! Si encuentras errores, tienes sugerencias o deseas agregar más contenido, no dudes en abrir un problema o enviar una solicitud de extracción.

## Licencia

Este proyecto está bajo la licencia [Licencia MIT](LICENSE).

