# 📘 Resumen de Algebra Lineal

Este repositorio contiene un resumen completo de la materia **Algebra Lineal**, diseñado para estudiantes de ingeniería. El documento incluye explicaciones teóricas, fórmulas clave y ejemplos prácticos.

---

## 🚀 Compilación del Documento

### 🛠️ Instalación de Dependencias

Para compilar el documento en **Arch Linux**, instala los siguientes paquetes:

```sh
sudo pacman -S texlive texlive-fontsrecommended texlive-langspanish biber
```

Estos paquetes incluyen todas las dependencias necesarias para trabajar con LaTeX.

### 📄 Generar el PDF

1. Sitúate en la raíz del repositorio.
2. Ejecuta el siguiente comando para compilar el documento:

   ```sh
   make
   ```

3. Para limpiar los archivos generados durante la compilación, utiliza:

   ```sh
   make clean
   make clsbib
   ```

   Esto dejará únicamente el documento final en formato PDF.

4. Si deseas explorar otras opciones de compilación, puedes usar:

   ```sh
   make help
   ```

---

## 📑 Índice de Contenidos

El resumen incluye los siguientes temas:

- Programación Lineal
- Espacios Vectoriales
- Matrices y Submatrices
- Espacios Metricos
- Funciones Lineales
- Diagonalización

---

## 📝 Notas Adicionales

- Este resumen está basado en el programa de la materia y los libros recomendados de la asignatura _Algebra Lineal_ de carreras de ingeniería en la **[Universidad de Mendoza](https://um.edu.ar/)**.
- Si encuentras algún error o tienes sugerencias, no dudes en abrir un _issue_ o enviar un _pull request_.

> [!IMPORTANT]
> Si se agregan imágenes al documento, es importante que se haga con `git lfs` para no llenar el repositorio con binarios. Ver documentación sobre [Git LFS](https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage).
> Un PR que no respete esta regla será rechazado.

---

## 📂 Estructura del Proyecto

- **`main.tex`**: Archivo principal del documento.
- **`chapters/`**: Contiene los capítulos organizados por temas.
- **`images/`**: Carpeta con las imágenes utilizadas en el resumen.
- **`styles/`**: Archivos de estilo personalizados para LaTeX.
- **`scripts/`**: Scripts auxiliares para cálculos y visualizaciones.

---

## 🛡️ Licencia

Este proyecto está bajo la licencia **[MIT](LICENSE)**. Siéntete libre de usarlo, modificarlo y compartirlo.

---