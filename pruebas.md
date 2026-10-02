# Pruebas locales (paso 4)

Realizadas con Chromium automatizado sobre `index.html` el 30-09-2026. Repita las pruebas manuales en un teléfono real.

| Prueba | Resultado | Estado |
|---|---|---|
| Teléfono 375 px y 320 px | Ancho del documento igual al de la pantalla; sin desplazamiento lateral. El cronograma es una línea de tiempo vertical | Correcto |
| Texto al 200 % (emulado con pantalla de 188 px) | Sin desplazamiento lateral; la única tabla (evaluación) se desplaza dentro de su propio recuadro | Correcto (se corrigieron 4 desbordes en la primera ronda) |
| Solo teclado | Orden: saltar al contenido, menú, próxima actividad y sus botones, simulador de fecha, tres accesos, cronograma, lecturas, lista, contacto. Foco visible en amarillo | Correcto |
| Lista de tareas | La marca persiste al recargar; «Desmarcar todo» la reinicia; si se borra el almacenamiento se reinicia sin error | Correcto |
| Próxima actividad por fecha | 28-04-2026 → Semana 4 + foro abierto; 30-09-2026 → «Las semanas 1 a 4 terminaron» | Correcto |
| Errores de JavaScript | Ninguno | Correcto |
| Enlaces externos (Laudon, CISSP, Prezi, YouTube) | Pendiente de comprobar desde una red con acceso; Laudon y CISSP piden la cuenta UTPL | Pendiente |
| Modo oscuro | Colores redefinidos con `prefers-color-scheme` | Revisar en teléfono |

## Prueba con un colega (guía 21)
Pida a un colega que, desde su teléfono, encuentre la lectura de la semana 2 en menos de 30 segundos. Anote el tiempo aquí: ______
Para probar otra fecha sin esperar: añada `?fecha=2026-04-15` a la dirección o use «Ver el sitio en otra fecha».
