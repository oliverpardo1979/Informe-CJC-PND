# Informe del CJC sobre propuestas para el PND

Proyecto LaTeX para editar en Overleaf. La versión extensa conserva ocho propuestas visibles. La revisión del 15 de noviembre fusionó las anteriores 1 y 3 y agregó la regla subsidiaria del salario mínimo. La del 16 de noviembre reformula las ocho como aportes a la ejecución de las Bases y reformas adicionales, con tres apartados iniciales: qué dicen las Bases, qué añade el CJC y cómo se ejecutaría. Las demás propuestas y los textos silenciados se conservan.

Orden actual: (1) adopción y desarrollo tecnológico, (2) alianzas de I+D+i y doctorados industriales, (3) eficiencia del Estado, (4) capital y competencia financiera, (5) gestión del SENA, (6) primer empleo formal juvenil, (7) competencia en contratación pública y (8) regla de ajuste del mínimo sin acuerdo tripartito. La última propone IPC de noviembre a noviembre definitivo, sin ajuste en enero, mediante ley ordinaria y con los reparos constitucionales explicados en el cuerpo.

La [comparación con las Bases del 13 de noviembre](material_complementario/Comparacion_Bases_PND_2026-11-13.md) distingue los compromisos existentes, las decisiones que añade el CJC y su vía de ejecución. La convergencia temática no excluye una propuesta si aporta una decisión sustantiva de financiación, gestión o regulación. Esta versión conserva las ocho, sin una selección prefijada de cinco ni un orden de impactos estimados.

Los artículos 1 y 2 desarrollan las modalidades tecnológicas. El artículo 3 corresponde a las alianzas de I+D+i y los doctorados. Los artículos 4 y 5 corresponden a eficiencia estatal y financiación. Los artículos 6 y 7 desarrollan el SENA. El artículo 8 prevé preparación y evaluación del primer empleo juvenil y el 9 desarrolla competencia en las compras. Las reformas de SAS, piso salarial juvenil y regla anual del mínimo se redactan en proyectos de ley ordinaria separados, con numeración propia y sus condiciones jurídicas. La implementación utiliza las estrategias y sistemas contemplados en las Bases. No se presume que su inclusión en ellas elimine los requisitos de unidad de materia, competencia o impacto fiscal.

Las propuestas originales 3, 5, 6, 7, 8 y 9, con todo su texto, enlaces y articulado, están comentadas línea por línea y no aparecen en el PDF. Buscar `INICIO PROPUESTA SILENCIADA` en `Paper/sections/Propuestas.tex`. Sus entradas del resumen y la introducción también están comentadas. Para recuperarlas, quitar el primer `% ` dentro del bloque correspondiente y revisar la numeración de artículos. La versión anterior de la propuesta 10 se conserva comentada junto a la nueva. Las etiquetas internas `prop:1`, `prop:2`, `prop:4` y `prop:10` conservan sus identificadores originales. Las nuevas propuestas usan `prop:11`, `prop:12`, `prop:13`, `prop:14` y `prop:15`. La etiqueta `prop:4` es ahora un alias de `prop:1`, dentro de la propuesta tecnológica fusionada. El PDF numera automáticamente las subsecciones de 2.1 a 2.8.

La introducción conecta el informe con Pardo y Orozco (2026), *Inteligencia Artificial y Empleo en Colombia*. Incluye las cuatro actividades con mayor proporción de ocupados en ocupaciones de alto potencial relativo de automatización, excluyendo organizaciones extraterritoriales. La fuente, el denominador y los límites del indicador acompañan el cuadro. El informe sigue siendo la versión extensa. La versión para la facultad requiere seleccionar como máximo cinco propuestas y sintetizarlas en no más de tres páginas.

La revisión de lectura del 27 de octubre adapta las explicaciones para un director o subdirector del DNP con experiencia en política pública, sin conocimientos especializados de IA. Presenta los términos antes de utilizarlos y distingue los instrumentos que podrían confundirse. La revisión del 16 de noviembre también ajusta el articulado para corresponder a los mecanismos expuestos en cada propuesta.

## Edición en Overleaf

1. Sincronizar este repositorio desde la integración GitHub del proyecto de Overleaf o importar su ZIP como un proyecto nuevo.
2. Seleccionar `main.tex` como documento principal y **pdfLaTeX** como compilador.
3. Compilar. No se requiere BibTeX, archivos externos ni ejecución de scripts. Las citas de programas e informes enlazan a referencias completas en `Paper/sections/Referencias.tex`, que conserva los enlaces originales a las fuentes. Las normas mantienen sus enlaces directos y el informe de IA se identifica en el material complementario.

