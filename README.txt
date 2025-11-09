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
- Base de datos completa de acordes (mayores, menores, séptimas, etc.)
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

RECURSOS EXTERNOS
----------------
La aplicación incluye enlaces a recursos externos para profundizar:

🎹 PIANO CHORDS
- Enlace directo a pianochord.org
- Diagramas visuales específicos para piano
- URLs en minúsculas (ej: cm7.html)

🤖 PERPLEXITY AI
- Búsqueda inteligente con prompt detallado
- Incluye: características, consejos, progresiones, notaciones alternativas
- Prompt en español optimizado para acordes de piano

🧠 GROK AI
- IA de xAI disponible en X (Twitter)
- Mismo prompt detallado que Perplexity
- Comparación de respuestas entre diferentes IAs

📖 WIKIPEDIA
- Búsqueda académica de artículos musicales
- Encuentra teoría musical, historia y contextos

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
1.1.0

HISTORIAL DE VERSIONES
----------------------

VERSIÓN 1.1.0 (Actual)
---------------------
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

NOTAS PARA VERSIONES FUTURAS

- cuando se pongan tres notas en el piano se activa un boton que ponga "Acordes con estas notas" y al tocae¡rlo aparece en un popup
    todos los acordes que incluyen esas notas. Al pinchar sobre uno de ellos se iluminan en azul las teclas adicionales.

- cuando se pone una sola tecla en el piano y aparece el TExto "Single note" aparece tambien un boton que ponga
 "Acordes basados en esta nota". Si se pulsa aparece un pop up con todos los acordes que tienen essa nota como tonica. Al pulsar cada uno de ellos 
 se iluminan en azul las teclas correspondientes a ese acorde. Si se añade una tecla mas desaparece ese popup

 

