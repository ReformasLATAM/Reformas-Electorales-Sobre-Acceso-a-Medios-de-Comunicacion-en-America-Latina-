# Reformas Electorales Sobre Acceso a Medios de Comunicación en América Latina 

Bienvenidos/as al repositorio GitHub de la base de datos "Reformas Electorales Sobre Acceso a Medios de Comunicación en América Latina" mantenida por integrantes del Observatorio de Reformas Políticas en América Latina.

## Contenidos

-   [Resumen](#resumen)
-   [Descripción](#descripción)
-   [Citado](#citado)

## Resumen

La base de datos contiene información sobre la normativa que regula el acceso a medios de comunicación y las campañas electorales de 18 países de América Latina entre 1981 y 2020. La revisión se realizó a partir del año de la transición a la democracia de cada país, con base en lo planteado por Alcántara; Páramo; Freidenberg y Déniz, 2006. En el caso de los países con procesos de cambio político graduales, se utiliza como base el año de inicio de la tercera ola de la democracia en América Latina (Huntington, 1991). La siguiente tabla precisa, para cada país, el año inicial (año cero) y final de la información contenida en la base de datos.

Integrantes del Observatorio de Reformas Políticas en América Latina recopilaron y codificaron la información. Las personas responsables de la recopilación de los datos son Flavia Freidenberg (Instituto de Investigaciones Jurídicas) y Karina Cáceres (Universidad de Salamanca), mientras que las personas responsables de la codificación de los datos son Mayte Sánchez Hernández (Facultad de Estudios Superiores Acatlán, UNAM) y Carlos Guadarrama Cruz (Facultad de Estudios Superiores Acatlán, UNAM).

## Descripción

El directorio `./Data/` contiene el archivo `./Data/DD_Acceso_Medios` en el cual se encuentra toda la información relevante respecto a la base de datos de reformas electorales sobre acceso a medios de comunicación en América Latina. En específico, la base de datos se compone de las siguientes variables:

-   `país`: nombre del país en el cual se llevó a cabo la reforma al régimen electoral ejecutivo en América Latina.

-   `cowcode`: código	del	país	de	acuerdo	con	la	codificación	de	“Correlates	of	War” https://correlatesofwar.org/data-sets/cow-country-codes.

-   `año_reforma`: año calendario al que corresponde la reforma al régimen electoral del ejecutivo en cada país de América Latina entre 1978-2021.

-   `consec_reforma_pais`: registra el número consecutivo de las reformas al régimen electoral ejecutivo en cada país de América Latina. Ejemplo: Peru_1 Peru_2, Peru_3, Peru_4.

-   `prohibicion_propaganda`: indica si la reforma electoral prohíbe o no la compra de propaganda en medios de comunicación. Valores: No [0]: la reforma no prohíbe la compra de propaganda en medios. Sí [1]: la reforma prohíbe la compra de propaganda en medios.

-   `acceso_gratuito`: indica si la reforma establece la modalidad gratuita para el acceso a medios. Valores: No [0]: la reforma no señala que la modalidad de acceso a medios es gratuita. Sí [1]: la reforma señala que la modalidad de acceso a medios es gratuita. 

-   `distribucion_tiempos`: indica la fórmula de distribución de los tiempos en medios de comunicación. Valores : No corresponde [0]: no se menciona alguna fórmula de distribución de tiempos en medios. Igualitaria [1]: la distribución de los tiempos en medios se basa en principios de igualdad y equidad en la competencia partidista. Sorteo [2]: la distribución de los tiempos en medios se hace teniendo como base principal el azar. Mixta [3]: la distribución de tiempos en medios combina dos o más fórmulas señaladas en las legislaciones de cada país. Legislativo [4]: la distribución de espacios en televisión depende de los porcentajes de miembros de los partidos políticos en órganos legislativos. No específica [99]: no se cuenta con información sobre el financiamiento para estas actividades.

-   `franja_presidente`: indica la duración en días que la legislación modificada establece para las campañas electorales presidenciales.

-   `franja_legislativo`: indica la duración en días que la legislación modificada establece para las campañas electorales legislativas.

-   `franja_municipal`: indica la duración en días que la legislación modificada establece para las campañas electorales a nivel municipal.

-   `franja_nacional`: indica la duración en días que la legislación modificada establece para las campañas electorales a nivel nacional.

-   `franja_primarias`: indica la duración en días que la legislación modificada establece para las campañas electorales cuando hay elecciones primarias.

-   `veda_electoral_antes`: indica si en la reforma se regula la veda electoral previo a la jornada electoral. Valores: No [0]: la reforma no regula este asunto. Sí [1]: la reforma regula la veda electoral previa a la jornada electoral.

-   `veda_electoral_durante`: indica si en la reforma se regula la veda electoral durante la jornada electoral. Valores: No [0]: la reforma no regula este asunto. Sí [1]: la reforma regula la veda electoral durante la jornada electoral.

-   `veda_electoral_despues`: indica si en la reforma se regula la veda electoral de manera inmediata a la jornada electoral. Valores: No [0]: la reforma no regula nada sobre este asunto. Sí [1]: la reforma regula la veda electoral posterior a la jornada electoral.

-   `proh_dif_enc_antes`: indica si la reforma electoral considera la prohibición de difusión de encuestas electorales previo a la jornada electoral. Valores: No [0]: la reforma no regula este asunto. Sí [1]: la reforma prohíbe la difusión de encuestas electorales previas a la jornada electoral. No específica [99]: no se cuenta con información sobre la prohibición de difusión de encuestas previo a la jornada electoral.

-   `proh_dif_enc_durante`: indica si la reforma electoral considera la prohibición de difusión de encuestas electorales durante la jornada electoral. Valores: No [0]: la reforma no regula este asunto. Sí [1]: la reforma prohíbe la difusión de encuestas electorales durante la jornada electoral.No específica [99]: no se cuenta con información sobre la prohibición de difusión de encuestas durante la jornada electoral.

## Citado

``` r
Freidenberg, Flavia. Dir., 2022, “Reformas Electorales sobre Acceso a Medios de Comunicación en América Latina”, DOI: https://doi.org/10.6084/m9.figshare.18665819.v1. Observatorio de Reformas Políticas en América Latina (1978-2021). Ciudad de México: Instituto de Investigaciones Jurídicas (IIJ-UNAM) y Washington, D.C.: Secretaría para el Fortalecimiento de la Democracia de la Organización de los Estados Americanos (SFD/OEA), V1. Disponible en: https://reformaspoliticas.org/bases-de-datos/
```