PIANO CHORDS HELPER
==================

Una aplicación web interactiva para identificar y aprender acordes de piano.

DESCRIPCIÓN
-----------
Esta aplicación permite a los usuarios identificar acordes de piano de dos maneras:
1. Clicando en las teclas del piano virtual para formar acordes
2. Ingresando nombres de acordes para ver sus notas

CARACTERÍSTICAS PRINCIPALES
-------------------------
- Piano virtual interactivo de 3 octavas
- Sistema de notación musical seleccionable:
  * Notación italiana: Do, Re, Mi, Fa, Sol, La, Si
  * Notación anglosajona: C, D, E, F, G, A, B
  * Cambio dinámico con el botón "🎵 Do#, Mib" / "🎵 C#, Eb"
- Interfaz multiidioma (Español/Inglés):
  * Cambio de idioma con botón de bandera (🇪🇸/🇬🇧)
  * Todas las etiquetas y textos se actualizan automáticamente
  * Información de acordes traducida completamente
  * Notación musical independiente del idioma de la interfaz
- Botón "Otros Acordes" (NUEVO v1.2.0):
  * Explora acordes con una nota como tónica
  * Encuentra acordes que contienen 3 notas específicas
  * Previsualización en azul y selección por doble clic
  * Solo ilumina una tecla por nota (la más central)
- Base de datos completa de acordes (mayores, menores, séptimas, etc.)
- Nombres alternativos de acordes mostrados entre paréntesis
- Información detallada de cada acorde incluyendo:
  * Estructura de notas (tónica, tercera, quinta, etc.)
  * Características sonoras
  * Usos comunes en música
  * Canciones famosas que los usan
  * Progresiones típicas
  * Consejos para tocar en piano

CÓMO USAR LA APLICACIÓN
----------------------
1. ABRIR LA APLICACIÓN
   - Abre el archivo "Piano Chords.html" en tu navegador web
   - No requiere instalación ni servidor
   - Por defecto se inicia en español con notación italiana

2. CAMBIAR IDIOMA Y NOTACIÓN
   - Cambiar idioma: Haz clic en la bandera (🇪🇸/🇬🇧) en la esquina superior derecha
   - Cambiar notación: Haz clic en "🎵 Do#, Mib" o "🎵 C#, Eb" en la esquina superior izquierda
   - Ambas opciones son independientes entre sí

3. IDENTIFICAR ACORDES
   - Haz clic en las teclas del piano para seleccionar notas
   - El acorde se identificará automáticamente
   - Aparecerá información detallada del acorde

4. BUSCAR ACORDES POR NOMBRE
   - Escribe el nombre del acorde en el campo de texto
   - Ejemplos anglo: "Cm7", "F#dim", "Amaj7"
   - Ejemplos italiano: "Dom7", "Fa#dim", "Lamaj7"
   - Haz clic en "Show Chord" / "Mostrar Acorde"
   - Las teclas correspondientes se resaltarán

5. OBTENER INFORMACIÓN ADICIONAL
   - Haz clic en "Chord Info" / "Info del Acorde" para ver información detallada
   - Incluye estructura de notas, características y consejos
   - La información se muestra en el idioma seleccionado

6. EXPLORAR "OTROS ACORDES" (NUEVO v1.2.0)
   - El botón "Otros Acordes" se activa automáticamente con 1 o 3 notas seleccionadas
   
   CON 1 NOTA:
   - Selecciona una sola nota en el piano
   - Haz clic en "Otros Acordes"
   - Verás todos los acordes que usan esa nota como tónica
   - Clic simple: Previsualiza el acorde en azul
   - Doble clic: Selecciona el acorde completo
   - La nota original permanece en rojo
   
   CON 3 NOTAS:
   - Selecciona tres notas en el piano
   - Haz clic en "Otros Acordes"
   - Verás todos los acordes que contienen esas tres notas
   - Clic simple: Previsualiza notas adicionales en azul
   - Doble clic: Selecciona el acorde completo
   - Solo se ilumina una tecla por nota (la más central del teclado)

RECURSOS EXTERNOS
----------------
La aplicación incluye enlaces a recursos externos para profundizar:

🧠 GROK AI (Primero)
- IA de xAI disponible en Grok.com
- Prompt detallado optimizado para acordes de piano
- Incluye: características, consejos, progresiones, notaciones alternativas
- Búsqueda inteligente con contexto musical

