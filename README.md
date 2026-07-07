# <img src="https://static.wikia.nocookie.net/megamitensei/images/f/fe/Persona_4_Logo_White.png/revision/latest?cb=20210606140945" width="36" height="36" align="top" style="border-radius: 4px;"> Hardcore Risette Fan — P4G Tracker

![Persona 4 Golden](https://img.shields.io/badge/Persona%204%20Golden-Hardcore%20Risette%20Fan-F5C400?style=for-the-badge&labelColor=0D0D0D&logo=sega&logoColor=F5C400)
![HTML5 & CSS3 & JS](https://img.shields.io/badge/Tech-Vanilla%20HTML%2FCSS%2FJS-3D3D3D?style=for-the-badge&labelColor=1A1A1A)
![License CC BY--NC 4.0](https://img.shields.io/badge/Licencia-Uso%20Libre%20(CC%20BY--NC%204.0)-E53935?style=for-the-badge&labelColor=0D0D0D)
![Price Free](https://img.shields.io/badge/Precio-100%25%20Gratuito-72cc18?style=for-the-badge&labelColor=0D0D0D)

Una herramienta web interactiva, moderna y completamente bilingüe (Español / Inglés) diseñada para ayudar a los jugadores de **Persona 4 Golden** a conseguir uno de los logros y trofeos más legendarios, exigentes y gratificantes del juego: **"Hardcore Risette Fan"** (*Fanático incondicional de Risette*).

Para obtener este trofeo, es necesario escuchar **250 frases únicas de navegación de combate** pronunciadas por Rise Kujikawa. Esta aplicación te permite llevar un control exhaustivo, rápido y persistente en tiempo real de cada línea que escuches durante tus partidas.

---

## 📑 Tabla de Contenidos

1. [✨ Características Principales](#-características-principales)
2. [🚀 Guía de Uso de la Herramienta](#-guía-de-uso-de-la-herramienta)
3. [⌨️ Atajos de Teclado](#-atajos-de-teclado)
4. [💡 Consejos para Obtener el Logro](#-consejos-para-obtener-el-logro)
5. [🛠️ Tecnologías Utilizadas](#️-tecnologías-utilizadas)
6. [⚖️ Licencia y Términos de Uso (Importante)](#️-licencia-y-términos-de-uso-importante)

---

## ✨ Características Principales

Esta herramienta ha sido diseñada con una estética premium inspirada directamente en la paleta visual y la interfaz de *Persona 4 Golden* (tonos dorados, oscuros y alto contraste), incluyendo todas las funciones necesarias para una experiencia de usuario perfecta:

- 🌐 **Soporte Bilingüe Instantáneo (Español / Inglés):** Cambia el idioma de toda la interfaz y de las cientos de frases de navegación con un solo clic en el botón superior (`EN` / `ES`). Ideal para quienes juegan el título con subtítulos en cualquiera de los dos idiomas.
- 📊 **Contador y Barra de Progreso en Tiempo Real:** Visualiza tu avance exacto (`0 / 250`), porcentaje completado (`%`) y animaciones dinámicas cada vez que marcas una nueva frase.
- 🏆 **Banner de Logro Desbloqueado:** Al alcanzar las 250 frases escuchadas, el sistema despliega una notificación de celebración estilo logro/trofeo en la pantalla.
- 🔍 **Buscador Inteligente con Resaltado:** Busca cualquier palabra o fragmento de frase en tiempo real. La herramienta filtrará las coincidencias y resaltará el texto exacto con un marcador visual (`<mark>`), mostrando el número de resultados encontrados.
- 🎭 **Filtros por Personaje:** Botones dedicados para filtrar las líneas de navegación según el miembro del equipo al que se refieren: **Todos, Protagonista, Yosuke, Chie, Yukiko, Kanji, Teddie, Naoto** u **Otros**. Cada botón utiliza su color temático oficial.
- 📂 **Acordeones Categorizados:** Frases organizadas de forma lógica por situaciones de combate (*Inicio de Batalla, Análisis, Debilidades, Efectos de Estado, Victoria, Huida, etc.*). Cada categoría y subcategoría cuenta con su propio marcador de progreso (ej. `5 / 12`).
- ⚡ **Expansión y Colapso Rápido:** Botones de acceso rápido para **"Expandir Todo"** o **"Colapsar Todo"** para navegar cómodamente por el catálogo completo.
- 💾 **Guardado Automático Local (LocalStorage):** No pierdas tu progreso. Todas las frases marcadas y tu preferencia de idioma se guardan de manera automática y privada en tu navegador.
- 🔄 **Exportación e Importación de Progreso (JSON):**
  - **Exportar:** Descarga tu progreso en un archivo `p4g_rise_progress.json` para hacer copias de seguridad o transferirlo a otro ordenador, móvil o navegador.
  - **Importar:** Sube un archivo de respaldo previamente descargado para restaurar tu partida en segundos.
- 🛡️ **Reinicio Seguro:** Botón para reiniciar el contador con un cuadro de diálogo de confirmación (modal) para evitar borrados accidentales.
- 📱 **100% Responsivo y Táctil:** Diseñado para funcionar de manera fluida y perfecta en ordenadores de escritorio, tabletas y teléfonos móviles, permitiendo usarlo como pantalla de apoyo mientras juegas.

---

## 🚀 Guía de Uso de la Herramienta

La aplicación consta de un único archivo estático ([`index.html`](file:///c:/laragon/www/p4g-risefan250/index.html)), lo que significa que no requiere instalación de programas externos, bases de datos ni conexión a internet para funcionar una vez cargada.

### 1️⃣ Cómo iniciar la herramienta
- **Opción A (Local):** Simplemente haz doble clic sobre el archivo `index.html` para abrirlo en tu navegador web favorito (Google Chrome, Firefox, Edge, Safari, Brave, etc.).
- **Opción B (Servidor Web / Laragon / XAMPP):** Coloca la carpeta en tu directorio web local (`www` o `htdocs`) y accede a través de `http://localhost/p4g-risefan250/`.

### 2️⃣ Cómo llevar el registro durante tu partida
1. **Selecciona tu Idioma:** Asegúrate de que el idioma superior (`EN` o `ES`) coincida con el idioma de los textos de tu videojuego.
2. **Escucha a Rise en Combate:** Durante las batallas en el Canal de Medianoche (TV World), escucha atentamente las líneas de voz y texto de Rise Kujikawa.
3. **Marca la Frase:** Busca la categoría correspondiente (o utiliza el buscador) y haz clic sobre la línea que acabas de escuchar. Verás cómo la casilla se marca con un check dorado (✔), el texto se tacha ligeramente y tu contador principal suma `+1`.
4. **Desmarcar:** Si cometiste un error al marcar una frase, simplemente vuelve a hacer clic sobre ella para desmarcarla.

### 3️⃣ Uso de Filtros y Búsqueda
- Si estás intentando conseguir frases de un estado alterado específico en un personaje (por ejemplo, *Chie con Miedo* o *Yosuke con Pánico*), haz clic en el filtro del personaje en la barra superior (ej. **Chie**) y abre la categoría **"Efectos de Estado"**.
- Si recuerdas una palabra que dijo Rise (como *"debilidad"* o *"sombra"*), escríbela en la barra de búsqueda para encontrar al instante todas las frases que contengan esa palabra.

### 4️⃣ Respaldo y Transferencia de Datos
- **Para crear una copia de seguridad:** Pulsa el botón **`Exportar`**. Se guardará un archivo `.json` en tu carpeta de Descargas.
- **Para pasar tu progreso al móvil u otro PC:** Envía ese archivo `.json` a tu otro dispositivo, entra a la herramienta, pulsa **`Importar`** y selecciona el archivo. Tu contador y casillas marcadas se restaurarán idénticamente.

---

## ⌨️ Atajos de Teclado

| Tecla / Combinación | Acción |
| :--- | :--- |
| `Ctrl + F` (o `Cmd + F` en Mac) | Enfocar directamente la barra de búsqueda para buscar una frase. |
| `Esc` (Escape) | Limpiar el buscador / Cerrar la ventana modal de confirmación de reinicio. |

---

## 💡 Consejos para Obtener el Logro

1. **Rotación del Equipo:** No juegues siempre con los mismos 3 compañeros. Rota constantemente a Yosuke, Chie, Yukiko, Kanji, Teddie y Naoto. Cada uno tiene frases únicas al derrotar enemigos, recibir golpes críticos, caer debilitados o sufrir estados alterados.
2. **Estados Alterados (Status Effects):** Gran parte de las frases provienen de estados negativos (*Veneno, Miedo, Agotamiento, Furia, Pánico, Debilidad, Envejecimiento*). Deja que algunos enemigos inflijan estos estados a tus compañeros para escuchar y registrar las líneas de Rise antes de curarlos.
3. **Niveles Bajos y Altos:** Rise tiene líneas diferentes para cuando los enemigos son más débiles que tu equipo, de nivel similar, o mucho más fuertes. Evita subir excesivamente de nivel muy rápido sin haber explorado mazmorras anteriores.
4. **Análisis y Debilidades:** Al empezar un combate con enemigos nuevos, usa la opción de análisis o golpea sus debilidades para activar las líneas de escaneo de Rise.
5. **No te rindas:** Hay más de 400 líneas de navegación registradas en el juego; ¡solo necesitas 250 de ellas para el trofeo!

---

## 🛠️ Tecnologías Utilizadas

Esta herramienta ha sido construida siguiendo las mejores prácticas de desarrollo web moderno, garantizando máxima velocidad, ligereza y compatibilidad:

- **HTML5 Semántico:** Estructura limpia y accesible con atributos ARIA para lectores de pantalla y notificaciones dinámicas.
- **Vanilla CSS3 (Variables & Flexbox/Grid):** Diseño completamente a medida sin frameworks pesados ni dependencias externas. Uso de variables CSS nativas (`:root`), transiciones suaves y micro-animaciones en interfaz.
- **Vanilla JavaScript (ES6+):** Lógica modular de alto rendimiento para gestión del DOM, filtrado en tiempo real, API de `localStorage` y lectura de archivos locales (`FileReader`).

---

## ⚖️ Licencia y Términos de Uso (Importante)

Este proyecto se distribuye bajo la licencia **Creative Commons Reconocimiento-NoComercial 4.0 Internacional (CC BY-NC 4.0)** y los términos específicos de uso de la comunidad. 

Al descargar, usar, alojar o modificar esta herramienta, aceptas los siguientes puntos de manera vinculante:

### 1. ✅ Uso Libre, Modificación y Adaptación (Permitido)
Cualquier usuario, jugador o desarrollador es libre de:
- **Utilizar** esta herramienta para uso personal o comunitario.
- **Modificar, adaptar, mejorar o bifurcar (fork)** el código fuente (HTML, CSS, JS, o datos de frases) para crear versiones personalizadas, añadir idiomas o integrar nuevas mejoras.
- **Compartir y redistribuir** copias de esta herramienta libremente.

### 2. ✍️ Atribución y Créditos (Obligatorio)
Si redistribuyes, compartes, publicas o modificas este proyecto (en su totalidad o en parte):
- **Es estrictamente obligatorio dar el crédito correspondiente** a los creadores y desarrolladores originales de esta herramienta.
- Debes incluir una mención visible y mantener los avisos de derechos de autor y enlaces al proyecto original en la documentación o en la interfaz de tu versión modificada.
- No puedes atribuirte la autoría exclusiva o creación original de esta herramienta.

### 3. 🚫 Prohibición Total de Venta y Comercialización (Estrictamente Prohibido)
- **ESTE ES UN PRODUCTO DE USO 100% GRATUITO** creado por y para la comunidad de fans de *Persona 4 Golden*.
- **Queda terminantemente prohibido vender, monetizar, comercializar, sublicenciar, cobrar por el acceso o incluir este software (o cualquier modificación derivada de él) dentro de paquetes comerciales de pago o detrás de muros de pago (paywalls).**
- Nadie está autorizado para obtener beneficios económicos o lucrarse directa o indirectamente con esta herramienta bajo ninguna circunstancia.

---

> Para leer el texto legal completo de la licencia y los términos de atribución y uso no comercial, consulta el archivo [`LICENSE`](LICENSE) adjunto en este directorio o visita [Creative Commons CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/deed.es).

---
*Hecho con ❤️ para la comunidad de fans de Persona 4 Golden y Rise Kujikawa.*
