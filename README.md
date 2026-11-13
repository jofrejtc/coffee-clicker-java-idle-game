# Coffee Clicker

Juego de escritorio en Java y Swing. El jugador produce café y reinvierte los recursos en generadores y mejoras. El código se organiza en capas de presentación, lógica de negocio y persistencia con MySQL.

## Aportación de Jofre

Implementé el inicio y el cierre de sesión, conecté los controladores y las vistas de usuario con la persistencia, y desarrollé la lógica de las mejoras de los generadores. También refactoricé `GameManager` para reducir sus responsabilidades.

## Ejecutar en local

Descarga [el proyecto completo](coffee-clicker-java-idle-game.zip), descomprime el ZIP y abre la carpeta `coffee-clicker-java-idle-game` antes de seguir los pasos de esta sección.

Requisitos: JDK 17 o posterior, Maven y una instancia local de MySQL. Usa una base y una cuenta dedicadas al proyecto.

1. Crea una base de datos vacía llamada `db_cc1` e importa `Database/db_cc1.sql` en ella.
2. Copia `files/ConfigDB/config.example.json` a `files/ConfigDB/config.json` y completa los datos de tu servidor local.
3. Desde la raíz del repositorio, ejecuta `mvn compile exec:java`.
4. Registra una cuenta de prueba en la aplicación. Usa datos ficticios y una contraseña exclusiva para esta demo académica.

El diagrama de clases de StarUML está en `docs/UML.mdj`. Esta versión incluye el esquema de la base de datos y los recursos de la interfaz.

## Verificación

El código Java se compiló con el destino Java 17 y las dependencias de Gson y MySQL indicadas. La ejecución completa de la interfaz requiere una base de datos local configurada.

## Equipo y licencia

Trabajo académico de Eric Faya, Víctor Corral, Bruno Bordoy, Jofre Tura Centelles y Guillem Gil. Guillem publicó el repositorio original. Esta copia conserva la licencia MIT y su aviso de copyright en `LICENSE`.
