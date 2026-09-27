# Problem Brief

## Decisión del problema

### Problema elegido

> El problema ganador en una frase, sin mencionar blockchain, y quién lo propuso.

En el manejo de evidencia digital, no existe forma de comprobar de manera independiente que un archivo no fue alterado en algún punto de la cadena de custodia, entre quien la recolecta, quien la analiza y quien la presenta legalmente.

Propuesto por: Johan Jimenez

### Por qué elegimos este

> Qué inclinó al equipo por este problema frente a los demás, según los criterios de la Sesión 1.

Escogimos este proyecto porque nos llama mucho la atención el alcance de la ciberseguridad y es un área en la que queremos aprender y adquirir experiencia. Además, como grupo consideramos que es una propuesta más completa y unificada para aplicar tecnologías como Blockchain en la protección y manejo de la información.

### Propuestas descartadas

> Cada propuesta considerada, quién la propuso y el motivo del descarte.

Escriban aquí su respuesta.

### Cómo tomamos la decisión

> Cómo llegó el equipo al acuerdo: votación, consenso tras debate u otro.

Como grupo, tomamos la decisión después de compartir nuestras ideas y analizar las diferentes propuestas. Finalmente, coincidimos en que este proyecto era el que más nos llamaba la atención, especialmente por el alcance de la ciberseguridad y la posibilidad de aplicar tecnologías como Blockchain. Por eso decidimos unir nuestros conocimientos y trabajar juntos en esta propuesta.

---

## Problem Brief

### Encabezado

> Nombre del proyecto y una frase que describa el problema. Extensión: breve.

**Nombre del proyecto: CustodiaChain — Cadena de Custodia Verificable de Evidencia Digital**

**Frase del problema:** En un proceso de custodia de evidencia digital que pasa por varias manos, hoy nadie puede demostrar de forma independiente y verificable que el archivo entregado al final es exactamente el mismo que se recolectó al inicio.

### Equipo y roles

> Integrantes con su usuario de GitHub, rol asumido por cada persona, responsable de las entregas y canal de coordinación interna. Extensión: breve.

**Líder de proyecto / Product Owner**<br>
**Usuario GitHub** : jbxmusic<br>
**Nombre** Jonathan Agudelo

**Desarrollador Frontend**<br>
**Usuario GitHub** : galbeiroc<br>
**Nombre**: Albeiro Crespo Gutierrez<br>

**Desarrollador Blockchain / Stellar (SDK) y Desarrollador Soroban (contratos inteligentes)**<br>
**Usuario GitHub** : softven-digital<br>
**Nombre**: Tito Acosta<br>

**Usuario GitHub** : jsebas2220<br>
**Nombre**: Johan Jimenez<br>

**QA Automatizado**<br>
Vacante

**QA Manual Documentación y evidencia**<br>
**Usuario GitHub**: anadeliaca2-cpu<br>
**Nombre**: Ana Caicedo

### Problema y evidencia

> Enunciado del problema en una frase, sin mencionar blockchain. Contexto, frecuencia y alcance. Evidencia mínima de que el problema existe: observación directa, experiencia propia, conversaciones o fuentes consultadas, con enlace o cita cuando aplique. Extensión: 150–300 palabras.

**Enunciado del problema (una frase, sin mencionar blockchain):**
En un proceso de custodia de evidencia digital que pasa por varias manos, hoy nadie puede demostrar de forma independiente y verificable que el archivo entregado al final es exactamente el mismo que se recolectó al inicio.

**Contexto, frecuencia y alcance:**
En procesos de custodia de evidencia digital que pasan por varias manos, nadie puede demostrar hoy, de forma independiente y verificable, que el archivo entregado al final es idéntico al recolectado al inicio, lo que compromete su validez probatoria.

### Usuario y actores

> Quién sufre el problema y qué necesita resolver. Cómo lo resuelve hoy y qué le cuesta en dinero, tiempo o esfuerzo. Demás actores que intervienen en el flujo, con el papel que cumple cada uno. Extensión: 150–300 palabras.

