
TE3.1 - Configuración de Eclipse y JetBrains IntelliJ IDEA
En esta tarea de aprendizaje, aprenderás a instalar el JDK y JREs en Windows y Linux, y a configurar Eclipse y JetBrains IntelliJ IDEA.

Recursos
Instalación del JDK en Linux
Instalación del JDK en Windows
Objetivos
Conocer cómo instalar el JDK/JRE en Windows y Linux.
Conocer cómo configurar Eclipse y JetBrains IntelliJ IDEA para utilizar un JDK.
Conocer cómo configurar Windows y Linux a nivel de sistema para utilizar diferentes versiones de Java.
Conocer cómo instalar y usar la herramienta SDKMan para instalar diferentes versiones de Java en Linux/MacOS/Windows.
Recursos
GIF Videos

Software crear GIFs animados para Windows
Software crear GIFs animados para Linux
Herramienta Online GIF
Entrega
El documento justificativo de la realización de la tarea se realizará en formato Markdown, el nombre del fichero será readme.md y estará dentro de la carpeta UT3\TE3.1 dentro del repositorio oficial del alumno para la asignatura.

El fichero readme.md debe contener los siguientes apartados:

Cada uno de los puntos de la tarea.
1. Configuración de Java en Windows y Linux
Revisa la configuración de tu máquina a través del terminal e indica la versión de Java que tienes instalada.
# Comprueba la versión de Java instalada
$> java -version
# Comprueba donde está instalado Java
$> where java
# Busca todas las versiones de Java instaladas
$> which java
📎 Adjunta una imagen de los comandos anteriores y responde a las siguientes preguntas

¿Qué versión de Java tienes instalada?

¿Cuantas versiones de Java tienes instaladas? ¿ Por qué?

Si tienes más de una versión indica todas las versiones y rutas de instalación.
Variables de entorno.

📎 Adjunta una imagen de las variables de entorno de tu sistema, tanto a nivel de usuario como a nivel de sistema.

Muestra a través de interfaz (Ventana de windows) (Usuarios y sistema) [adjuntar imagen]
Muestra a nvel de comandos (Solo usuario) (set) [adjuntar imagen]
Muestra el contenido de la variable PATH (echo %PATH%) y de la variable JAVA_HOME (echo %JAVA_HOME%)
Instala el JDK 19 la implementación de Adoptium (Windows)

Ves a la página de Adoptium y descarga la versión de Java 19 para Windows y la arquitectura de tu PC (x32/x64). (Incluye un gif de la instalación)

Una vez instalado, muestra la versión de Java instalada y la ruta de instalación. (a través de comandos y adjunta una imagen) (java -version y where java)

¿ La versión de Java que te muestra es la 19? ¿ Por qué?

