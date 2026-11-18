# 6. ARQUITECTURA DE INFORMACIÓN Y FLUJO DE USUARIO

Responsable: Valentina González

## 6.1. Mapa de contenidos
La arquitectura organiza al Blackboard en tres niveles. El botón “Aa” está en el primero, de manera visible, para que cualquier función quede a un máximo de dos clics (RNF1). El segundo nivel es el panel de accesibilidad, que se abre desde cualquier página. El tercero reúne las funciones que se usan en el lugar donde se necesitan: el botón “Escuchar” en la página de lectura, el micrófono en los campos de texto y la lupa en el contenido de la clase en vivo.

*(Insertar Figura 4: Mapa de contenidos del panel de accesibilidad)*

## 6.2. Etiquetas principales
Para cumplir con RNF5 (usarse sin capacitación previa), las etiquetas son cortas, están en español cotidiano y siempre acompañan al ícono, de modo que el usuario no tiene que interpretar solo el dibujo.

| Elemento | Etiqueta | Ícono | Por qué |
| :--- | :--- | :--- | :--- |
| Botón del panel | Accesibilidad | Aa | “Aa” se reconoce como texto y la palabra evita dudas. |
| Modo oscuro | Modo oscuro | Luna | Mismo nombre que en el celular. |
| Tamaño de letra | Tamaño de letra | A− / A+ | Igual que en lectores digitales y navegadores. |
| Lectura en voz alta | Escuchar | Parlante o ícono de triángulo | Verbo simple, como en los podcasts. |
| Dictado | Dictar | Micrófono | Igual que el teclado del celular. |
| Zoom en clase | Ampliar | Lupa + | Se asocia al pellizco que ya conoce. |
| Reinicio | Restablecer | Flecha circular | Permite volver atrás sin miedo. |

## 6.3. Navegación
*   **Barra superior global y fija:** “Aa” está siempre en el mismo lugar, sin importar la página (RNF1, RNF5).
*   **Adaptación al dispositivo:** en el notebook el panel se abre como menú lateral que no tapa el contenido; en el celular, como una hoja desde abajo, alcanzable con el pulgar.
*   **Mini-reproductor flotante:** al cerrar el panel, la lectura continúa y los controles de pausa y velocidad siguen visibles.
*   **Ubicación:** migas de pan (Cursos > Curso > Unidad) para saber dónde se está.
*   **Salida fácil:** el panel se cierra con X, tocando fuera de él o con la tecla Esc, y “Restablecer” devuelve todo a la apariencia original.
*   **Funciones en el lugar de uso:** el micrófono aparece en cada campo de texto y la lupa en el contenido de Collaborate, para no obligar a buscarlas en el panel.

## 6.4. Flujo de usuario de la tarea principal
El flujo corresponde a la tarea principal definida en la sección de requisitos: leer y comprender el material escrito de un curso, ajustando la interfaz a las necesidades del estudiante. Se recorre con la persona Camila, que estudia de noche después del trabajo.

| Paso | Acción de Camila | Respuesta del sistema | Clics |
| :--- | :--- | :--- | :--- |
| 1 | Entra al curso | Muestra el curso con “Aa” visible | – |
| 2 | Abre el contenido | Muestra la página de lectura | – |
| 3 | Selecciona "Aa" | Abre el panel sin salir de la página | 1 |
| 4 | Activa modo oscuro o cambia la letra | Aplica el cambio al instante y marca el estado | 2 |
| 5 | Selecciona "Escuchar" | Lee el texto y lo resalta | 2 |
| 6 | Pausa o cambia la velocidad | Responde desde el mini-reproductor | 1 |
| 7 | Vuelve a leer con la vista | Detiene la lectura y guarda los ajustes | 1 |

Con este diseño, cada función cumple RNF1, ya que se alcanza como máximo en el segundo toque desde cualquier página.

*(Insertar Figura 5: Flujo de usuario de la tarea principal)*
