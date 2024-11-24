---
title: Base de datos
layout: Base de datos
---
title: Lenguaje de marcas
layout: Lenguaje de marcas
---
index.md
markdown
Copiar código
# Mi Portafolio de Asignaturas

Bienvenido/a a mi portafolio. En este espacio encontrarás información organizada por asignaturas. Haz clic en el índice para ir directamente a cada sección.

---

## Índice

1. [Bases de Datos](#bases-de-datos)
2. [Sistemas Informáticos](#sistemas-informáticos)
3. [Entornos de Desarrollo](#entornos-de-desarrollo)
4. [Lenguaje de Marcas](#lenguaje-de-marcas)
5. [FOL](#fol)
6. [Inglés](#inglés)

---

## Bases de Datos

### Descripción

En esta sección se incluyen los contenidos relacionados con el diseño, gestión y manipulación de bases de datos.

### Ejemplos

- **Modelo Relacional**: Diseños de esquemas de base de datos.
- **SQL**: Consultas, creación de tablas y relaciones.
  ```sql
  SELECT nombre, edad 
  FROM alumnos 
  WHERE edad > 18;
Proyectos: Gestión de inventarios, registros escolares.
Herramientas Utilizadas
MySQL
PostgreSQL
SQLite
Sistemas Informáticos
Descripción
Aspectos técnicos sobre la administración de sistemas operativos y redes.

Ejemplos
Montaje de equipos: Configuración de hardware y software.
Administración Linux: Comandos básicos de terminal.
bash
Copiar código
sudo apt update
sudo apt upgrade
Redes: Configuración de routers y redes locales.
Entornos de Desarrollo
Descripción
Sección dedicada a la configuración de entornos de programación, herramientas y metodologías de trabajo.

Ejemplos
Configuración de IDEs: VS Code, IntelliJ, Eclipse.
Uso de Git y GitHub para control de versiones.
CI/CD Pipelines con GitHub Actions:
yaml
Copiar código
name: Build and Test
on: [push]
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - name: Run tests
        run: npm test
Lenguaje de Marcas
Descripción
Estudio y uso de lenguajes como HTML, XML, y JSON.

Ejemplos
Creación de sitios web básicos con HTML5.
Uso de XML para definir datos estructurados.
xml
Copiar código
<alumno>
    <nombre>Juan Pérez</nombre>
    <edad>20</edad>
</alumno>
FOL (Formación y Orientación Laboral)
Descripción
Conceptos relacionados con el mundo laboral, derechos y emprendimiento.

Ejemplos
Derechos Laborales: Resumen de derechos básicos del trabajador.
Prevención de Riesgos Laborales: Identificación de riesgos y medidas preventivas.
Proyectos de Emprendimiento: Creación de planes de negocio.
Inglés
Descripción
Sección dedicada al aprendizaje del inglés técnico aplicado a la informática.

Ejemplos
Vocabulario Técnico:
Server: Servidor
Database: Base de datos
Prácticas de Traducción:
Traducción de manuales de usuario y documentación técnica.
Ejemplo de texto:
plaintext
Copiar código
"To access the server, use the following credentials..."
Contacto
Si deseas más información, no dudes en contactarme.

markdown
Copiar código

### ¿Cómo usarlo con GitHub Pages?
1. **Configura el repositorio:**  
   - Coloca este archivo como `index.md` en la raíz del repositorio.
   - Asegúrate de habilitar **GitHub Pages** en la configuración del repositorio y selecciona la rama principal como fuente.

2. **Personaliza el estilo:**  
   GitHub Pages usará automáticamente un tema predeterminado para mostrar el archivo Markdown como una página web. Puedes personalizar el diseño eligiendo un tema en las configuraciones o añadiendo un archivo `/_config.yml` para usar un tema de Jekyll.

Ejemplo de configuración para usar un tema de Jekyll:
```yaml
theme: minima


[Just the Docs]: https://just-the-docs.github.io/just-the-docs/
[GitHub Pages]: https://docs.github.com/en/pages
[README]: https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md
[Jekyll]: https://jekyllrb.com
[GitHub Pages / Actions workflow]: https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/
[use this template]: https://github.com/just-the-docs/just-the-docs-template/generate