Configura tu sistema para que utilice la versión de Java 19 como versión por defecto a nivel de usuario. (Si ya lo tienes explica por qué)
![Captura de pantalla 2025-02-27 164050](https://github.com/user-attachments/assets/b63cefce-6bc1-4484-82e9-0aae0237d476)
![Captura de pantalla 2025-02-27 164302](https://github.com/user-attachments/assets/da338829-f985-49e4-8b41-a7759975eb71)
![Captura de pantalla 2025-02-27 164349](https://github.com/user-attachments/assets/0d7abbdf-a4e6-49ed-9baf-313754746070)
![Captura de pantalla 2025-02-27 164430](https://github.com/user-attachments/assets/e8f73d2f-730c-4dbc-a8a9-bdff3190a679)
![Captura de pantalla 2025-02-27 164830](https://github.com/user-attachments/assets/f97b3311-5b1a-42fe-aa17-d38397825c17)
![Captura de pantalla 2025-02-27 165356](https://github.com/user-attachments/assets/c52642ec-02fa-4737-8a53-9fe122ecc4a1)




2. Utilización de SDKMan
Instala SDKMan en Windows. (_Para ello puedes seguir la guía disponible aquí

Instala SDKMan en Windows e explica los pasos que has seguido, adjunta una captura final de SDK funcionando.

Muestra la versión de SDKMan instalada

¿ Dónde se ha instalado SDKMan? ¿ Por qué?

Muestra las versiones de Java que tienes instaladas a través de SDKMan

¿ Qué ventajas tiene instalar SDKMan?

¿ Instala la versión de Jara 8.0_302-zulu a través de SDKMan ?

¿ Instala la versión de Java 11.0.12-zulu a través de SDKMan ?

¿ Instala la versión de Java 17.0.0-zulu a través de SDKMan ?

Configura tu sistema para que utilice la versión de Java 17.0.0 como versión por defecto a nivel de usuario. (Para que las aplicaciones que ejecutes utilicen esta versión de Java)

¿ Qué tienes hacer o comando tienes que utilizar (SDKMAN) para que una aplicación ejecutada desde la interfaz (Windows o Linux) utilize esa versión de Java?

¿ Qué variable de Entorno tienes que modificar para que una aplicación ejecutada desde la interfaz (Windows o Linux) utilize esa versión de Java?

Si necesitas compilar una aplicación de Java desde la terminal, fuera del IDE, y necesita compilarse con la version de Java 8, ¿ Cómo lo harías?

¿ Qué comando de SDKMAN tienes que utilizar para que a nivel de la terminal actual use la versión de Java 8?

¿ Qué comando utilizas para compilar una aplicación de Java ?

Un proyecto en el que estas trabajando, neceseita la versión de Java 11, pero requieres compilarlo con esa versión, pero no quieres tener siempre que recordar esto, y quieres que se active automáticamente esa versión una vez accedas al directorio del proyecto.

¿ Cómo puedes realizar esto con SDKMAN ? (indica los comandos que tienes que utilizar y la configuración de la herramienta)

Haz una captura de pantalla entrando y saliendo del directorio del proyecto, para ver cono se activa y desactiva una versión y otra de Java.
![Captura de pantalla 2025-02-27 172137](https://github.com/user-attachments/assets/74665499-a997-4376-8b81-6a3f13556606)
![Captura de pantalla 2025-02-27 172145](https://github.com/user-attachments/assets/4dbd83ab-fcc1-4ca0-850f-e53bd878cff5)
![Captura de pantalla 2025-02-27 172321](https://github.com/user-attachments/assets/fa59cda5-cb50-4c94-918f-b1c24759622e)
![Captura de pantalla 2025-02-27 172426](https://github.com/user-attachments/assets/02d78572-8139-4807-aded-0f8a5aac86bc)
![Captura de pantalla 2025-02-27 172524](https://github.com/user-attachments/assets/597265f5-2831-4a49-bf35-2eb3e2ec359a)
![Captura de pantalla 2025-02-27 172554](https://github.com/user-attachments/assets/a999af7d-b356-482a-928d-54505f4aca13)
![Captura de pantalla 2025-02-27 172752](https://github.com/user-attachments/assets/5db8d7b4-28c5-41cc-9a73-33c17c4a709a)
![Captura de pantalla 2025-02-27 172849](https://github.com/user-attachments/assets/13ec4b64-5698-40cb-9b32-881d254d13c0)
![Captura de pantalla 2025-02-27 172958](https://github.com/user-attachments/assets/a615d374-008b-4303-982c-969649c71cc2)

3. Utilización de JetBrains IntelliJ IDEA
Crea un nuevo proyecto en IntelliJ IDEA (TE21-Paso10) y configura en ese directorio, con SDKMAN para que utilize la versión de Java 11.
Ahora al abrir IntellJ IDEA, debe activar esa versión automaticamente, pues detectar la configuración. (Incluye una captura de panntalla o GIF de la configuración))
Crea un nuevo proyecto en IntelliJ IDEA (TE21-Paso12) que se guarde en la carpeta TE21-Paso12.
Configura el proyecto para que utilice la versión de Java 17 descargada con SDKMAN. (Muestra una captura de pantalla de la configuración del fichero .sdkmanrc)
Agrega otro módulo al proyecto, que se guarde en la carpeta Modulo2.
Agrega otro módulo al proyecto, que se guarde en la carpeta Modulo3.
(Muestra una captura de pantalla de la estructura del proyecto en IntelliJ IDEA)

Vincula el proyecto principal, con los módulos 2 y 3. (Muestra una captura de pantalla de la configuración de los módulos)
En el módulo 2, crea una clase que se llame Utilidades y que tenga un método que se llame calculadora y que tenga los métodos de suma, resta, multiplicación y división.
(Muestra el código de la clase Utilidades con un bloque de código)

En el módulo 3, crea una clase llamada Conversor que tenga un método que se llame Texto_to_Uppercase que convierta un texto a mayúsculas, y otro método que se llame Texto_to_Lowercase que convierta un texto a minúsculas.
(Muestra el código de la clase Conversor con un bloque de código)

En el módulo principal, crea una clase llamada Principal que tenga un método main que instancie las clases Utilidades y Conversor y que muestre por consola el resultado de las operaciones de la clase Utilidades y el resultado de las operaciones de la clase Conversor.
(Muestra un gif donde se muestre la ejecución del programa, en depuración y se visualice que no existen errores de compilación ni ejecución).
![Captura de pantalla 2025-02-27 173048](https://github.com/user-attachments/assets/69575419-3aa5-4ff3-b8b4-bb5e0197fbaf)
![Captura de pantalla 2025-02-27 174356](https://github.com/user-attachments/assets/a730fa55-9bc9-4208-af17-4933feb1035d)
![Captura de pantalla 2025-02-27 174708](https://github.com/user-attachments/assets/b8a32a40-5074-4deb-bda5-05940837727d)
![Captura de pantalla 2025-02-27 174916](https://github.com/user-attachments/assets/5b0ef4a4-b6be-4aee-986f-44c366e6c961)
