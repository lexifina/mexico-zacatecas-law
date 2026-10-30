# Zacatecas: law history in git

The law of the State of Zacatecas (Estado Libre y Soberano de Zacatecas, Mexico) as a git history: one file per article, one commit per publication that changed it, dated the day it took effect, with the decree as the commit's author. `git blame` names the decree behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `mx-zac/`. Mexico's federal law is in [lexifina/mexico-law](https://github.com/lexifina/mexico-law).

The text is in Spanish, exactly as the source prints it.

## What this repository holds

99 ordenamientos with 628 versions so far: the constitution first, then the codes and laws in force, added in parts. Regulations, decrees and repealed laws are not included yet.

| Folder | Ordenamiento | Versions | History |
| --- | --- | ---: | --- |
| `constitucion-politica/` | CONSTITUCION POLITICA DEL ESTADO LIBRE Y SOBERANO DE ZACATECAS | 71 | as first published, then each reform: 16 August 1998 to 17 September 2026 |
| `codigo-civil/` | CODIGO CIVIL DEL ESTADO DE ZACATECAS | 24 | as first published, then each reform: 23 July 1986 to 19 July 2026 |
| `codigo-de-procedimientos-civiles/` | CODIGO DE PROCEDIMIENTOS CIVILES PARA EL ESTADO DE ZACATECAS | 18 | as first published, then each reform: 1 May 1966 to 22 February 2018 |
| `codigo-familiar/` | CODIGO FAMILIAR DEL ESTADO DE ZACATECAS | 38 | as first published, then each reform: 10 May 1986 to 23 August 2026 |
| `codigo-fiscal/` | CODIGO FISCAL DEL ESTADO DE ZACATECAS Y SUS MUNICIPIOS | 11 | as first published, then each reform: 3 January 2017 to 3 January 2026 |
| `codigo-municipal-reglamentario-de-fresnillo-zacatecas/` | CODIGO MUNICIPAL REGLAMENTARIO DE FRESNILLO, ZACATECAS | 4 | as first published, then each reform: 12 September 2004 to 20 September 2016 |
| `codigo-penal/` | CODIGO PENAL PARA EL ESTADO DE ZACATECAS | 68 | as first published, then each reform: 20 May 1986 to 17 September 2026 |
| `codigo-territorial-y-urbano/` | CODIGO TERRITORIAL Y URBANO PARA EL ESTADO DE ZACATECAS Y SUS MUNICIPIOS | 5 | as first published, then each reform: 1 September 2019 to 5 October 2025 |
| `ley-antiquebranto-para-una-gestion-responsable-y-sostenible/` | LEY ANTIQUEBRANTO PARA UNA GESTION RESPONSABLE Y SOSTENIBLE DE LAS FINANZAS PUBLICAS DEL ESTADO DE ZACATECAS | 1 | as first published: 13 August 2024 |
| `ley-de-acceso-de-las-mujeres-a-una-vida-libre-de-violencia/` | LEY DE ACCESO DE LAS MUJERES A UNA VIDA LIBRE DE VIOLENCIA PARA EL ESTADO DE ZACATECAS | 14 | as first published, then each reform: 18 January 2009 to 19 July 2026 |
| `ley-de-adquisiciones-arrendamientos-y-servicios/` | LEY DE ADQUISICIONES, ARRENDAMIENTOS Y SERVICIOS DEL ESTADO DE ZACATECAS Y SUS MUNICIPIOS | 1 | as first published: 4 July 2019 |
| `ley-de-arancel/` | LEY DE ARANCEL | 3 | as first published, then each reform: 2 March 1989 to 16 February 1997 |
| `ley-de-archivos/` | LEY DE ARCHIVOS PARA EL ESTADO DE ZACATECAS Y SUS MUNICIPIOS | 2 | as first published, then each reform: 4 July 2021 to 1 February 2024 |
| `ley-de-asistencia-social/` | LEY DE ASISTENCIA SOCIAL DEL ESTADO DE ZACATECAS | 9 | as first published, then each reform: 5 April 2007 to 1 October 2023 |
| `ley-de-asociaciones-publico-privadas/` | LEY DE ASOCIACIONES PUBLICO PRIVADAS DEL ESTADO DE ZACATECAS | 1 | as first published: 7 January 2018 |
| `ley-de-atencion-a-victimas/` | LEY DE ATENCION A VICTIMAS DEL ESTADO DE ZACATECAS | 1 | as first published: 14 December 2014 |
| `ley-de-austeridad-disciplina-y-responsabilidad-financiera/` | LEY DE AUSTERIDAD, DISCIPLINA Y RESPONSABILIDAD FINANCIERA DEL ESTADO DE ZACATECAS Y SUS MUNICIPIOS | 3 | as first published, then each reform: 30 December 2021 to 13 August 2024 |
| `ley-de-becas-estimulos-educativos-y-apoyos-financieros/` | LEY DE BECAS, ESTIMULOS EDUCATIVOS Y APOYOS FINANCIEROS DEL ESTADO DE ZACATECAS | 5 | as first published, then each reform: 4 February 2010 to 17 September 2017 |
| `ley-de-bibliotecas-publicas/` | LEY DE BIBLIOTECAS PUBLICAS PARA EL ESTADO DE ZACATECAS | 2 | as first published, then each reform: 12 March 2006 to 26 February 2015 |
| `ley-de-bienes/` | LEY DE BIENES DEL ESTADO DE ZACATECAS Y SUS MUNICIPIOS | 1 | as first published: 1 January 2020 |
| `ley-de-bienestar-y-proteccion-de-los-animales-en-el-estado-d/` | LEY DE BIENESTAR Y PROTECCION DE LOS ANIMALES EN EL ESTADO DE ZACATECAS | 4 | as first published, then each reform: 25 August 2016 to 26 April 2026 |
| `ley-de-cajas-populares/` | LEY DE CAJAS POPULARES DEL ESTADO DE ZACATECAS | 1 | as first published: 10 September 1987 |
| `ley-de-cambio-climatico/` | LEY DE CAMBIO CLIMATICO PARA EL ESTADO Y MUNICIPIOS DE ZACATECAS | 4 | as first published, then each reform: 24 September 2015 to 30 October 2023 |
| `ley-de-catastro/` | LEY DE CATASTRO DEL ESTADO DE ZACATECAS | 3 | as first published, then each reform: 7 January 1988 to 4 December 2014 |
| `ley-de-ciencia-tecnologia-e-innovacion/` | LEY DE CIENCIA, TECNOLOGIA E INNOVACION DEL ESTADO DE ZACATECAS - ANTES LEY DE CIENCIA Y TECNOLOGIA DEL ESTADO DE ZACATECAS - | 7 | as first published, then each reform: 14 May 2006 to 8 July 2021 |
| `ley-de-construccion/` | LEY DE CONSTRUCCION PARA EL ESTADO Y MUNICIPIOS DE ZACATECAS | 2 | as first published, then each reform: 2 June 2016 to 1 October 2023 |
| `ley-de-coordinacion-y-colaboracion-financiera/` | LEY DE COORDINACION Y COLABORACION FINANCIERA PARA EL ESTADO DE ZACATECAS Y SUS MUNICIPIOS | 11 | as first published, then each reform: 3 January 2017 to 3 January 2026 |
| `ley-de-cultura/` | LEY DE CULTURA DEL ESTADO DE ZACATECAS Y SUS MUNICIPIOS | 3 | as first published, then each reform: 9 September 2021 to 5 October 2025 |
| `ley-de-cultura-fisica-y-deporte/` | LEY DE CULTURA FISICA Y DEPORTE DEL ESTADO DE ZACATECAS | 6 | as first published, then each reform: 18 June 2015 to 12 August 2021 |
| `ley-de-desarrollo-forestal-sustentable/` | LEY DE DESARROLLO FORESTAL SUSTENTABLE DEL ESTADO DE ZACATECAS | 4 | as first published, then each reform: 31 October 2006 to 11 January 2018 |
| `ley-de-desarrollo-metropolitano/` | LEY DE DESARROLLO METROPOLITANO DEL ESTADO DE ZACATECAS | 3 | as first published, then each reform: 5 December 2010 to 22 February 2018 |
| `ley-de-desarrollo-social/` | LEY DE DESARROLLO SOCIAL PARA EL ESTADO Y MUNICIPIOS DE ZACATECAS | 12 | as first published, then each reform: 18 January 2009 to 22 January 2026 |
| `ley-de-desarrollo-proteccion-y-difusion-de-las-actividades-a/` | LEY DE DESARROLLO, PROTECCION Y DIFUSION DE LAS ACTIVIDADES ARTESANALES DEL ESTADO DE ZACATECAS Y SUS MUNICIPIOS | 1 | as first published: 30 August 2020 |
| `ley-de-educacion/` | LEY DE EDUCACION DEL ESTADO DE ZACATECAS | 13 | as first published, then each reform: 18 June 2020 to 17 September 2026 |
| `ley-de-entrega-recepcion/` | LEY DE ENTREGA-RECEPCION DEL ESTADO DE ZACATECAS | 4 | as first published, then each reform: 17 June 2018 to 26 April 2026 |
| `ley-de-estacionamientos-publicos/` | LEY DE ESTACIONAMIENTOS PUBLICOS PARA EL ESTADO DE ZACATECAS | 1 | as first published: 27 December 2015 |
| `ley-de-estimulos-y-recompensas-a-los-funcionarios-y-empleado/` | LEY DE ESTIMULOS Y RECOMPENSAS A LOS FUNCIONARIOS Y EMPLEADOS DEL ESTADO DE ZACATECAS | 1 | as first published: 22 February 1955 |
| `ley-de-expropiacion/` | LEY DE EXPROPIACION PARA EL ESTADO DE ZACATECAS | 3 | as first published, then each reform: 23 September 1944 to 4 March 1965 |
| `ley-de-financiamientos-obligaciones-emprestitos-y-deuda-publ/` | LEY DE FINANCIAMIENTOS, OBLIGACIONES, EMPRESTITOS Y DEUDA PUBLICA DEL ESTADO DE ZACATECAS Y SUS MUNICIPIOS | 1 | as first published: 13 August 2024 |
| `ley-de-firma-electronica/` | LEY DE FIRMA ELECTRONICA DEL ESTADO DE ZACATECAS | 3 | as first published, then each reform: 26 December 2013 to 31 December 2024 |
| `ley-de-fiscalizacion-y-rendicion-de-cuentas/` | LEY DE FISCALIZACION Y RENDICION DE CUENTAS DEL ESTADO DE ZACATECAS | 3 | as first published, then each reform: 19 July 2017 to 27 March 2025 |
| `ley-de-fomento-a-la-ganaderia/` | LEY DE FOMENTO A LA GANADERIA DEL ESTADO DE ZACATECAS | 6 | as first published, then each reform: 30 April 2006 to 1 October 2023 |
| `ley-de-fomento-a-las-actividades-realizadas-por-organizacion/` | LEY DE FOMENTO A LAS ACTIVIDADES REALIZADAS POR ORGANIZACIONES DE LA SOCIEDAD CIVIL EN EL ESTADO DE ZACATECAS Y SUS MUNICIPIOS | 2 | as first published, then each reform: 15 July 2004 to 24 March 2013 |
| `ley-de-fomento-para-el-desarrollo-economico/` | LEY DE FOMENTO PARA EL DESARROLLO ECONOMICO DEL ESTADO DE ZACATECAS | 8 | as first published, then each reform: 17 August 2003 to 1 October 2023 |
| `ley-de-fraccionamientos-rurales/` | LEY DE FRACCIONAMIENTOS RURALES PARA EL ESTADO DE ZACATECAS | 5 | as first published, then each reform: 14 June 2009 to 25 February 2021 |
| `ley-de-hacienda/` | LEY DE HACIENDA DEL ESTADO DE ZACATECAS | 13 | as first published, then each reform: 1 January 2017 to 22 August 2026 |
| `ley-de-hacienda-municipal/` | LEY DE HACIENDA MUNICIPAL PARA EL ESTADO DE ZACATECAS | 12 | as first published, then each reform: 1 January 1985 to 4 December 2014 |
| `ley-de-ingresos/` | LEY DE INGRESOS DEL ESTADO DE ZACATECAS PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 3 January 2026 |
| `ley-de-justicia-administrativa/` | LEY DE JUSTICIA ADMINISTRATIVA DEL ESTADO DE ZACATECAS | 2 | as first published, then each reform: 22 February 2026 to 25 March 2026 |
| `ley-de-justicia-alternativa/` | LEY DE JUSTICIA ALTERNATIVA DEL ESTADO DE ZACATECAS | 3 | as first published, then each reform: 1 January 2009 to 25 February 2021 |
| `ley-de-justicia-comunitaria/` | LEY DE JUSTICIA COMUNITARIA DEL ESTADO DE ZACATECAS | 2 | as first published, then each reform: 11 July 2002 to 27 October 2005 |
| `ley-de-la-comision-de-derechos-humanos/` | LEY DE LA COMISION DE DERECHOS HUMANOS DEL ESTADO DE ZACATECAS | 11 | as first published, then each reform: 28 January 1993 to 5 October 2025 |
| `ley-de-las-entidades-publicas-paraestatales/` | LEY DE LAS ENTIDADES PUBLICAS PARAESTATALES | 5 | as first published, then each reform: 8 January 1989 to 4 July 2019 |
| `ley-de-las-instituciones-policiales-de-la-secretaria-de-segu/` | LEY DE LAS INSTITUCIONES POLICIALES DE LA SECRETARIA DE SEGURIDAD PUBLICA DEL ESTADO DE ZACATECAS | 2 | as first published, then each reform: 23 April 2015 to 11 August 2024 |
| `ley-de-los-derechos-de-ninas-ninos-y-adolescentes/` | LEY DE LOS DERECHOS DE NIÑAS, NIÑOS Y ADOLESCENTES DEL ESTADO DE ZACATECAS | 13 | as first published, then each reform: 29 September 2015 to 27 January 2026 |
| `ley-de-los-derechos-y-defensa-del-contribuyente/` | LEY DE LOS DERECHOS Y DEFENSA DEL CONTRIBUYENTE DEL ESTADO DE ZACATECAS Y SUS MUNICIPIOS | 5 | as first published, then each reform: 1 January 2018 to 31 December 2019 |
| `ley-de-los-sistemas-de-agua-potable-alcantarillado-y-saneami/` | LEY DE LOS SISTEMAS DE AGUA POTABLE, ALCANTARILLADO Y SANEAMIENTO DEL ESTADO DE ZACATECAS | 3 | as first published, then each reform: 14 August 1994 to 24 March 2013 |
| `ley-de-mecenazgo-cultural/` | LEY DE MECENAZGO CULTURAL DEL ESTADO DE ZACATECAS | 1 | as first published: 5 October 2025 |
| `ley-de-mejora-regulatoria/` | LEY DE MEJORA REGULATORIA DEL ESTADO DE ZACATECAS Y SUS MUNICIPIOS | 1 | as first published: 20 August 2020 |
| `ley-de-obra-publica-y-servicios-relacionados/` | LEY DE OBRA PUBLICA Y SERVICIOS RELACIONADOS PARA EL ESTADO Y LOS MUNICIPIOS DE ZACATECAS | 1 | as first published: 19 May 2020 |
| `ley-de-obras-por-cooperacion/` | LEY DE OBRAS POR COOPERACION | 1 | as first published: 1 January 1989 |
| `ley-de-participacion-ciudadana/` | LEY DE PARTICIPACION CIUDADANA PARA EL ESTADO DE ZACATECAS | 3 | as first published, then each reform: 9 September 2001 to 9 March 2023 |
| `ley-de-planeacion/` | LEY DE PLANEACION DEL ESTADO DE ZACATECAS Y SUS MUNICIPIOS | 1 | as first published: 10 August 2017 |
| `ley-de-premios-al-merito-ciudadano/` | LEY DE PREMIOS AL MERITO CIUDADANO DEL ESTADO DE ZACATECAS | 2 | as first published, then each reform: 4 September 2014 to 17 September 2026 |
| `ley-de-prevencion-social-de-la-violencia-y-la-delincuencia/` | LEY DE PREVENCION SOCIAL DE LA VIOLENCIA Y LA DELINCUENCIA DEL ESTADO DE ZACATECAS | 1 | as first published: 5 October 2025 |
| `ley-de-procedimiento-administrativo/` | LEY DE PROCEDIMIENTO ADMINISTRATIVO DEL ESTADO Y MUNICIPIOS DE ZACATECAS | 1 | as first published: 26 September 2009 |
| `ley-de-productos-organicos/` | LEY DE PRODUCTOS ORGANICOS PARA EL ESTADO DE ZACATECAS | 1 | as first published: 29 November 2015 |
| `ley-de-proteccion-civil/` | LEY DE PROTECCION CIVIL DEL ESTADO Y MUNICIPIOS DE ZACATECAS | 5 | as first published, then each reform: 15 March 2018 to 22 August 2026 |
| `ley-de-proteccion-contra-la-exposicion-al-humo-de-tabaco/` | LEY DE PROTECCION CONTRA LA EXPOSICION AL HUMO DE TABACO DEL ESTADO DE ZACATECAS -ANTES LEY DE PROTECCION DE LA SALUD DE LOS NO FUMADORES DEL ESTADO DE ZACATECAS- | 4 | as first published, then each reform: 6 October 2011 to 17 September 2026 |
| `ley-de-proteccion-de-datos-personales-en-posesion-de-sujetos/` | LEY DE PROTECCION DE DATOS PERSONALES EN POSESION DE SUJETOS OBLIGADOS DEL ESTADO DE ZACATECAS | 2 | as first published, then each reform: 21 September 2025 to 19 July 2026 |
| `ley-de-proteccion-de-los-derechos-de-las-personas-adultas-ma/` | LEY DE PROTECCION DE LOS DERECHOS DE LAS PERSONAS ADULTAS MAYORES PARA EL ESTADO DE ZACATECAS | 10 | as first published, then each reform: 25 June 2006 to 22 January 2026 |
| `ley-de-proteccion-y-conservacion-del-patrimonio-cultural/` | LEY DE PROTECCION Y CONSERVACION DEL PATRIMONIO CULTURAL DEL ESTADO DE ZACATECAS | 4 | as first published, then each reform: 15 December 2013 to 29 September 2018 |
| `ley-de-residuos-solidos/` | LEY DE RESIDUOS SOLIDOS PARA EL ESTADO DE ZACATECAS | 3 | as first published, then each reform: 17 October 2010 to 24 March 2013 |
| `ley-de-responsabilidad-patrimonial/` | LEY DE RESPONSABILIDAD PATRIMONIAL DEL ESTADO Y MUNICIPIOS DE ZACATECAS | 1 | as first published: 30 April 2023 |
| `ley-de-responsabilidades-de-los-servidores-publicos/` | LEY DE RESPONSABILIDADES DE LOS SERVIDORES PUBLICOS DEL ESTADO Y MUNICIPIOS DE ZACATECAS | 3 | as first published, then each reform: 7 February 2013 to 6 September 2017 |
| `ley-de-revocacion-de-mandato/` | LEY DE REVOCACION DE MANDATO DEL ESTADO DE ZACATECAS | 1 | as first published: 8 September 2024 |
| `ley-de-salud/` | LEY DE SALUD DEL ESTADO DE ZACATECAS | 21 | as first published, then each reform: 8 March 2018 to 17 September 2026 |
| `ley-de-salud-mental/` | LEY DE SALUD MENTAL DEL ESTADO DE ZACATECAS | 1 | as first published: 9 October 2025 |
| `ley-de-servicios-integrales-para-el-desarrollo-infantil-de-z/` | LEY DE SERVICIOS INTEGRALES PARA EL DESARROLLO INFANTIL DE ZACATECAS | 2 | as first published, then each reform: 4 July 2013 to 12 August 2021 |
| `ley-de-transparencia-y-acceso-a-la-informacion-publica/` | LEY DE TRANSPARENCIA Y ACCESO A LA INFORMACION PUBLICA DEL ESTADO DE ZACATECAS | 2 | as first published, then each reform: 16 October 2025 to 19 July 2026 |
| `ley-de-transporte-transito-y-vialidad/` | LEY DE TRANSPORTE, TRANSITO Y VIALIDAD DEL ESTADO DE ZACATECAS | 8 | as first published, then each reform: 21 November 2013 to 1 October 2026 |
| `ley-de-turismo/` | LEY DE TURISMO DEL ESTADO DE ZACATECAS | 10 | as first published, then each reform: 8 March 2018 to 16 September 2026 |
| `ley-de-videovigilancia/` | LEY DE VIDEOVIGILANCIA PARA EL ESTADO DE ZACATECAS | 2 | as first published, then each reform: 18 February 2019 to 7 February 2021 |
| `ley-de-voluntad-anticipada/` | LEY DE VOLUNTAD ANTICIPADA DEL ESTADO DE ZACATECAS | 1 | as first published: 10 July 2018 |
| `ley-del-centro-de-conciliacion-laboral/` | LEY DEL CENTRO DE CONCILIACION LABORAL DEL ESTADO DE ZACATECAS | 3 | as first published, then each reform: 31 March 2020 to 16 October 2025 |
| `ley-del-centro-de-investigaciones-bibliograficas-de-zacateca/` | LEY DEL CENTRO DE INVESTIGACIONES BIBLIOGRAFICAS DE ZACATECAS | 2 | as first published, then each reform: 15 July 2006 to 24 March 2013 |
| `ley-del-ejercicio-profesional-en-el-estado-de-zacatecas/` | LEY DEL EJERCICIO PROFESIONAL EN EL ESTADO DE ZACATECAS | 3 | as first published, then each reform: 8 June 2003 to 19 August 2018 |
| `ley-del-equilibrio-ecologico-y-la-proteccion-al-ambiente/` | LEY DEL EQUILIBRIO ECOLOGICO Y LA PROTECCION AL AMBIENTE DEL ESTADO DE ZACATECAS | 8 | as first published, then each reform: 1 April 2007 to 10 January 2021 |
| `ley-del-expediente-clinico-universal/` | LEY DEL EXPEDIENTE CLINICO UNIVERSAL PARA EL ESTADO DE ZACATECAS | 1 | as first published: 31 March 2014 |
| `ley-del-instituto-de-la-defensoria-publica/` | LEY DEL INSTITUTO DE LA DEFENSORIA PUBLICA DEL ESTADO DE ZACATECAS | 2 | as first published, then each reform: 15 February 2015 to 1 January 2020 |
| `ley-del-instituto-de-seguridad-y-servicios-sociales-de-los-t/` | LEY DEL INSTITUTO DE SEGURIDAD Y SERVICIOS SOCIALES DE LOS TRABAJADORES DEL ESTADO DE ZACATECAS | 3 | as first published, then each reform: 22 March 2015 to 9 October 2025 |
| `ley-del-instituto-regional-del-patrimonio-mundial-en-zacatec/` | LEY DEL INSTITUTO REGIONAL DEL PATRIMONIO MUNDIAL EN ZACATECAS | 2 | as first published, then each reform: 31 August 2014 to 26 November 2017 |
| `ley-del-notariado/` | LEY DEL NOTARIADO PARA EL ESTADO DE ZACATECAS | 4 | as first published, then each reform: 1 October 2006 to 19 December 2025 |
| `ley-del-periodico-oficial/` | LEY DEL PERIODICO OFICIAL DEL ESTADO DE ZACATECAS Y SUS MUNICIPIOS | 2 | as first published, then each reform: 1 January 2015 to 19 March 2023 |
| `ley-del-servicio-civil/` | LEY DEL SERVICIO CIVIL DEL ESTADO DE ZACATECAS | 23 | as first published, then each reform: 14 September 1996 to 17 September 2026 |
| `ley-del-servicio-profesional-de-carrera/` | LEY DEL SERVICIO PROFESIONAL DE CARRERA DEL ESTADO Y MUNICIPIOS DE ZACATECAS | 3 | as first published, then each reform: 5 August 2004 to 27 November 2022 |
| `ley-del-sistema-de-medios-de-impugnacion-electoral/` | LEY DEL SISTEMA DE MEDIOS DE IMPUGNACION ELECTORAL DEL ESTADO DE ZACATECAS | 7 | as first published, then each reform: 5 October 2003 to 16 February 2025 |
| `ley-del-sistema-estatal-anticorrupcion-de-zacatecas/` | LEY DEL SISTEMA ESTATAL ANTICORRUPCION DE ZACATECAS | 6 | as first published, then each reform: 16 July 2017 to 16 October 2025 |
| `ley-del-sistema-estatal-de-archivos-de-zacatecas/` | LEY DEL SISTEMA ESTATAL DE ARCHIVOS DE ZACATECAS | 1 | as first published: 8 November 1987 |

## Source

The legislation compilation of Mexico's Supreme Court, the Suprema Corte de Justicia de la Nación (SCJN), at <https://legislacion.scjn.gob.mx/>. For each ordenamiento it lists every publication in the state's official gazette (Periódico Oficial) that changed it (decree, erratum, ruling), with the date of publication, the decree's extract and the whole consolidated text as it stood after that publication. Each version here is one of those texts.

## Dates

- Each commit is dated at **noon, America/Mexico_City, on the day the publication took effect**: the day its own transitorios name, as SCJN's extract quotes them (most often the day after publication). When a decree names none, 3 days after publication.
- A consolidated text holds every change published before it, so it is never dated before the latest of their in-force days. Different in-force days for parts of one decree are not split.
- An act's first commit is its first publication when SCJN holds the original text; otherwise it is the oldest version SCJN holds.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 Bis; `encabezado.md` holds the title, the promulgation and preamble; `transitorios-original.md` the original transitory articles and `transitorios-<date>.md` those of the reform published that day. Section headings and editor's notes such as "(REFORMADO, P.O. ...)" stay in the file of the article they stand before. One paragraph per line.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of SCJN's own text of that version (read independently of the parser), and every unit's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the publication that changed the text (a decree, an erratum or a ruling), named by its category, gazette date and issue, with an e-mail address that cannot exist (`<key>@legislacion.scjn.gob.mx.invalid`). The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the state's official gazette (Periódico Oficial). The history starts with the oldest text SCJN holds for each ordenamiento, which for many is later than its enactment. Only the ordenamientos listed above are included.
