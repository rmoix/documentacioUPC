# Documentació UPC



**Opcions escollides:**
* Llenguatge de marcat: **Git-flavoured Markdown**
* Eina de construcció de documentació: **Mkdocs**
* Plataforma on hostatjar la documentació: **GitHub pages**

## Mkdocs

Mkdocs és un generador de pàgines estàtiques a partir de fitxers markdown (*.md). El seu funicionament és mol senzill i està pensat per a generar documentació atractiva de manera molt àgil.

### Instal·lació

### Configuració

### Ús

**Crear projecte:**  
`mkdocs new my-project`  
`cd my-project`

**Editar les pàgines**  
`gedit index.md`

**Vista prèvia**   
`mkdocs serve`  
Mkdocs disposa d'un mini servidor web integrat. El lloc web s'actualitza automàticament si es fa qualsevol canvi.


# Fonts d'informació

[Documentation Guide - Write The Docs](http://writethedocs.org/guide)






















For half documentation visit [mkdocs.org](http://mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs help` - Print this help message.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
