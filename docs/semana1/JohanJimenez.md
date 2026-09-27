# Propuesta individual

**Nombre:** Johan Sebastian Jimenez Molina

**Usuario de GitHub:** jsebas2220

---

## El problema

> El problema en una sola frase, sin mencionar blockchain.

Proceso de custodia de evidencia digital que pasa por varias manos, hoy nadie puede demostrar de forma independiente y verificable que el archivo entregado al final es exactamente el mismo que se recolectó al inicio.

## ¿Quién lo sufre?

> Quién tiene el problema y en qué situación lo vive.

Peritos forenses o analistas que maneja evidencia digital dentro de una investigación (criminal, corporativa o de auditoría), junto con la fiscalía o parte legal que debe presentarla ante un juez, y el auditor o defensa que debe confiar en su autenticidad.

Lo viven en el momento en que la evidencia debe pasar de una persona a otra —del sitio donde se recolectó, al analista que la procesa, al almacén donde se resguarda, hasta la sala donde se presenta como prueba—, y en cada uno de esos traspasos dependen únicamente de registros manuales y de la palabra de quien la manejó, sin ninguna forma de comprobar por sí mismos, de manera independiente, que el archivo no fue modificado en el camino.

## ¿Cómo se resuelve hoy y qué cuesta?

> Cómo lo resuelven hoy las personas afectadas y qué les cuesta en dinero, tiempo o esfuerzo.

Los peritos y custodios llevan planillas físicas o en Excel donde cada persona que recibe la evidencia firma a mano, anota fecha/hora y describe el estado del archivo. En algunos casos más avanzados usan un sistema interno de gestión de casos (una base de datos institucional) donde registran los mismos datos, pero de forma digital. Cuando hay dudas sobre la integridad de un archivo, se recalculan hashes manualmente y se comparan contra lo anotado en la planilla o el sistema.

Lo que les cuesta:

Tiempo: cada traspaso de evidencia requiere diligenciar formularios a mano o duplicar el registro en el sistema interno, y en caso de disputa, reconstruir la cadena completa puede tomar horas o días revisando archivos físicos o pidiendo confirmaciones a cada persona que tuvo contacto con la evidencia.
Dinero: el almacenamiento físico seguro de evidencia (bodegas, cajas fuertes, personal dedicado a custodiarla) y el tiempo del personal técnico y legal invertido en re-verificar y defender la cadena de custodia ante disputas tiene un costo operativo alto, especialmente en casos que se alargan o se apelan.
Esfuerzo / riesgo: si una sola firma falta, un registro está incompleto o hay una inconsistencia de fechas, toda la evidencia puede ser impugnada y descartada en el proceso legal, sin importar que el archivo en sí nunca haya sido alterado — el esfuerzo de meses de investigación se pierde por una falla puramente administrativa, no técnica.

## ¿Por qué creo que blockchain podría aportar?

> Hipótesis personal, no certeza, apoyada en al menos un criterio de la Sesión 1: partes que no confían entre sí comparten un registro, histórico inalterable, o eliminar un intermediario que concentra la confianza.

Hipótesis:

Creo que este problema puede beneficiarse de un registro histórico inalterable compartido entre partes que no confían plenamente entre sí (perito, custodio, fiscalía, defensa), porque hoy cada actor depende de la palabra y los archivos internos de los demás para creer que la evidencia no fue modificada. Si existiera un registro donde cada evento de custodia quedara anotado de forma que ninguna de las partes —ni siquiera la institución que lo administra— pudiera alterarlo retroactivamente, cualquiera de ellas podría verificar la integridad de la evidencia por sí misma, sin tener que confiar ciegamente en la otra.

No tengo certeza de que esto elimine por completo la necesidad de procesos legales o de un custodio físico de la evidencia (el archivo original sigue debiendo resguardarse en algún lugar), pero sí creo, como hipótesis a validar con el MVP, que puede reducir el esfuerzo y el riesgo de impugnación que hoy generan los registros manuales inconsistentes entre las partes.
