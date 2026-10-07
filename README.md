Cientifiks: Anna i el misteri de les tres fonts

Fork del proyecto original jorditus99/cient-fiks, desarrollado en equipo.

Plataforma de videojuegos educativos en la que hay que ayudar a Anna a devolver el agua a las fuentes de su escuela superando cinco juegos. Incluye registro, inicio de sesión y un ranking de puntuaciones.

🎮 Demo

Jugar al juego de limpieza de residuos

Se juega desde el ordenador con las flechas del teclado: hay que recoger la basura del agua del Delta del Llobregat sin atrapar a los animales.

Nota: esta demo está publicada en GitHub Pages, que solo sirve archivos estáticos. Por eso el juego funciona, pero el login, el registro y el ranking no: necesitan un servidor con PHP y MySQL. Al terminar la partida, la puntuación no se guarda en el ranking.

👩‍💻 Mi aporte (Virginia)

Login

Inicio de sesión con sesiones de PHP.
Verificación de contraseñas hasheadas con password_verify.
Consultas a la base de datos con PDO y sentencias preparadas, para prevenir inyección SQL.
Código: log_in.php y php_library/library.php.

Juego de limpieza de residuos

Desarrollado en JavaScript, sin librerías.
Detección de colisiones entre la cesta y los objetos que caen.
Sistema de 3 vidas y puntuación por residuo recogido.
Dificultad progresiva: cada 50 puntos aumenta la velocidad y la frecuencia de los objetos.
Envío de la puntuación al ranking mediante fetch a un endpoint PHP.
Código: joc_virginia/.
🛠️ Tecnologías
Frontend: HTML5, CSS3, JavaScript
Backend: PHP con PDO
Base de datos: MySQL
👥 Equipo

Proyecto desarrollado junto a Erfan, Jordi, Natalia y Roger. Cada integrante creó uno de los cinco juegos de la plataforma.
