# Bruno

Bruno reúne **21 herramientas** para estudiar, practicar, calcular, jugar y entretenerse, todas en un mismo sitio, con el mismo menú y el mismo aspecto. No hace falta instalar nada ni crear una cuenta.



## Qué puedes hacer

| | |
|---|---|
| **Estudiar** | Apuntar tu horario, tus entregas y tus exámenes; guardar notas; escribir con formato y dibujar en una pizarra. |
| **Practicar** | Entrenar verbos irregulares, «porque / porqué» y modalidades oracionales, y **crear tus propios ejercicios** para convertirlos en herramientas nuevas. |
| **Mates y tiempo** | Calcular con una calculadora científica, convertir unidades, y usar un reloj con temporizador, cronómetro y zonas horarias. |
| **Juegos** | Jugar al ajedrez, al parchís, al UNO, a Snake, a Fruit Merge y más, solo o con amigos en el mismo dispositivo. |
| **Vídeo y búsqueda** | Ver los vídeos de tu equipo y buscar en Google o DuckDuckGo desde un mismo cuadro. |
| **Personalizar** | Poner tu nombre, elegir entre seis estilos visuales, tema claro u oscuro, y ajustar la barra lateral y el sonido. |

Tus datos se guardan en tu propio navegador: no hay cuentas ni servidores.

---

## Cómo abrirla

Abre la dirección de la web en tu navegador (Chrome, Edge, Firefox o Safari, en una versión reciente). Si tienes el proyecto descargado en tu ordenador, abre el archivo `index.html`.

<details>
<summary><b>Si los ajustes no se mantienen al cambiar de herramienta</b></summary>

Tus preferencias y tus datos se guardan en el almacenamiento del navegador, que solo se comparte entre páginas del mismo origen. Al abrir los archivos con doble clic, algunos navegadores tratan cada archivo como un sitio distinto, y entonces el tema, tu nombre o tus herramientas propias no pasan de una página a otra.

La solución es abrir la web a través de un servidor local. Desde la carpeta del proyecto, ejecuta:

```
python3 -m http.server 8000
```

y abre en el navegador la dirección `localhost:8000`.
</details>

---

## Conocer la pantalla

- **Menú lateral.** Lista todas las herramientas por categoría. La que tienes abierta aparece resaltada; pulsa cualquiera para abrirla.
- **Tu nombre, arriba del menú.** Al pulsarlo se abre la página de personalización.
- **En el móvil**, el menú se oculta: ábrelo con el botón de las tres rayas de la barra superior.
- **Inicio** reúne un saludo según la hora, un reloj, un buscador, un panel «Hoy» (tus clases, tu agenda y tus notas favoritas) y una tarjeta por cada herramienta.

> Cada herramienta se abre en su propia página. Lo que solo estaba en pantalla y no se guarda —un temporizador en marcha, un dibujo de la Pizarra sin descargar, una partida empezada o la lista de vídeos de BrunoTube— se pierde al cambiar de herramienta.

---

## Personalizar la web

Pulsa tu nombre en la parte superior del menú. Los cambios se aplican al momento y se recuerdan en todas las herramientas.

| Ajuste | Qué hace |
|---|---|
| **Nombre** | Aparece en el saludo, en el menú y en el título de la pestaña. |
| **Tema** | Claro, oscuro, o el de tu dispositivo. |
| **Estilo** | Cambia los colores y el aspecto de toda la web. Hay seis: **Index** (cuaderno cuadriculado con amarillo subrayador), **Board** (escritorio limpio con acento verde azulado), **Caramelo** (rojo y dorado), **Pastel** (rosa con turquesa), **Bosque** (verdes y tierra) y **Océano** (azules con un toque de naranja). |
| **Barra lateral** | Fija; contraída (solo iconos); o contraída y se abre al pasar el cursor. |
| **Sonido** | Activa o desactiva el sonido al pulsar botones. |

![La misma herramienta en tres estilos distintos](capturas/estilos.png)

---

## Las herramientas

### Estudiar

**Horario.** Apunta tus clases por día y hora: escribe la asignatura, elige el día y la hora, y pulsa *Añadir clase*. *Solo hoy* muestra únicamente las de hoy, y el cuadro de búsqueda filtra por asignatura o día. Puedes exportar el horario e importar uno desde un archivo (JSON o CSV). Inicio muestra tus clases de hoy.

**Calendario.** Marca exámenes, entregas y planes. Pulsa un día del mes, escribe el nombre del evento, elige su color y pulsa *Añadir evento*. Con las flechas cambias de mes y con *Hoy* vuelves al día actual. Cada evento se puede eliminar, y puedes exportar el calendario. Inicio muestra tu agenda de hoy.

