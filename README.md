# Informe del CJC sobre propuestas para el PND

Proyecto LaTeX para editar en Overleaf. La versión extensa visible contiene ocho propuestas, correspondientes a las originales 1, 2, 4 y 10 y cuatro propuestas nuevas sobre financiación empresarial, formación del SENA, primer empleo formal juvenil y competencia en la contratación pública. La primera apoya la adopción de herramientas disponibles. La segunda sostiene alianzas de investigación con financiación empresarial e incorpora doctorados industriales con empleo remunerado y dirección universitaria. La tercera cofinancia desarrollo y validación de soluciones replicables. La cuarta propone eliminar trámites y funciones innecesarios, reorganizar dependencias, plantas y contratación, y medir el ahorro administrativo neto. La quinta combina apertura del mercado de valores a las SAS, acceso acreditado a datos financieros y requisitos proporcionales a los riesgos. La sexta amplía la autonomía de centros del SENA, vincula financiación a resultados y compara provisión pública con operación de programas por terceros. La séptima propone un piso del 70% del mínimo general durante los primeros seis meses del primer empleo formal de quienes lo inicien entre los 18 y los 24 años, y el mínimo general desde el séptimo mes. La octava reduce barreras de experiencia, financieras y documentales en la contratación pública, ajusta capacidad por lote y evalúa ahorro con calidad y cumplimiento.

Los artículos 1 al 5 desarrollan las primeras cinco propuestas. El artículo 2 incluye los doctorados industriales. Los artículos 6 y 7 desarrollan la propuesta del SENA y conservan la dirección administrativa pública durante el piloto. Transferir gobierno o patrimonio de centros requeriría una reforma institucional específica. La reforma de las SAS se formula como artículo de una ley ordinaria complementaria, dentro de la quinta propuesta, debido al antecedente de la Sentencia C-038/25. El artículo 8 del PND prevé preparación y evaluación del primer empleo juvenil. La séptima propuesta incorpora además dos artículos de una ley ordinaria complementaria para crear el piso salarial, conservar las bases mínimas de cotización y establecer verificación y protección contra sustituciones. Los parámetros salariales requieren justificación constitucional de suficiencia y proporcionalidad. El artículo 9 ejecuta y evalúa el programa de competencia en las compras del Plan. Su complemento reglamentario modifica indicadores y alternativas de acreditación del Decreto 1082 y actualiza los documentos tipo. La propuesta distingue estos cambios de obligaciones existentes y reconoce la transición del Decreto 997 de 2026.

Las propuestas originales 3, 5, 6, 7, 8 y 9, con todo su texto, enlaces y articulado, están comentadas línea por línea y no aparecen en el PDF. Buscar `INICIO PROPUESTA SILENCIADA` en `Paper/sections/Propuestas.tex`. Sus entradas del resumen y la introducción también están comentadas. Para recuperarlas, quitar el primer `% ` dentro del bloque correspondiente y revisar la numeración de artículos. La versión anterior de la propuesta 10 se conserva comentada junto a la nueva. Las etiquetas internas `prop:1`, `prop:2`, `prop:4` y `prop:10` conservan sus identificadores originales. Las nuevas propuestas usan `prop:11`, `prop:12`, `prop:13` y `prop:14`. El PDF numera automáticamente las subsecciones de 2.1 a 2.8.

La introducción conecta el informe con Pardo y Orozco (2026), *Inteligencia Artificial y Empleo en Colombia*. Incluye las cuatro actividades con mayor proporción de ocupados en ocupaciones de alto potencial relativo de automatización, excluyendo organizaciones extraterritoriales. La fuente, el denominador y los límites del indicador acompañan el cuadro. El informe sigue siendo la versión extensa. La versión para la facultad requiere seleccionar como máximo cinco propuestas y sintetizarlas en no más de tres páginas.

La revisión de lectura del 27 de octubre adapta las explicaciones para un director o subdirector del DNP con experiencia en política pública, sin conocimientos especializados de IA. Presenta los términos antes de utilizarlos y distingue los instrumentos que podrían confundirse. Los textos del articulado se conservan sin cambios.

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

La introducción es la sección 1 y «Propuestas» es la sección 2. Las ocho propuestas visibles son subsecciones de 2.1 a 2.8. Sus apartados son subsubsecciones sin numeración. Cada propuesta comienza con «Qué proponemos», que reúne el instrumento y la explicación de la medida. El cierre es la sección 3. El resumen ejecutivo y el material complementario conservan títulos sin numerar. La nota de uso de IA permanece al final.
