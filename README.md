# Línguas v2 — GitHub Pages, gratis

## Archivos
- `index.html`: estructura y pantallas.
- `styles.css`: diseño adaptable a móvil y escritorio.
- `app.js`: banco de ejercicios, lógica de actividades y guardado del progreso.

## Publicar
1. Sube los tres archivos a la raíz de tu repositorio de GitHub.
2. Entra en **Settings → Pages**.
3. En **Build and deployment**, elige **Deploy from a branch**.
4. Selecciona `main` y la carpeta `/(root)`, y pulsa **Save**.
5. Abre la URL que aparece en Settings → Pages.

No hay servidor, API, claves, build ni facturación.

## Funciones
- Portugués europeo y gallego.
- Ejercicios de vocabulario, gramática y lectura para A1–C2.
- Exámenes de hasta 10 preguntas (según el banco disponible por nivel) con puntuación e historial.
- Listening mediante `speechSynthesis` del navegador.
- Speaking con consignas y reconocimiento de voz opcional (`SpeechRecognition`), según soporte del navegador.
- Progreso guardado en `localStorage`.
- Exportar/importar progreso mediante archivo JSON.
- Funciona sin cuenta; el progreso permanece en el mismo navegador y dispositivo.

## Limitaciones honestas
- Es una academia estática sin IA generativa: no puede corregir libremente cualquier frase ni evaluar de forma fiable la pronunciación.
- El banco de ejercicios de esta versión es una primera base y no contiene todavía una cantidad equivalente a un examen oficial de cada nivel. Algunas categorías o niveles pueden tener pocas preguntas; se pueden ampliar los bancos en `app.js`.
- La síntesis de voz y el reconocimiento dependen del navegador y las voces instaladas. La disponibilidad de una voz de gallego no está garantizada.
- El nivel estimado es orientativo y no equivale a una certificación oficial.
- El progreso se guarda en el navegador local. Exporta `linguas-progreso.json` con el botón de la web para hacer copia de seguridad o transferirlo; puedes importarlo en otro dispositivo.