**Quién sufre el problema y qué necesita resolver:**
El perito forense y la fiscalía sufren el problema: necesitan demostrar, sin depender solo de su palabra, que el archivo presentado es idéntico al recolectado en la escena, para evitar que la evidencia sea impugnada o descartada por dudas sobre su integridad.

### Flujo actual de valor

> Recorrido paso a paso de cómo se mueve hoy el dinero, la información o el activo, desde el origen hasta el destino. Diagrama o secuencia numerada, con los intermediarios explícitos. Señalar si algún paso responde a una obligación normativa. Extensión: 150–300 palabras.

![Texto alternativo](flujo_custodia_evidencia.png)

Recorrido paso a paso (con intermediarios explícitos y obligación normativa marcada con *):

**Escena del incidente — origen:** se detecta el hallazgo y se inicia la preservación del entorno antes de tocar la evidencia.

Cadena: perito recolector* → custodio/almacén* → analista forense → fiscalía* → juez, cada traspaso exige firma (*obligación normativa). El custodio concentra casi todos los traspasos, siendo el mayor punto único de fallo si su registro es incompleto.


### Fricciones identificadas

> Puntos concretos donde el flujo falla, se encarece o se demora. Cada fricción indica en qué paso ocurre, qué la causa y a quién afecta. Extensión: 150–300 palabras.

Con base en el flujo que ya vimos, aquí están los puntos concretos de fricción, ubicados en cada paso:

*Paso 2 → 3 (Perito recolector → Custodio/almacén**

Las fricciones se concentran en el custodio/almacén (recepción sin validación, registros manuales por acceso, papeleo duplicado con el analista) y en el traspaso a fiscalía (inconsistencias que la defensa impugna). El custodio es el intermediario necesario y a la vez el mayor punto único de fallo.

### Oportunidad e hipótesis

> Oportunidad priorizada entre las fricciones identificadas, con el motivo de la elección. Hipótesis inicial de por qué blockchain podría mejorar ese punto, expresada en términos de qué cambiaría para el usuario. Extensión: 150–300 palabras.

**Oportunidad priorizada:** la fricción en el traspaso Custodio → Fiscalía (paso 3→5) y, más ampliamente, todo el registro de accesos que pasa por el custodio/almacén.

**Motivo de la elección:**

El custodio es el cuello de botella estructural: una falla en su registro puede anular toda la evidencia. Hipótesis: un registro compartido e inalterable eliminaría la necesidad de confiar en una sola parte, permitiendo a fiscalía y juez verificar la integridad de forma independiente y en minutos.

### Criterio de pertinencia

> Justificación de por qué el caso requiere un registro distribuido y no una base de datos tradicional o una integración entre sistemas existentes. Debe apoyarse en al menos uno de los criterios de la Sesión 1: varias partes que no confían entre sí necesitan compartir un mismo registro, el histórico no puede alterarse, o se elimina un intermediario que hoy concentra la confianza. Extensión: 150–300 palabras.

Por qué no basta una base de datos tradicional ni una integración entre sistemas:

Una base de datos centralizada siempre depende de un administrador de confianza. Como custodio, fiscalía, defensa y juez no confían entre sí, necesitan un registro distribuido donde nadie pueda alterar retroactivamente el historial sin que las demás partes lo detecten, sin depender de la buena fe de una sola institución.

### Supuestos y riesgos

> Dos o tres supuestos que tendrían que ser ciertos para que la hipótesis funcione, y qué podría invalidarla. Extensión: 150–300 palabras.

**Supuestos que tendrían que ser ciertos:**

Supuestos clave: que el sistema judicial reconozca legalmente un registro on-chain como prueba, que cada actor use su propia clave sin compartirla, y que la seguridad física del objeto siga garantizada aparte. Riesgo: si no hay reconocimiento legal, o la fricción real es coordinación humana, la solución no resolvería el problema.