**Notas.** Tareas y apuntes rápidos: escribe un título y el contenido, elige un color y pulsa *Guardar nota*. Marca una nota como favorita para tenerla a mano en la pestaña *Favoritas*, busca entre ellas y ordénalas por fecha o por título. Puedes exportar e importar una copia.

**Board.** Una nota rápida con formato que **se guarda sola** mientras escribes. Permite cambiar el tipo de letra, el tamaño, el color y el resaltado; negrita (`Ctrl+B`), cursiva (`Ctrl+I`), subrayado (`Ctrl+U`) y tachado; listas, alineación, deshacer (`Ctrl+Z`) y rehacer (`Ctrl+Y`). Puedes ver la nota como código HTML o como texto plano, y vaciarla.

**Pizarra.** Dibuja y descarga tu pizarra como imagen PNG. Tiene lápiz, goma, rellenar, línea, cuadrado y círculo (con o sin relleno), doce colores o uno a tu elección, grosor del trazo, tamaño de pizarra ajustable, deshacer y rehacer, y *Borrar todo*. Escribe un nombre y pulsa *Descargar imagen*. **El dibujo no se guarda al salir: descárgalo antes.**

### Practicar

Las tres primeras herramientas de esta categoría funcionan igual:

- Puedes **elegir la respuesta entre varias opciones** o **escribirla**.
- *Marcar pregunta* guarda una pregunta para repasarla, y *Ver marcadas* muestra solo esas.
- *Siguiente* pasa a la siguiente pregunta y *Empezar de nuevo* reinicia el progreso.
- En las pestañas de clasificar eliges la categoría de cada frase y pulsas *Corregir*; *Nuevas frases* trae otras.
- **Tu progreso se guarda** en el navegador.

**Verbos irregulares.** 240 frases y una tabla de 119 verbos irregulares en inglés. Tiene cuatro pestañas: *Practicar frases* (completa el hueco), *Clasificar frases* (indica si usa el pasado simple o el participio), *Tabla completa* (consulta y busca verbos) y *Practicar tabla* (rellena las columnas ocultas y pulsa *Comprobar tabla*).

**Porque, porqué, por que, por qué.** 75 frases para elegir la forma correcta, una a una (*Paso a paso*) o de tres en tres (*Tres a la vez*), con una guía rápida del significado de cada forma.

**Modalidades oracionales.** 731 frases para identificar su modalidad (enunciativa, interrogativa, exclamativa, exhortativa, dubitativa o desiderativa), de tres en tres.

**Creador de ejercicios.** Crea tus propios ejercicios y publícalos como herramientas. Se explica más abajo, en *Crear tus propias herramientas*.

### Mates y tiempo

**Calculadora.** Tiene dos pestañas.
- *Calculadora*: científica, con funciones trigonométricas y sus inversas, logaritmos, raíces, potencias, factorial, valor absoluto y resto. El botón **DEG** alterna entre grados y radianes y **Ans** recupera el último resultado. Incluye memoria (`MC`, `MR`, `M+`, `M−`, `MS`) y un historial de operaciones. Puedes escribir con el teclado (números, `+ - * / ( ) % ^ !`) y calcular con `Intro` o `=`.
- *Conversor de unidades*: longitud, peso, volumen, velocidad, tiempo, área, datos digitales y temperatura.

**Reloj.** Tiene cuatro pestañas: *Reloj* (hora y fecha, formato de 12 o 24 horas y pantalla completa), *Temporizador* (tiempos rápidos de 1, 5, 10 o 25 minutos, o los minutos y segundos que quieras, con alarma al terminar), *Cronómetro* (con vueltas) y *Zonas horarias* (añade ciudades de una lista de 27). Con `Espacio` inicias o pausas el temporizador o el cronómetro, y con `F` pasas a pantalla completa.

### Juegos

Los juegos para varias personas se juegan **en el mismo dispositivo**.

**Adivina el número.** La máquina piensa un número del 1 al 100. Escribe el tuyo y te dice si es mayor o menor, y va estrechando el rango. Se guarda tu mejor marca (menos intentos).

**Tres en raya.** Juega entre dos personas o contra la máquina. Un marcador cuenta las victorias y los empates.

**Ajedrez.** Dos jugadores o contra la máquina. Pulsa una pieza para ver sus movimientos legales y después la casilla de destino. Incluye enroque, captura al paso, coronación, jaque, jaque mate y ahogado, y puedes deshacer jugadas.

