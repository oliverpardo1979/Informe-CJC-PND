# Informe del CJC sobre propuestas para el PND

Proyecto LaTeX para editar en Overleaf. La versión extensa conserva seis propuestas visibles. La propuesta salarial reúne el salario de entrada juvenil y la regla de ajuste anual, conservando sus instrumentos, referentes y articulados separados. La revisión del 15 de noviembre fusionó las anteriores 1 y 3 y agregó la regla subsidiaria del salario mínimo. La del 16 de noviembre organiza cada propuesta en cuatro subsecciones: Antecedentes, Descripción de la propuesta, Justificación y Articulado. La descripción incluye ejecución, financiación y evaluación. La propuesta de eficiencia del Estado se conserva comentada, incluido su articulado. La primera propuesta amplía la asistencia técnica de Fábricas de Productividad y Sostenibilidad y la complementa con convocatorias para desarrollar soluciones de IA a problemas comunes de las empresas.

Orden actual: (1) adopción y desarrollo tecnológico, (2) alianzas de I+D+i y doctorados industriales, (3) capital y competencia financiera, (4) centros de formación de participación mixta, (5) salario mínimo de entrada juvenil y regla de ajuste anual y (6) competencia en contratación pública. El segundo componente salarial propone IPC de noviembre a noviembre definitivo, sin ajuste en enero, mediante ley ordinaria y con los reparos constitucionales explicados en el cuerpo.

La [comparación con las Bases del 13 de noviembre](material_complementario/Comparacion_Bases_PND_2026-11-13.md) distingue los compromisos existentes, las decisiones que añade el CJC y su vía de ejecución. La convergencia temática no excluye una propuesta si aporta una decisión sustantiva de financiación, gestión o regulación. Esta versión conserva seis, sin una selección prefijada de cinco ni un orden de impactos estimados.

Los artículos 1 y 2 desarrollan la asistencia técnica y las convocatorias para problemas comunes de las empresas. El artículo 3 corresponde a las alianzas de I+D+i y los doctorados. El artículo 4 desarrolla la financiación. Los artículos 5 y 6 establecen el programa de centros de formación de participación mixta y su evaluación. El artículo 7 prevé preparación y evaluación del primer empleo juvenil y el 8 desarrolla competencia en las compras. La propuesta de centros mixtos incluye, dentro del mismo documento, nueve artículos de una ley ordinaria complementaria. Modifican la Ley 30 (artículo 23, nuevo artículo 23A y concordancias de los artículos 57, 58 y 61), añaden una línea de financiación al artículo 32 de la Ley 119 y modifican el numeral 2 del artículo 243 del Estatuto Tributario mediante una distribución anual costeada y un nuevo parágrafo 6. Mantienen las rutas SENA y Nación–MinTrabajo y ajustan la garantía presupuestal conjunta para evitar una reposición duplicada. Las reformas de SAS, piso salarial juvenil y regla anual del mínimo se redactan en proyectos de ley ordinaria separados, con numeración propia y sus condiciones jurídicas. La implementación utiliza las estrategias y sistemas contemplados en las Bases. No se presume que su inclusión en ellas elimine los requisitos de unidad de materia, competencia o impacto fiscal.

Las propuestas originales 3, 5, 6, 7, 8, 9 y 10, con todo su texto, enlaces y articulado, están comentadas línea por línea y no aparecen en el PDF. Buscar `INICIO PROPUESTA SILENCIADA` en `Paper/sections/Propuestas.tex`. Sus entradas del resumen y la introducción también están comentadas. Para recuperarlas, quitar el primer `% ` dentro del bloque correspondiente y revisar la numeración de artículos. Se conservan comentadas tanto la versión anterior de la propuesta 10 como su reformulación de eficiencia del Estado. Las etiquetas internas conservan sus identificadores originales. Las propuestas activas usan `prop:1`, `prop:2`, `prop:11`, `prop:12`, `prop:13` y `prop:14`. La etiqueta `prop:4` es un alias de `prop:1` en la propuesta tecnológica. La etiqueta `prop:15` es un alias de `prop:13` en la propuesta salarial fusionada. El PDF numera las propuestas como secciones 1 a 6. Cada una contiene cuatro subsecciones numeradas, de Antecedentes a Articulado.

Una breve nota reemplaza la introducción. Los antecedentes de la primera propuesta conectan el informe con Pardo y Orozco (2026), *Inteligencia Artificial y Empleo en Colombia*, y conservan el cuadro de las cuatro actividades con mayor proporción de ocupados en ocupaciones de alto potencial relativo de automatización, excluyendo organizaciones extraterritoriales. La fuente, el denominador y los límites del indicador acompañan el cuadro. El informe sigue siendo la versión extensa. La versión para la facultad requiere seleccionar como máximo cinco propuestas y sintetizarlas en no más de tres páginas.

La revisión de lectura del 27 de octubre adapta las explicaciones para un director o subdirector del DNP con experiencia en política pública, sin conocimientos especializados de IA. Presenta los términos antes de utilizarlos y distingue los instrumentos que podrían confundirse. La revisión del 16 de noviembre también ajusta el articulado para corresponder a los mecanismos expuestos en cada propuesta.

