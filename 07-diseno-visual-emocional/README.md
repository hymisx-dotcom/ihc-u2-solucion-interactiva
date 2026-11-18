# 7. DISEÑO VISUAL Y EMOCIONAL

Responsable: Valentina González

Las decisiones visuales responden a la persona (Camila), al contexto de uso (noche, pantalla pequeña, cansancio) y a los requisitos RNF2 (WCAG 2.1 nivel AA) y RNF5.

## 7.1. Jerarquía visual
*   **Una acción principal por vista:** En el panel, el interruptor de modo oscuro y el botón “Escuchar” son lo más grande y destacado; “Restablecer” es secundario y tiene menos peso.
*   **Orden por frecuencia de uso:** Apariencia, luego Escuchar y al final Restablecer.
*   **Agrupación por tarea:** Secciones con espacio y títulos, en vez de una lista larga de opciones.
*   **El contenido manda:** El panel no tapa el texto en el notebook y en el celular se cierra con un gesto.

## 7.2. Legibilidad
*   **Tamaño:** Texto base de 16 px con cuatro niveles (100 %, 125 %, 150 % y 200 %), que cumple RF2 y la ampliación hasta 200 % que pide WCAG 1.4.4.
*   **Espaciado:** Interlineado de 1,5 y líneas de unas 60 a 80 letras, para no cansar la vista en lecturas largas.
*   **Tipografía:** Sans-serif simple, sin cursivas largas ni mayúsculas continuas.
*   **Zonas táctiles:** Botones de al menos 44 × 44 px, útiles para quién tiene un brazo lesionado o usa el celular en movimiento.
*   **Alcance del cambio:** El tamaño de letra modifica solo el texto, no toda la página, para que no se desordenen menús ni tablas.

## 7.3. Colores

| Modo | Fondo | Texto | Botones y enlaces | Contraste texto / fondo | Contraste botones / fondo |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Claro | #FFFFFF | #1A1A1A | #1F3A93 (azul oscuro) | 17,4:1 | 10,1:1 |
| Oscuro | #404040 | #E6E6E6 | #93B7FF (azul claro) | 8,3:1 | 5,2:1 |

WCAG 2.1 nivel AA exige un contraste mínimo de 4,5:1 para texto normal y de 3:1 para texto grande y elementos de interfaz (W3C, 2018). Todas las combinaciones de la paleta lo superan: En modo claro, el texto alcanza 17,4:1 y los botones y enlaces 10,1:1; en modo oscuro, el texto alcanza 8,3:1 y los botones y enlaces 5,2:1. Los valores se calcularon con la fórmula de contraste de WCAG.

Modo oscuro suave: Se utiliza un gris oscuro (#404040) con texto gris claro (#E6E6E6), en lugar de negro puro con blanco puro. Así el contraste sigue siendo alto (8,3:1), pero se reduce el encandilamiento que molesta a Camila de noche.
El color no es el único indicador (WCAG 1.4.1): Los interruptores muestran también el texto “Activado” o “Desactivado”, y el resaltado de lectura se acompaña de subrayado.

## 7.4. Retroalimentación
Se sigue el principio de visibilidad del estado del sistema (Nielsen, 1994), donde el alumno siempre ve el resultado de los cambios que realizó.

| Acción | Retroalimentación |
| :--- | :--- |
| Activar modo oscuro o cambiar la letra | Cambio inmediato en toda la página y estado marcado en el panel. |
| Escuchar | El texto leído se resalta y el botón cambia a "Pausar". |
| Pausar o cambiar velocidad | Indicador de velocidad visible (por ejemplo, "1,5x"). |
| Dictar | Ícono de micrófono animado y texto que aparece mientras habla. |
| Ampliar en Collaborate | Indicador de zoom ("2x") y botón "Restablecer vista". |
| Guardar ajustes | Aviso breve: "Tus ajustes se guardaron correctamente". |
| Error (sin conexión o sin voz) | Mensaje claro con qué hacer: "No pudimos encontrar esta página. Intenta de nuevo" |

## 7.5. Confianza y sensación de control
*   **Todo es reversible:** “Restablecer” y los interruptores permiten volver atrás sin consecuencias.
*   **Nada ocurre solo:** El audio no se reproduce automáticamente y el dictado se revisa y corrige antes de enviar.
*   **El estudiante ve qué cambia:** El zoom afecta solo su vista, y el panel lo indica con el mensaje “Solo tú ves este cambio”.
*   **Previsibilidad:** “Aa” siempre está en el mismo lugar y se comporta igual en computador y celular.
*   **Tono emocional:** Lenguaje neutro y amable, sin términos clínicos como “discapacidad” o “necesidades especiales”. El panel se presenta como una forma de personalizar la plataforma, útil para cualquier estudiante, de modo que nadie se sienta señalado por usarlo.