**Snake.** Muévete con las flechas o con `W A S D`; en pantalla táctil, desliza sobre el tablero. `Espacio` pausa y reanuda. Se guarda tu récord.

**Fruit Merge.** Deja caer frutas y junta dos iguales para fusionarlas en una mayor. Mueve el ratón o el dedo, o usa las flechas, y suelta con un clic, un toque o `Espacio`. Puedes pausar y deshacer. Se guarda tu récord.

**Parchís.** De 2 a 4 jugadores, con casillas seguras y capturas. Tira el dado en tu turno y mueve una ficha.

**UNO.** De 2 a 4 jugadores pasándose el mismo dispositivo. Cada jugador ve sus cartas solo en su turno. Juega una carta del mismo color, número o símbolo que la de la mesa; si no puedes, roba una. Gana quien se quede sin cartas.

**El Tapete.** Una sala con cuatro juegos de cartas que eliges con las pestañas:

| Juego | Cómo se juega |
|---|---|
| **Blackjack** | De 1 a 5 asientos. Apuesta con fichas de 5, 25 o 100 y llega a 21 sin pasarte antes que la banca. El blackjack paga 3 a 2. |
| **Tute** | Dos asientos, baraja española. Bazas, cantes y cambio del siete. |
| **Póker** | Texas Hold'em de 2 a 6 asientos, con ciegas, *all-in* y botes laterales. |
| **Solitario** | Klondike con deshacer. Doble clic sube cartas a los montones y puedes robar de 1 o de 3. |

En Blackjack, Tute y Póker, **cada asiento puede ser una persona o la máquina**: puedes jugar contra la IA, con amigos o mezclando ambos. Las fichas son de mentira y no se guardan. Cada mesa tiene su apartado *Reglas de esta mesa*.

![Una mesa de Blackjack en El Tapete](capturas/el-tapete.png)

### Vídeo y búsqueda

**BrunoTube.** Reproduce **vídeos de tu equipo** sin subirlos a internet. Pulsa *Seleccionar vídeos* (o arrástralos a la ventana) y se forma una lista; con *Añadir vídeos* sumas más. Tiene anterior, siguiente, repetir, imagen en imagen y velocidad de 0,5× a 2×.

| Tecla | Acción |
|---|---|
| `Espacio` o `K` | Reproducir / pausar |
| `←` / `→` | Retroceder / avanzar 5 segundos |
| `J` / `L` | Retroceder / avanzar 10 segundos |
| `N` / `P` | Siguiente / anterior |
| `M` | Silenciar |
| `F` | Pantalla completa |

La lista de vídeos no se conserva al salir, pero sí se recuerdan la velocidad y el volumen.

**Buscador.** Busca con Google o DuckDuckGo desde un mismo cuadro; el motor que elijas se recuerda. Escribe `/maps` seguido de un lugar para abrirlo en Google Maps.

---

## Crear tus propias herramientas

En **Practicar → Creador de ejercicios** escribes un ejercicio y lo añades a la web como una herramienta más, con su nombre, su icono y su propia entrada en el menú y en Inicio.

### 1. Escribe el ejercicio

En la pestaña *Crear ejercicio* hay un ejemplo (*Capitales de Europa*) que puedes editar o sustituir. Pon un título y, si quieres, una descripción. Cada pregunta tiene estos campos:

| Campo | Para qué sirve |
|---|---|
| **Frase o pregunta** | Usa `___` (tres guiones bajos) para marcar el hueco, o escribe una pregunta directa. |
| **Respuesta correcta** | La respuesta que se espera. |
| **Otras respuestas válidas** *(opcional)* | Variantes que también se aceptan, separadas por comas. |
| **Opciones incorrectas** *(opcional)* | Si las añades, se podrá **elegir** entre ellas; si no, la respuesta se **escribe**. |
| **Pista** *(opcional)* | Una ayuda que se muestra con la pregunta. |
| **Categoría** *(opcional)* | Con categorías se activa la pestaña de clasificar. |
| **Explicación** *(opcional)* | Se muestra al corregir. |

Con *Añadir pregunta* creas otra, y cada una se puede duplicar o eliminar. Si añades una **tabla de referencia**, se activan las pestañas para consultarla y practicarla; para aceptar varias respuestas en una celda, sepáralas con `/` (por ejemplo, `was / were`). Pulsa *Aplicar y practicar* para probar el ejercicio.

### 2. Ponle nombre e icono

En la tarjeta **Añadir a la web como herramienta**, escribe el nombre (hasta 40 caracteres), elige el icono y pulsa *Añadir a la web*. La herramienta aparece al momento en el menú (dentro de *Practicar*) y como tarjeta en Inicio.