## Edición en Overleaf

1. Sincronizar este repositorio desde la integración GitHub del proyecto de Overleaf o importar su ZIP como un proyecto nuevo.
2. Seleccionar `main.tex` como documento principal y **pdfLaTeX** como compilador.
3. Compilar. No se requiere BibTeX, archivos externos ni ejecución de scripts. Las citas de programas e informes enlazan a referencias completas en `Paper/sections/Referencias.tex`, que conserva los enlaces originales a las fuentes. Las normas mantienen sus enlaces directos y el informe de IA se identifica en el material complementario.

## Archivos

- `main.tex` reúne las partes del informe.
- `Paper/configuracion.tex` contiene formato, título, autoría, fecha y etiqueta de edición.
- `Paper/sections/Portada.tex` contiene la portada.
- `Paper/sections/ResumenEjecutivo.tex` presenta las seis propuestas visibles en negrilla, con una breve explicación por propuesta.
- `Paper/sections/Introduccion.tex` contiene la breve nota inicial. La introducción anterior se conserva comentada.
- `Paper/sections/Propuestas.tex` contiene las seis propuestas como secciones, cada una con cuatro subsecciones. Conserva los artículos íntegros, las condiciones comunes de ejecución sin numerar y los textos silenciados al final. Los recortes por repetición también se conservan comentados.
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
- Títulos de propuestas, en `Paper/sections/Propuestas.tex`, comandos `\section{...}`.
- Las cuatro subsecciones se editan en los comandos `\subsection{...}` de ese mismo archivo. Las divisiones internas breves usan `\textbf{...}`. Los artículos completos permanecen en recuadros dentro de cada propuesta. Buscar «Articulado propuesto» o «Artículo 1», «Artículo 2» y así sucesivamente.
- Los artículos de la reforma pensional se conservan completos, comentados dentro de la propuesta original 8.

## Desarrollo jurídico de la versión original de diez propuestas

La versión original incorporó, con corte de consulta del 26 de octubre de 2026, la revisión de los PND de 2015, 2019 y 2023, las normas sectoriales colombianas y los referentes legales de Reino Unido, Singapur, Canadá, Estados Unidos y la Unión Europea. Los párrafos siguientes describen esa versión y su numeración original. La selección visible actual y la forma de recuperar los textos comentados se explican al comienzo de este archivo.

Los artículos 1 a 7 desarrollan las primeras seis propuestas y los artículos 16 y 17 corresponden a la novena y la décima. Los artículos 8 a 15 corresponden a la octava propuesta y modifican directamente las disposiciones legales, con reglas de transición. Se eliminó el artículo que se limitaba a ordenar la presentación posterior de otro proyecto de ley. Los recuadros contienen únicamente el texto normativo. La justificación, los referentes y las condiciones para radicar están fuera de ellos. La numeración debe ajustarse a la que adopte el proyecto de ley del PND.

La inclusión de los artículos en la ley del PND requiere conexión directa e inmediata con programas específicos de las Bases y del plan de inversiones. El bloque pensional exige una justificación especial por su carácter permanente. Si no se demuestra esa conexión, deberá tramitarse por la vía legislativa ordinaria. También requiere actualizar concordancias al radicar, revisar derechos y evaluar efectos fiscales y actuariales. El artículo 13 fija un mínimo inicial de capital de $2.000 millones, con actualización por IPC después de su aplicación. El monto es una propuesta del CJC y requiere un estudio de suficiencia y de los requisitos que seguirían aplicando por las demás actividades autorizadas. La nota de uso de IA permanece al final del informe.

## Formato de referencia

Se reutilizaron el logo, la serie, la portada, el recuadro del resumen y los encabezados de los proyectos [Informe Actividades](https://github.com/oliverpardo1979/Informe_Actividades), [Informes departamentales](https://github.com/oliverpardo1979/Informes-departamentales), [Informe Tamaño](https://github.com/oliverpardo1979/Informe_Tamano) e [Informe Educación](https://github.com/oliverpardo1979/Informe_Educacion). El cuerpo conserva el texto de las diez propuestas extensas preparadas por Oliver Pardo.

## Verificación de referentes internacionales

La [verificación de referentes internacionales](material_complementario/Verificacion_referentes_internacionales.md), realizada el 27 de octubre de 2026, detalla qué componente de cada propuesta está respaldado por las fuentes primarias y qué elementos corresponden a la adaptación del CJC.

## Uso de inteligencia artificial

La nota al final del informe identifica el uso de IA generativa en la búsqueda de antecedentes y la redacción. La autoría asume la responsabilidad por el contenido.

## Jerarquía de secciones

Después del resumen ejecutivo aparece una breve nota de contexto. Las seis propuestas son secciones numeradas del 1 al 6. Cada una contiene cuatro subsecciones numeradas: Antecedentes, Descripción de la propuesta, Justificación y Articulado. Las divisiones internas se presentan en negrilla, sin otro nivel de secciones. La descripción incluye responsables, financiación y evaluación. La vía legislativa se explica antes de los artículos, distinguiendo el PND de los proyectos de ley complementarios. El cierre, las referencias y el material complementario conservan títulos sin numerar. La nota de uso de IA permanece al final.
