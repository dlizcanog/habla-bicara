# Habla · Bicara

Intérprete por voz español ⇄ bahasa Indonesia para conversaciones cara a cara.

- Cada botón tiene un idioma fijo: el amarillo (ES) siempre traduce al bahasa y el rojo (ID) siempre al español. Nunca adivina el idioma.
- Reconoce la voz con el micrófono de Chrome, traduce con Claude y lee la traducción en voz alta en el idioma de destino.
- **Memoria**: guarda la situación del día y las reglas aprendidas de cada corrección (botón Corregir), y las usa en todas las traducciones. También recuerda las últimas frases de la conversación para mantener las mismas palabras.
- **¿Qué dice?** muestra en español lo que dice literalmente cada frase en bahasa.
- Calidad Rápida o Precisa (modelo más fuerte) en Memoria.
- La clave de API y la memoria se guardan solo en el navegador del teléfono (localStorage); no están en este repositorio.

- Bahasa coloquial (bahasa sehari-hari), no formal.
- Tolera pausas cortas al hablar: espera el silencio elegido en Memoria (1 s, 1,8 s o 2,8 s) antes de traducir. Tocar el botón otra vez traduce al instante.

## Modo escucha

`escuchar.html`: solo escucha. Por defecto usa el mismo reconocimiento de voz de Chrome que la conversación (bahasa, escucha continua) y Claude traduce cada frase al español y estima quién habla por el contexto; el nombre de cada frase se puede corregir. Opcional en Ajustes: Deepgram (nova-3), que separa las voces por el sonido pero reconoce peor el bahasa y necesita su propia clave.

Página: https://dlizcanog.github.io/habla-bicara/
Modo escucha: https://dlizcanog.github.io/habla-bicara/escuchar.html