### 3. Dibuja el icono

Pulsa *Dibujar o elegir…*:

1. Dibuja en el cuadro con el ratón, el dedo o un lápiz. Puedes hacer varios trazos.
2. Al soltar, el dibujo **se corrige solo**: las rectas quedan rectas, las esquinas afiladas, los círculos y rectángulos se reconocen, las curvas se suavizan y los extremos que casi se tocan se unen. Tu trazo original se ve en gris debajo del resultado.
3. A la derecha ves el icono grande y **tal como quedará en el menú**.
4. Ajusta lo que quieras: el deslizador **Corrección** (de *Suave* a *Fuerte*) y los interruptores de reconocer círculos y rectángulos, alinear rectas, unir extremos y mostrar tu trazo original.
5. *Deshacer trazo* quita el último trazo y *Borrar todo* empieza de cero. *Ver y copiar el SVG* te da el icono como archivo `.svg`.
6. Pulsa *Usar este icono*.

Si prefieres no dibujar, la pestaña *Elegir de la lista* ofrece una colección de iconos ya hechos.

> **Consejo.** Dibuja formas sencillas y grandes, de uno o dos trazos. Los iconos se ven pequeños en el menú y los detalles finos no se aprecian.

![El editor de iconos: el dibujo se corrige al soltar el trazo](capturas/editor-iconos.png)

![La herramienta aparece en el menú con su icono](capturas/mis-herramientas.png)

### 4. Gestiona tus herramientas

La pestaña **Mis herramientas** muestra todo lo que has publicado. Para cada una puedes:

- **Abrir** la herramienta.
- **Editar**: la carga en el editor. Mientras la editas, *Aplicar y practicar* también guarda los cambios en ella.
- **Exportar**: descarga un archivo con el nombre, el icono y el ejercicio.
- **Eliminar**: la borra (pide una segunda pulsación para confirmar) y desaparece del menú y de Inicio.

Con *Nueva herramienta* empiezas otra en blanco, y con *Importar…* añades una herramienta desde un archivo exportado.

> Las herramientas propias **se guardan en el navegador donde las creas**. Para llevarlas a otro navegador o dispositivo, expórtalas y vuelve a importarlas allí.

---

## Tus datos y copias de seguridad

No hay cuentas ni servidor: todo se guarda en el navegador. Por eso **los datos no viajan** entre navegadores ni dispositivos, y **borrar los datos del sitio, usar otro navegador o una ventana privada los pierde**.

| Qué | Cómo hacer copia |
|---|---|
| Horario | Exportar (JSON o CSV) |
| Calendario | Exportar |
| Notas | Exportar copia |
| Board | Copiar el texto |
| Herramientas propias | Exportar desde *Mis herramientas* |
| Preferencias, récords y progreso de los ejercicios | No necesitan copia: se vuelven a elegir o a conseguir |
| **Pizarra** | **No se guarda:** descarga la imagen |
| **Lista de BrunoTube** | **No se guarda** |

---

## Problemas frecuentes

| Problema | Solución |
|---|---|
| El tema, mi nombre o mis herramientas no pasan de una herramienta a otra. | Estás abriendo los archivos con doble clic. Ábrela con un servidor local (mira *Cómo abrirla*). |
| He perdido mis datos o mis herramientas. | Se guardan en el navegador: cambiar de navegador, borrar los datos del sitio o usar una ventana privada los elimina. Restáuralos importando una copia. |
| Una herramienta propia dice «Esta herramienta no existe aquí». | Se creó en otro navegador o se eliminó. Impórtala desde *Mis herramientas*. |
| El icono dibujado no sale como esperaba. | Sube el deslizador *Corrección*, o dibuja formas más sencillas y grandes. Con *Mostrar mi trazo original* ves la diferencia. |
| Una herramienta muestra «No se ha podido cargar». | Recarga la página. |
| La letra se ve distinta a las capturas. | Las tipografías se descargan de internet. Sin conexión se usan otras de reserva; todo funciona igual. |
| El menú no se ve en el móvil. | Pulsa el botón de las tres rayas de la barra superior. |

---

## Privacidad

No hay cuentas, analíticas ni cookies. Tus datos se quedan en tu navegador. BrunoTube reproduce los vídeos de tu equipo sin subirlos. El *Buscador* abre Google o DuckDuckGo en el navegador: es lo único que sale de tu equipo, y solo cuando buscas.

---

## Créditos

Creado por Bruno Iglesias Cal. Para hacerlo me apoyé en tutoriales y en herramientas de inteligencia artificial.
