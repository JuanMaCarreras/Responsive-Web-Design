#### 1. Estructura y Contenido Principal

    El contenido principal de la página debe estar dentro de un elemento main con el id="main-doc".

#### 2. Secciones de Documentación Técnica

    Dentro del elemento #main-doc, deben haber varios elementos section, cada uno con la clase main-section. Debe haber un mínimo de cinco secciones.

#### 3. Encabezado de Cada Sección

    El primer elemento dentro de cada .main-section debe ser un elemento header que contenga texto describiendo el tema de esa sección.

#### 4. Identificadores de Sección Correspondientes

    Cada elemento section con la clase main-section también debe tener un id que corresponda con el texto de cada encabezado contenido en él. Cualquier espacio debe ser reemplazado con guiones bajos (por ejemplo, la sección que contiene el encabezado "JavaScript and Java" debe tener un id="JavaScript_and_Java").

#### 5. Párrafos en las Secciones

    Los elementos .main-section deben contener al menos diez elementos p en total (no cada uno).

#### 6. Elementos de Código en las Secciones

    Los elementos .main-section deben contener al menos cinco elementos code en total (no cada uno).

#### 7. Elementos de Lista en las Secciones

    Los elementos .main-section deben contener al menos cinco elementos li en total (no cada uno).

#### 8. Barra de Navegación

    Debe haber un elemento nav con el id="navbar".

#### 9. Encabezado en la Barra de Navegación

    El elemento de la barra de navegación debe contener un elemento header que contenga texto describiendo el tema de la documentación técnica.

#### 10. Enlaces en la Barra de Navegación

    Adicionalmente, la barra de navegación debe contener elementos a con la clase nav-link. Debe haber uno para cada elemento con la clase main-section.

#### 11. Orden de los Elementos en la Barra de Navegación

    El elemento header en el #navbar debe venir antes de cualquier elemento a en la barra de navegación.

#### 12. Texto de los Enlaces de Navegación

    Cada elemento con la clase nav-link debe contener texto que corresponda al texto del encabezado dentro de cada sección (por ejemplo, si tienes una sección/encabezado "Hello world", tu barra de navegación debe tener un elemento que contenga el texto "Hello world").

#### 13. Navegación al Hacer Clic en los Enlaces

    Cuando haces clic en un elemento de la barra de navegación, la página debe navegar a la sección correspondiente del elemento #main-doc (por ejemplo, si haces clic en un elemento .nav-link que contiene el texto "Hello world", la página debe navegar a un elemento section con ese id y que contiene el encabezado correspondiente).

#### 14. Visibilidad de la Barra de Navegación

    En dispositivos de tamaño regular (laptops, desktops), el elemento con id="navbar" debe mostrarse en el lado izquierdo de la pantalla y debe estar siempre visible para el usuario.

#### 15. Uso de Media Queries

    Tu documentación técnica debe usar al menos una media query.
