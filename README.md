AnalizadorFacial-Java
🚀 AnalizadorFacial-Java es una aplicación en Java que usa OpenCV para detectar rostros en tiempo real a través de la cámara y clasificar el género de las personas (hombre o mujer) con un modelo de Deep Learning.

📌 Características
✅ Detección de rostros en tiempo real usando OpenCV.
✅ Clasificación de género (hombre/mujer) con redes neuronales.
✅ Interfaz gráfica con ventana de visualización.
✅ Botón para cerrar la aplicación de forma segura.

🔧 Requisitos
Antes de ejecutar el proyecto, asegúrate de tener:

Java 8+
OpenCV 4+ con el módulo opencv_dnn
Modelos preentrenados para detección facial y clasificación de género
📥 Descarga los modelos necesarios
Modelo de detección facial:
haarcascade_frontalface_default.xml
Modelo de clasificación de género:
deploy_gender.prototxt
gender_net.caffemodel
Coloca estos archivos en la carpeta del proyecto.

🚀 Instalación y Ejecución
Clona el repositorio

git clone [https://github.com/tuusuario/AnalizadorFacial-Java.git](https://github.com/Miguel-Manzanilla/AnalizadorFacial-Java.git)

cd AnalizadorFacial-Java

Compila y ejecuta el código

javac -cp "libs/opencv-4.x.jar" src/AnalizadorFacial.java
java -cp "libs/opencv-4.x.jar:src" AnalizadorFacial

🛠 Mejoras futuras
🔹 Detección de edad.
🔹 Reconocimiento de personas específicas.
🔹 Captura de imágenes cuando se detecte una cara.

💡 ¡Contribuciones bienvenidas! Si tienes ideas para mejorar el proyecto, abre un issue o envía un pull request. 🚀
