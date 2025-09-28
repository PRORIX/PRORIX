### PRORIX: Estudiante de 2º DAM · Desarrollo de Aplicaciones Multiplataforma


---

## Índice

1. [Sobre mí](#sobre-mí)
2. [Habilidades técnicas](#habilidades-técnicas)
3. [Formación actual](#formación-actual)
4. [Proyectos destacados](#proyectos-destacados)
5. [Experiencia](#experiencia)
6. [Cómo ejecutar / probar mis proyectos](#cómo-ejecutar--probar-mis-proyectos)
7. [Objetivos y motivación](#objetivos-y-motivación)
8. [Colaboraciones y contacto](#colaboraciones-y-contacto)
9. [Licencia](#licencia)

---

## Sobre mí

Soy estudiante de **2º curso de Desarrollo de Aplicaciones Multiplataforma (DAM)**. Me apasiona la programación y la ingeniería del software. Me considero una persona **perfeccionista**, con mentalidad de mejora continua: aprendo cada día para entregar código limpio, mantenible y bien documentado.

**Resumen breve**

* Perfil: estudiante de 2º DAM con experiencia en proyectos completos (escritorio y web).
* Actitud: orientado al detalle, responsable y con ganas de aprender y aportar.
* Disponibilidad: abierto a prácticas, colaboraciones y ofertas de empleo junior (he realizado prácticas fuera de España).

---

## Habilidades técnicas

**Lenguajes**

* Java (sólido — proyectos con JavaFX).
* PHP (en aprendizaje y uso en proyectos web).
* SQL / MySQL (consultas avanzadas, joins y modelado relacional).
* JavaScript, HTML, CSS (front-end básico y dinamización).
* SQLite (proyectos locales ligeros, por ejemplo juegos).

**Frameworks / Librerías / Herramientas**

* JavaFX — interfaces gráficas de escritorio.
* Maven / Gradle — gestión de proyectos Java.
* Git / GitHub — control de versiones y flujo de trabajo colaborativo.
* SQLite, MySQL — gestión de datos en proyectos según necesidades.
* Herramientas: Visual Studio Code, IntelliJ IDEA (según proyecto).

**Competencias blandas**

* Perfeccionismo aplicado a la calidad del código.
* Aprendizaje continuo y adaptabilidad.
* Trabajo en equipo y capacidad para recibir/aceptar feedback.

---

## Formación actual

* **Ciclo Formativo de Grado Superior — Desarrollo de Aplicaciones Multiplataforma (2º curso)**.
  Contenidos principales: programación en Java, bases de datos, desarrollo web (PHP, HTML, JS), interfaces gráficas, y buenas prácticas de ingeniería del software.

---

## Proyectos destacados

> A continuación un resumen de proyectos realizados (en este repositorio o en repositorios asociados). Cada proyecto incluye tecnología principal y un breve resumen.

### 1. **Gusanoguason** — Juego del gusano (Snake)

* **Tecnologías:** Java, JavaFX, SQLite.
* **Descripción:** Juego del gusano con sistema de login/registro (SQLite), perfiles de usuario y sistema de puntuación. Interfaz creada con JavaFX y persistencia local.
* **Estado:** Funcional (pantalla de juego, perfil, registro, puntuación).

### 2. **CRIM Shop** — Tienda online simulada

* **Tecnologías:** Java, JavaFX, SQLite (simulación de pasarela de pago).
* **Descripción:** Tienda online de ejemplo con gestión de productos, carrito, simulación de pagos y panel de administración. Pensada como proyecto de aprendizaje para integrar front y back sin depender de APIs externas reales.
* **Estado:** Completa (simulada), preparada para ampliarse con integración web si se desea.

### 3. **Bot para Discord (dynamización de streams)**

* **Tecnologías:** Python (o Node.js según versión), Discord API.
* **Descripción:** Bot que automatiza mensajes y funciones para dinamizar streams en Twitch; incluye comandos personalizados y gestión básica de interacción.

### 4. **Proyectos adicionales / prácticas**

* Scripts de scraping y procesamiento de datos (proyecto académico).
* Pequeños proyectos web en PHP + MySQL para practicar autenticación y CRUD.

> En cada proyecto intento mantener: estructura clara del repositorio, README por proyecto, instrucciones de ejecución y pruebas básicas.

---

## Experiencia

* **Prácticas en empresa fuera de España** — experiencia en entorno laboral real; tareas relacionadas con desarrollo y mantenimiento de aplicaciones.
* Proyectos personales y colaborativos realizados durante el ciclo formativo y fuera de él (ver carpetas de cada proyecto en este perfil).

---

## Cómo ejecutar / probar mis proyectos

Cada proyecto incluye su propio README con instrucciones detalladas; aquí hay comandos y pasos generales para probar ejemplos típicos:

### Proyectos Java / JavaFX

```bash
# Con Maven (si el proyecto usa Maven + plugin javafx)
mvn clean javafx:run
```

Asegúrate de tener la versión de JDK compatible instalada (por ejemplo JDK 11+ según el proyecto).

### Proyectos PHP + MySQL

```bash
# Levantar servidor PHP simple (para pruebas)
php -S localhost:8000 -t public/

# Importar base de datos (MySQL)
mysql -u usuario -p nombre_basedatos < dump.sql
```

Configura las credenciales en el archivo de configuración del proyecto antes de ejecutar.

### Proyectos con SQLite (juegos o apps locales)

* Normalmente basta con ejecutar la aplicación Java; la DB suele estar en `src/main/resources/Usuarios.db` o en la ruta indicada en el README del proyecto.
* Si necesitas inspeccionar la DB:

```bash
sqlite3 src/main/resources/Usuarios.db
.tables
```

---

## Objetivos y motivación

* Consolidar conocimientos en **Java** y ampliar experiencia en **desarrollo web (PHP, JS)**.
* Crear proyectos que demuestren buenas prácticas (estructura, pruebas mínimas, documentación).
* Aspiración a entrar en prácticas o puesto junior donde aportar y seguir aprendiendo cada día.

---

## Colaboraciones y contacto

Estoy abierto a colaboraciones, propuestas de prácticas y ofertas junior. Para contactar prefiero que lo hagas a través de mi perfil de GitHub (abrir un *issue* en este repositorio) o mediante correo electrónico.

**Contacto:**

* Email: `romengilberto08@gmail.com`

También puedes abrir un *issue* en cualquiera de los repositorios para consultarme detalles sobre código, arquitectura o propuestas concretas.

---

## Buenas prácticas en este perfil

* Cada proyecto incluye su propio `README.md` con:

  * Objetivo y tecnologías.
  * Pasos para ejecutar.
  * Estructura de carpetas.
  * Notas sobre dependencias y versiones.
* Uso de branches para features y `main`/`master` para código estable.

---

## Licencia

Este README y los proyectos en este perfil usan, por defecto, la **licencia MIT** (si no se indica otra). Revisa cada repositorio individual para confirmar la licencia específica.
