## 🚀 Ejercicio 1: Uso de Bucles y Formularios

### Requisito
[cite_start]Desarrollar un script PHP que, a través de un formulario, permita al usuario dibujar un rectángulo de estrellas (`*`) utilizando bucles. [cite: 6]

### Formulario Requerido
[cite_start]El formulario debe solicitar al usuario el alto y el ancho del rectángulo. [cite: 7, 9]

* [cite_start]**Texto a mostrar:** "Escriba el alto y ancho (0 < números < 100) y mostraré un rectángulo de estrellas de ese tamaño" [cite: 9]
* **Campos de entrada:**
    * [cite_start]Ancho: (Campo de texto) [cite: 10]
    * [cite_start]Alto: (Campo de texto) [cite: 11]
* [cite_start]**Botones:** "Dibujar" y "Borrar" [cite: 12]

### Resultado Esperado (Ejemplo)
[cite_start]Si se introducen Alto: **4** y Ancho: **7**, el resultado debe ser un rectángulo de 4 filas y 7 columnas de estrellas. [cite: 14, 15]

---

## 🎲 Ejercicio 2: Uso de Números Aleatorios y Vectores

### Requisito
[cite_start]Crear un programa PHP que simule una confrontación entre dos jugadores lanzando **cinco dados al azar** cada uno. [cite: 26, 31]

### Lógica del Juego
1.  [cite_start]Cada jugador tirará **cinco dados** (simulación de números aleatorios entre 1 y 6). [cite: 31]
2.  Se debe mostrar la tirada individual de cada jugador (simulada con imágenes o valores).
3.  [cite_start]La puntuación de cada jugador se calcula **sumando los valores de sus cinco dados**. [cite: 32]
4.  [cite_start]Se comparan las sumas para determinar quién ha ganado. [cite: 32]
5.  Se debe indicar el resultado final.
    * [cite_start]*Ejemplo de resultado:* "En conjunto, ha ganado el jugador 1." [cite: 30]

---

## 📝 Ejercicio 3: Manejo de Formularios y Ficheros de Texto

### Parte 1: El Formulario (`alumno.html`)
[cite_start]Realizar una página web llamada `alumno.html` que contenga un formulario para la introducción de datos del alumno. [cite: 38, 40]

**Campos Requeridos:**
* [cite_start]**Nombre:** Campo de texto. [cite: 42, 44, 56, 58]
* [cite_start]**Teléfono de Contacto:** Campo de texto. [cite: 50, 63, 64]
* [cite_start]**Enseñanza (Selección Múltiple/Radio):** [cite: 43, 57, 68]
    * [cite_start]Secundaria [cite: 46, 59]
    * [cite_start]Bachillerato [cite: 47, 60]
    * [cite_start]Ciclo Medio [cite: 48, 61]
    * [cite_start]Ciclo Superior [cite: 49, 62]
* [cite_start]**Matriculado (Checkbox/Radio):** Indica si el alumno está actualmente matriculado. [cite: 51, 65, 68]
* [cite_start]**Opción de Mostrar Datos:** (Campo para elegir el destino de los datos) [cite: 52, 66, 69]
    * Por Pantalla
    * En Archivo `datos.txt`
* [cite_start]**Botón de Envío:** "Enviar datos" [cite: 54, 67]

### Parte 2: Procesamiento (`datos_alumno.php`)
[cite_start]Al pulsar "Enviar datos", se cargará la página `datos_alumno.php`, que recibirá y procesará los datos introducidos. [cite: 70]

**Lógica de Procesamiento:**

1.  **Si se eligió "Mostrar datos: Por Pantalla":**
    * [cite_start]Mostrará la información del alumno formateada en pantalla. [cite: 71]
    * [cite_start]*Ejemplo de salida:* "El alumno Felipe Ríos Vázquez, con teléfono 955979999, está matriculado en un ciclo superior" [cite: 72, 73]
2.  **Si se eligió "Mostrar datos: En Archivo datos.txt":**
    * [cite_start]Deberá guardarse la misma información formateada en el fichero `datos.txt` (ubicado en la misma carpeta que `datos_alumno.php`). [cite: 74]
    * [cite_start]Tras guardar correctamente, aparecerá un **enlace** en pantalla con el texto **"mostrar archivo"**. [cite: 75]
    * [cite_start]Al pulsar el enlace, se cargará la página `mostrardatos.php`. [cite: 75]

### Parte 3: Mostrar Contenido (`mostrardatos.php`)
* [cite_start]La página `mostrardatos.php` deberá abrir el fichero `datos.txt` en modo lectura y mostrar su contenido en el navegador. [cite: 75]

---

## 📞 Ejercicio 4: Agenda Virtual PHP

### Requisito
[cite_start]Crear un programa PHP para gestionar una agenda de contactos, usando ficheros de texto para el almacenamiento. [cite: 81, 82, 92]

### Funcionalidades Requeridas
[cite_start]El programa debe ser capaz de: [cite: 92]

1.  [cite_start]**Mostrar los contactos** existentes. [cite: 93]
    * [cite_start]*Ejemplo de contacto guardado:* `Contacto: Pedro Base de Datos 918989899 C/Mayor 56 Vive cerca` [cite: 83]
2.  [cite_start]**Dar de alta** nuevos contactos mediante un formulario. [cite: 86, 91, 94]
    * [cite_start]**Campos de Alta:** Nombre, Trabajo, Teléfono, Dirección, Otras. [cite: 86, 87, 88, 89, 90]
3.  [cite_start]**Buscar un contacto** y mostrar los datos específicos de ese contacto en concreto. [cite: 95]
