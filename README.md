# Informe del CJC sobre propuestas para el PND

Proyecto LaTeX para editar en Overleaf. El cuerpo desarrolla las diez propuestas extensas preparadas el 23 de octubre de 2026 sobre productividad, inteligencia artificial, investigación y financiación empresarial. Cada propuesta incluye su desarrollo jurídico, los referentes legales internacionales y el articulado completo correspondiente. La revisión de lectura precisa referentes, secuencia y conexiones para equipos técnicos del DNP y del Gobierno y conserva las diez medidas, sus argumentos, ejemplos y enlaces. El articulado contiene 17 textos normativos con numeración provisional, presentados en recuadros dentro de las propuestas. La portada y el resumen ejecutivo utilizan el formato del CJC. La selección de cinco para el documento de máximo tres páginas de la facultad se realiza por separado.

## Edición en Overleaf

1. Sincronizar este repositorio desde la integración GitHub del proyecto de Overleaf o importar su ZIP como un proyecto nuevo.
2. Seleccionar `main.tex` como documento principal y **pdfLaTeX** como compilador.
3. Compilar. No se requiere BibTeX, archivos externos ni ejecución de scripts. Las referencias se conservan como enlaces dentro del texto original.

## Archivos

- `main.tex` reúne las partes del informe.
- `Paper/configuracion.tex` contiene formato, título, autoría, fecha y etiqueta de edición.
- `Paper/sections/Portada.tex` contiene la portada.
- `Paper/sections/ResumenEjecutivo.tex` presenta las diez propuestas en negrilla, con una frase por propuesta.
- `Paper/sections/Introduccion.tex` contiene la sección 1, «Introducción», con la motivación y la justificación del informe y un párrafo breve por propuesta.
- `Paper/sections/Propuestas.tex` contiene la sección 2, «Propuestas», con las diez propuestas extensas como subsecciones 2.1 a 2.10 y sus apartados como subsubsecciones sin numeración. Dentro de cada una están el texto anterior, el fundamento jurídico y los artículos completos. También incluye el cierre sobre su articulación y las condiciones generales de instrumentación.
- `Paper/sections/MaterialComplementario.tex` contiene la referencia y el enlace a la matriz de Jorge Orozco.
- `Paper/sections/NotaIA.tex` contiene la nota de uso de IA, al final del informe.
- `Paper/figures/logo_cjc_palatino_horizontal.png` es el logo utilizado por los informes anteriores.

La etiqueta «Propuestas para el PND» puede reemplazarse por un número de informe cuando se asigne. La fecha es fija y se modifica en `Paper/configuracion.tex`.

## Material complementario

[Matriz de políticas e iniciativas de inteligencia artificial de Jorge Orozco](material_complementario/Matriz_politicas_IA_Jorge_Orozco_2026-10-21.xlsm). Archivo Excel en formato `.xlsm`, versión consultada el 21 de octubre de 2026, con todas las filas visibles. Contiene las hojas «Matriz evidencia», «Resumen» y «Criterios», y permite consultar experiencias internacionales, instrumentos y fuentes oficiales. El archivo se conserva sin modificar su contenido.

La matriz también está enlazada desde el informe, después del cuerpo de las propuestas y antes de la nota final de uso de IA.

## Dónde editar títulos, subtítulos y artículos

- Resumen ejecutivo e introducción, en `Paper/sections/ResumenEjecutivo.tex` y `Paper/sections/Introduccion.tex`, respectivamente.
- Título y subtítulo de portada, en `Paper/configuracion.tex`, comandos `reporttitle` y `reportsubtitle`.
- Títulos de propuestas, en `Paper/sections/Propuestas.tex`, comandos `\subsection{...}`.
- Subtítulos, en los comandos `\subsubsection{...}` de ese mismo archivo. Los artículos completos permanecen en recuadros dentro de cada propuesta. Buscar «Texto propuesto para la ley del Plan Nacional de Desarrollo» o «Artículo 1», «Artículo 2» y así sucesivamente.
- Los artículos 8 a 15 modifican directamente el régimen del ahorro pensional y están completos dentro de la propuesta 8.

## Desarrollo jurídico dentro de las propuestas

El informe incorpora, con corte de consulta del 26 de octubre de 2026, la revisión de los PND de 2015, 2019 y 2023, las normas sectoriales colombianas y los referentes legales de Reino Unido, Singapur, Canadá, Estados Unidos y la Unión Europea. Ese contenido se distribuye dentro de las diez propuestas y se compila con `main.tex`. No requiere seleccionar otro documento ni consultar un anexo para leer el articulado.

Los artículos 1 a 7 desarrollan las primeras siete propuestas y los artículos 16 y 17 corresponden a la novena y la décima. Los artículos 8 a 15 corresponden a la octava propuesta y modifican directamente las disposiciones legales, con reglas de transición. Se eliminó el artículo que se limitaba a ordenar la presentación posterior de otro proyecto de ley. Los recuadros contienen únicamente el texto normativo. La justificación, los referentes y las condiciones para radicar están fuera de ellos. La numeración debe ajustarse a la que adopte el proyecto de ley del PND.

La inclusión de los artículos en la ley del PND requiere conexión directa e inmediata con programas específicos de las Bases y del plan de inversiones. El bloque pensional exige una justificación especial por su carácter permanente. Si no se demuestra esa conexión, deberá tramitarse por la vía legislativa ordinaria. También requiere actualizar concordancias al radicar, revisar derechos y evaluar efectos fiscales y actuariales. El artículo 13 sustituye el piso legal por una regla de determinación técnica del capital, sin inventar un monto que no ha sido estudiado. La nota de uso de IA permanece al final del informe.

## Formato de referencia

Se reutilizaron el logo, la serie, la portada, el recuadro del resumen y los encabezados de los proyectos [Informe Actividades](https://github.com/oliverpardo1979/Informe_Actividades), [Informes departamentales](https://github.com/oliverpardo1979/Informes-departamentales), [Informe Tamaño](https://github.com/oliverpardo1979/Informe_Tamano) e [Informe Educación](https://github.com/oliverpardo1979/Informe_Educacion). El cuerpo conserva el texto de las diez propuestas extensas preparadas por Oliver Pardo.

## Verificación de referentes internacionales

La [verificación de referentes internacionales](material_complementario/Verificacion_referentes_internacionales.md), realizada el 27 de octubre de 2026, detalla qué componente de cada propuesta está respaldado por las fuentes primarias y qué elementos corresponden a la adaptación del CJC.

## Uso de inteligencia artificial

La nota al final del informe identifica el uso de IA generativa en la búsqueda y síntesis de antecedentes, la redacción y la preparación de LaTeX. La nota no atribuye a la IA la responsabilidad por los argumentos o las propuestas.

## Jerarquía de secciones

La introducción es la sección 1 y «Propuestas» es la sección 2. Cada propuesta es una subsección numerada de 2.1 a 2.10. Sus apartados son subsubsecciones sin numeración. El cierre es la sección 3. El resumen ejecutivo y el material complementario conservan títulos sin numerar. Las referencias internas a las propuestas utilizan las etiquetas `prop:1` a `prop:10`. La numeración de los 17 artículos propuestos es independiente y se conserva.
