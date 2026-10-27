# Informe del CJC sobre propuestas para el PND

Proyecto LaTeX para editar en Overleaf. El cuerpo reproduce el texto completo de las diez propuestas extensas preparadas el 23 de octubre de 2026 sobre productividad, inteligencia artificial, investigación y financiación empresarial. La conversión conserva párrafos, instrumentos, ejemplos, condiciones y enlaces, sin resumir ni reescribir el contenido. La portada y el resumen ejecutivo utilizan el formato del CJC. La selección de cinco para el documento de máximo tres páginas de la facultad se realiza por separado.

## Edición en Overleaf

1. Sincronizar este repositorio desde la integración GitHub del proyecto de Overleaf o importar su ZIP como un proyecto nuevo.
2. Seleccionar `main.tex` como documento principal y **pdfLaTeX** como compilador.
3. Compilar. No se requiere BibTeX, archivos externos ni ejecución de scripts. Las referencias se conservan como enlaces dentro del texto original.

## Archivos

- `main.tex` reúne las partes del informe.
- `Paper/configuracion.tex` contiene formato, título, autoría, fecha y etiqueta de edición.
- `Paper/sections/Portada.tex` contiene la portada.
- `Paper/sections/ResumenEjecutivo.tex` contiene el resumen ejecutivo.
- `Paper/sections/Propuestas.tex` presenta las diez propuestas extensas como una enumeración del 1 al 10, con su contenido íntegro, sus fuentes enlazadas y el cierre sobre su articulación.
- `Paper/sections/MaterialComplementario.tex` contiene la referencia y el enlace a la matriz de Jorge Orozco.
- `Paper/sections/NotaIA.tex` contiene la nota de uso de IA, al final del informe.
- `Paper/figures/logo_cjc_palatino_horizontal.png` es el logo utilizado por los informes anteriores.

La etiqueta «Propuestas para el PND» puede reemplazarse por un número de informe cuando se asigne. La fecha es fija y se modifica en `Paper/configuracion.tex`.

## Material complementario

[Matriz de políticas e iniciativas de inteligencia artificial de Jorge Orozco](material_complementario/Matriz_politicas_IA_Jorge_Orozco_2026-10-21.xlsm). Archivo Excel en formato `.xlsm`, versión consultada el 21 de octubre de 2026, con todas las filas visibles. Contiene las hojas «Matriz evidencia», «Resumen» y «Criterios», y permite consultar experiencias internacionales, instrumentos y fuentes oficiales. El archivo se conserva sin modificar su contenido.

La matriz también está enlazada desde el informe, después del cuerpo de las propuestas y antes de la nota final de uso de IA.

## Formato de referencia

Se reutilizaron el logo, la serie, la portada, el recuadro del resumen y los encabezados de los proyectos [Informe Actividades](https://github.com/oliverpardo1979/Informe_Actividades), [Informes departamentales](https://github.com/oliverpardo1979/Informes-departamentales), [Informe Tamaño](https://github.com/oliverpardo1979/Informe_Tamano) e [Informe Educación](https://github.com/oliverpardo1979/Informe_Educacion). El cuerpo conserva el texto de las diez propuestas extensas preparadas por Oliver Pardo.

## Uso de inteligencia artificial

La nota al final del informe identifica el uso de IA generativa en la búsqueda y síntesis de antecedentes, la redacción y la preparación de LaTeX. La nota no atribuye a la IA la responsabilidad por los argumentos o las propuestas.