## Archivos

- `main.tex` reúne las partes del informe.
- `Paper/configuracion.tex` contiene formato, título, autoría, fecha y etiqueta de edición.
- `Paper/sections/Portada.tex` contiene la portada.
- `Paper/sections/ResumenEjecutivo.tex` presenta las ocho propuestas visibles en negrilla, con una breve explicación por propuesta.
- `Paper/sections/Introduccion.tex` contiene la sección 1, «Introducción», con la motivación y la justificación del informe y un párrafo breve por propuesta.
- `Paper/sections/Propuestas.tex` contiene la sección 2, «Propuestas», con ocho subsecciones visibles, los apartados sin numeración, el articulado y los textos comentados de las propuestas silenciadas. El cierre reúne las condiciones de ejecución.
- `Paper/sections/Referencias.tex` contiene las fuentes no normativas citadas, con autor, fecha, título y enlace.
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
- Subtítulos, en los comandos `\subsubsection{...}` de ese mismo archivo. Los artículos completos permanecen en recuadros dentro de cada propuesta. Buscar «Articulado propuesto» o «Artículo 1», «Artículo 2» y así sucesivamente.
- Los artículos de la reforma pensional se conservan completos, comentados dentro de la propuesta original 8.

## Desarrollo jurídico de la versión original de diez propuestas

La versión original incorporó, con corte de consulta del 26 de octubre de 2026, la revisión de los PND de 2015, 2019 y 2023, las normas sectoriales colombianas y los referentes legales de Reino Unido, Singapur, Canadá, Estados Unidos y la Unión Europea. Los párrafos siguientes describen esa versión y su numeración original. La selección visible actual y la forma de recuperar los textos comentados se explican al comienzo de este archivo.

Los artículos 1 a 7 desarrollan las primeras siete propuestas y los artículos 16 y 17 corresponden a la novena y la décima. Los artículos 8 a 15 corresponden a la octava propuesta y modifican directamente las disposiciones legales, con reglas de transición. Se eliminó el artículo que se limitaba a ordenar la presentación posterior de otro proyecto de ley. Los recuadros contienen únicamente el texto normativo. La justificación, los referentes y las condiciones para radicar están fuera de ellos. La numeración debe ajustarse a la que adopte el proyecto de ley del PND.

La inclusión de los artículos en la ley del PND requiere conexión directa e inmediata con programas específicos de las Bases y del plan de inversiones. El bloque pensional exige una justificación especial por su carácter permanente. Si no se demuestra esa conexión, deberá tramitarse por la vía legislativa ordinaria. También requiere actualizar concordancias al radicar, revisar derechos y evaluar efectos fiscales y actuariales. El artículo 13 fija un mínimo inicial de capital de $2.000 millones, con actualización por IPC después de su aplicación. El monto es una propuesta del CJC y requiere un estudio de suficiencia y de los requisitos que seguirían aplicando por las demás actividades autorizadas. La nota de uso de IA permanece al final del informe.

## Formato de referencia

Se reutilizaron el logo, la serie, la portada, el recuadro del resumen y los encabezados de los proyectos [Informe Actividades](https://github.com/oliverpardo1979/Informe_Actividades), [Informes departamentales](https://github.com/oliverpardo1979/Informes-departamentales), [Informe Tamaño](https://github.com/oliverpardo1979/Informe_Tamano) e [Informe Educación](https://github.com/oliverpardo1979/Informe_Educacion). El cuerpo conserva el texto de las diez propuestas extensas preparadas por Oliver Pardo.

## Verificación de referentes internacionales

La [verificación de referentes internacionales](material_complementario/Verificacion_referentes_internacionales.md), realizada el 27 de octubre de 2026, detalla qué componente de cada propuesta está respaldado por las fuentes primarias y qué elementos corresponden a la adaptación del CJC.

## Uso de inteligencia artificial

La nota al final del informe identifica el uso de IA generativa en la búsqueda de antecedentes y la redacción. La autoría asume la responsabilidad por el contenido.

## Jerarquía de secciones

La introducción es la sección 1 y «Propuestas» es la sección 2. Las ocho propuestas visibles son subsecciones de 2.1 a 2.8. Sus apartados son subsubsecciones sin numeración. Cada propuesta comienza con «Qué dicen las Bases», «Qué añade el CJC» y «Cómo se ejecutaría». Después se desarrollan la justificación, los antecedentes y la evaluación, el fundamento jurídico, el complemento a las Bases y los artículos correspondientes. El cierre es la sección 3. El resumen ejecutivo y el material complementario conservan títulos sin numerar. La nota de uso de IA permanece al final.
