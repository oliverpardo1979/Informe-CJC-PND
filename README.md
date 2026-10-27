# Informe del CJC sobre propuestas para el PND

Proyecto LaTeX para editar en Overleaf. El cuerpo desarrolla las diez propuestas extensas preparadas el 23 de octubre de 2026 sobre productividad, inteligencia artificial, investigación y financiación empresarial. Cada propuesta incluye su desarrollo jurídico, los referentes legales internacionales y el articulado completo correspondiente. La revisión de lectura del 26 de octubre precisa referentes, secuencia y conexiones para equipos técnicos del DNP y del Gobierno. Conserva las diez medidas, sus argumentos, ejemplos y enlaces. Los 18 bloques de articulado y los diez textos para las Bases se mantuvieron sin cambios durante esa revisión. La portada y el resumen ejecutivo utilizan el formato del CJC. La selección de cinco para el documento de máximo tres páginas de la facultad se realiza por separado.

## Edición en Overleaf

1. Sincronizar este repositorio desde la integración GitHub del proyecto de Overleaf o importar su ZIP como un proyecto nuevo.
2. Seleccionar `main.tex` como documento principal y **pdfLaTeX** como compilador.
3. Compilar. No se requiere BibTeX, archivos externos ni ejecución de scripts. Las referencias se conservan como enlaces dentro del texto original.

## Archivos

- `main.tex` reúne las partes del informe.
- `Paper/configuracion.tex` contiene formato, título, autoría, fecha y etiqueta de edición.
- `Paper/sections/Portada.tex` contiene la portada.
- `Paper/sections/ResumenEjecutivo.tex` contiene el resumen ejecutivo.
- `Paper/sections/Propuestas.tex` contiene las diez propuestas extensas, enumeradas del 1 al 10. Dentro de cada una están el texto anterior, el fundamento jurídico y los artículos completos. También incluye el cierre sobre su articulación y las condiciones generales de instrumentación.
- `Paper/sections/MaterialComplementario.tex` contiene la referencia y el enlace a la matriz de Jorge Orozco.
- `Paper/sections/NotaIA.tex` contiene la nota de uso de IA, al final del informe.
- `Paper/figures/logo_cjc_palatino_horizontal.png` es el logo utilizado por los informes anteriores.

La etiqueta «Propuestas para el PND» puede reemplazarse por un número de informe cuando se asigne. La fecha es fija y se modifica en `Paper/configuracion.tex`.

## Material complementario

[Matriz de políticas e iniciativas de inteligencia artificial de Jorge Orozco](material_complementario/Matriz_politicas_IA_Jorge_Orozco_2026-10-21.xlsm). Archivo Excel en formato `.xlsm`, versión consultada el 21 de octubre de 2026, con todas las filas visibles. Contiene las hojas «Matriz evidencia», «Resumen» y «Criterios», y permite consultar experiencias internacionales, instrumentos y fuentes oficiales. El archivo se conserva sin modificar su contenido.

La matriz también está enlazada desde el informe, después del cuerpo de las propuestas y antes de la nota final de uso de IA.

## Dónde editar títulos, subtítulos y artículos

- Título y subtítulo de portada, en `Paper/configuracion.tex`, comandos `reporttitle` y `reportsubtitle`.
- Títulos de propuestas, en `Paper/sections/Propuestas.tex`, líneas que comienzan con `\item \textbf{...}`.
- Subtítulos y artículos completos, en ese mismo archivo, dentro de cada propuesta. Buscar «Desarrollo jurídico y articulado propuesto» o «Artículo P1», «Artículo P2» y así sucesivamente.
- Los ocho artículos F1 a F8 de reforma del ahorro pensional están completos dentro de la propuesta 10.

## Desarrollo jurídico dentro de las propuestas

El informe incorpora, con corte de consulta del 26 de octubre de 2026, la revisión de los PND de 2015, 2019 y 2023, las normas sectoriales colombianas y los referentes legales de Reino Unido, Singapur, Canadá, Estados Unidos y la Unión Europea. Ese contenido se distribuye dentro de las diez propuestas y se compila con `main.tex`. No requiere seleccionar otro documento ni consultar un anexo para leer el articulado.

Cada propuesta incluye un artículo candidato P1 a P10 para el PND. Cuando las facultades vigentes y las Bases sean suficientes, el texto indica esa alternativa. La propuesta 10 incluye además los ocho artículos F1 a F8 para una reforma pensional cuyo trámite legislativo se plantea por separado de la ley del Plan. Su presentación editorial dentro de la propuesta no supone que todos deban aprobarse como artículos del PND.

Los artículos P requieren conexión con programas específicos de las próximas Bases y del plan de inversiones. Los artículos F necesitan actualización de concordancias al radicar, revisión de derechos, efectos fiscales y actuariales y reglas de transición. No se fija un nuevo capital mínimo sin estudio de suficiencia. La nota de uso de IA permanece al final del informe.

## Formato de referencia

Se reutilizaron el logo, la serie, la portada, el recuadro del resumen y los encabezados de los proyectos [Informe Actividades](https://github.com/oliverpardo1979/Informe_Actividades), [Informes departamentales](https://github.com/oliverpardo1979/Informes-departamentales), [Informe Tamaño](https://github.com/oliverpardo1979/Informe_Tamano) e [Informe Educación](https://github.com/oliverpardo1979/Informe_Educacion). El cuerpo conserva el texto de las diez propuestas extensas preparadas por Oliver Pardo.

## Uso de inteligencia artificial

La nota al final del informe identifica el uso de IA generativa en la búsqueda y síntesis de antecedentes, la redacción y la preparación de LaTeX. La nota no atribuye a la IA la responsabilidad por los argumentos o las propuestas.