🤖 PERPLEXITY AI
- Búsqueda inteligente con prompt detallado
- Incluye: características, consejos, progresiones, notaciones alternativas
- Prompt en español optimizado para acordes de piano

🎹 PIANO CHORDS (Último)
- Enlace inteligente a pianochord.org
- Traducción automática de notación italiana a anglosajona
- Extrae solo la nota raíz del acorde para mostrar todos los acordes de esa nota
- URLs optimizadas: sostenidos como "-sharp" (ej: c-sharp.html)
- Ejemplos:
  * "Do7" → c.html (muestra todos los acordes de Do/C)
  * "Fasus4" → f.html (muestra todos los acordes de Fa/F)
  * "Do#maj7" → c-sharp.html (muestra todos los acordes de Do#/C#)

ACORDES SOPORTADOS
-----------------
La aplicación soporta acordes en ambas notaciones:

NOTACIÓN ANGLOSAJONA:
MAYORES: C, C#, D, D#, E, F, F#, G, G#, A, A#, B
MENORES: Cm, C#m, Dm, D#m, Em, Fm, F#m, Gm, G#m, Am, A#m, Bm
SÉPTIMAS: C7, Cmaj7, Cm7, Cdim7, Cm7b5, etc.
AUMENTADOS: Caug (+)
DISMINUIDOS: Cdim, Cdim7 (°)
SUSPENDIDOS: Csus2, Csus4
SÉXTAS: C6, Cm6
NOVENAS: C9, Cm9, etc.

NOTACIÓN ITALIANA:
MAYORES: Do, Do#, Re, Re#, Mi, Fa, Fa#, Sol, Sol#, La, La#, Si
MENORES: Dom, Do#m, Rem, Re#m, Mim, Fam, Fa#m, Solm, Sol#m, Lam, La#m, Sim
SÉPTIMAS: Do7, Domaj7, Dom7, Dodim7, Dom7b5, etc.
AUMENTADOS: Doaug (+)
DISMINUIDOS: Dodim, Dodim7 (°)
SUSPENDIDOS: Dosus2, Dosus4
SÉXTAS: Do6, Dom6
NOVENAS: Do9, Dom9, etc.

Notas re4ferentes a la pestaña "Pentagrama"

Nivel 1: seqA = "C4, D4, B3, C3, D3, B2, C5, D5, B4, G4, F4, F3, G3, G2, G3, G4, F4, F3, F4, F5", 
seqB = "G2, G3, G4, A4, G3, A3, G2, A2, F3, F4, F5, E5, F4, E4, F3, E3, G3, D3, E3, F3";


Nivel 1:
Notas naturales (C, D, E, F, G, A, B) desde G2 hasta F5.

Nivel 2:
Notas naturales (C, D, E, F, G, A, B) desde F2 hasta G5.

Nivel 3:
Notas naturales (C, D, E, F, G, A, B) desde C2 hasta B5 (todas las naturales en octavas 2–5).
Nivel 4:
Todas las notas (incluidos sostenidos) desde C2 hasta B5 (cromático completo).
Nivel 5:
Igual que Nivel 4 (C2–B5 cromático), pero algunas alteraciones con sostenido pueden mostrarse como bemol aleatoriamente.




TECNOLOGÍA
----------
- HTML5, CSS3, JavaScript (Vanilla)
- Sin dependencias externas
- Funciona completamente offline
- Compatible con navegadores modernos

ARCHIVOS DEL PROYECTO
--------------------
- Piano Chords.html: Aplicación principal
- README.txt: Esta documentación
- .gitignore: Archivos ignorados por Git

AUTOR
-----
Aplicación desarrollada para facilitar el aprendizaje de teoría musical y acordes de piano.

VERSIÓN
-------
1.3.0

HISTORIAL DE VERSIONES
----------------------

VERSIÓN 1.3.0 (Actual)
---------------------
✨ NUEVAS CARACTERÍSTICAS:

🎹 FAVICON:
- Añadido favicon personalizado con emoji de piano 🎹
- Mejora la identificación visual de la aplicación en pestañas del navegador

🔗 MEJORAS EN RECURSOS EXTERNOS:

📖 MODAL "LEARN MORE":
- Reordenamiento de enlaces para mejor experiencia de usuario
- Nuevo orden: Grok AI → Perplexity AI → Piano Chords
- Eliminado enlace a Wikipedia para simplificar opciones

🎹 PIANO CHORDS (pianochord.org):
- Mejora significativa en la integración con pianochord.org
- Traducción automática de notación italiana a anglosajona
  * Ejemplo: "Do7" se traduce a "C" y envía a c.html
  * Ejemplo: "Fasus4" se traduce a "F" y envía a f.html
- Extracción inteligente de la nota raíz del acorde
- Envío a la página de lista de acordes de la nota raíz (más útil que acordes específicos)
- Conversión correcta de sostenidos en URLs:
  * Los sostenidos (#) se convierten a "-sharp" en la URL
  * Ejemplo: "C#" → c-sharp.html, "Fa#" → f-sharp.html
- Soluciona problemas de compatibilidad con nomenclatura no anglosajona
- Mejor experiencia al explorar todos los acordes de una nota específica

VERSIÓN 1.2.0
-------------
✨ NUEVAS CARACTERÍSTICAS:

🎹 BOTÓN "OTROS ACORDES":
- Nuevo botón que se activa automáticamente con 1 nota o 3 notas seleccionadas
- Con 1 nota seleccionada:
  * Muestra todos los acordes que tienen esa nota como tónica
  * Perfecto para explorar variaciones de acordes
  * Ayuda a descubrir nuevos acordes desde una nota base
  
- Con 3 notas seleccionadas:
  * Muestra todos los acordes que contienen esas tres notas
  * Útil para identificar acordes alternativos o inversiones
  * Explora diferentes posibilidades armónicas
  
- Interacción intuitiva:
  * Clic simple: Previsualiza el acorde en azul en el piano
  * Doble clic: Selecciona el acorde completo
  * Solo se ilumina una tecla por nota (la más central)
  * La nota original permanece en rojo al añadir notas adicionales
  * Acorde seleccionado marcado en verde en la lista

📋 NOMBRES ALTERNATIVOS:
- Los acordes ahora muestran nombres alternativos entre paréntesis
- Ejemplo: "Cm (Cmin, C-)" muestra todas las formas válidas
- Nombres alternativos en peso normal para mejor legibilidad
- Solo se muestra el nombre principal en la lista de "Otros Acordes"

🎨 MEJORAS DE INTERFAZ:
- Modal compacto de "Otros Acordes" que no oculta el piano
- Sin desenfoque del fondo para ver las teclas iluminadas
- Diseño optimizado con tamaño reducido
- Scrollbar personalizado para mejor UX
- Responsive en dispositivos móviles

📚 DOCUMENTACIÓN:
- Modal de ayuda actualizado con la nueva funcionalidad
- Mensajes informativos cuando se selecciona una sola nota
- Guía completa de uso de "Otros Acordes"

VERSIÓN 1.1.0
-------------
✨ NUEVAS CARACTERÍSTICAS:
- Sistema de notación musical seleccionable:
  * Notación italiana (Do, Re, Mi, Fa, Sol, La, Si)
  * Notación anglosajona (C, D, E, F, G, A, B)
  * Cambio dinámico con botón "🎵 Do#, Mib" / "🎵 C#, Eb"
  * Todas las etiquetas del piano se actualizan automáticamente
  * Los nombres de acordes se adaptan a la notación seleccionada
  
- Interfaz multiidioma (Español/Inglés):
  * Cambio de idioma con botón de bandera (🇪🇸/🇬🇧)
  * Traducción completa de todos los textos de la interfaz
  * Base de datos de información de acordes traducida al español
  * Modal de ayuda completamente traducido
  * Notación musical independiente del idioma de interfaz
  
- Configuración por defecto:
  * Idioma: Español
  * Notación: Italiana (Do, Re, Mi)

🎨 MEJORAS DE DISEÑO:
- Botones de control alineados en el header
- Diseño responsive mejorado para móviles
- Actualización de emojis y textos descriptivos

VERSIÓN 1.0.0
-------------
- Identificación automática de acordes
- Información detallada de cada acorde
- Recursos externos integrados (IA, diagramas, Wikipedia)
- Interfaz intuitiva y responsive
- Base de datos completa de acordes comunes
