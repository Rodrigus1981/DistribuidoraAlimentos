## Instrucciones de Instalación

1. **Descargar e Instalar el JDK**:
   - Visita la página de descargas de Oracle Java SE: [Oracle JDK Downloads](https://www.oracle.com/cl/java/technologies/javase/javase-jdk8-downloads.html).
   - Descarga e instala la versión correspondiente del JDK para tu sistema operativo.

2. **Documentación de Cada Línea de Código**:
   import java.util.Scanner; // Importa la clase Scanner para leer la entrada del usuario

public class Main {
    public static void main(String[] args) {
        // Crear un objeto Scanner para la entrada de datos
        Scanner scanner = new Scanner(System.in);

        // Solicitar los datos al usuario
        System.out.println("Ingrese la marca del vehículo:");
        String marca = scanner.nextLine(); // Lee la marca ingresada por el usuario

        // Repite para los demás datos...

        // Mostrar los datos ingresados
        System.out.println("La marca que ha ingresado es: " + marca); // Imprime la marca ingresada
        // Repite para los demás datos...
    }
}


## Compilación y Ejecución

1. **Compilar el Código**:
   - Abre una terminal o línea de comandos.
   - Navega al directorio donde se encuentra el archivo `menu_vehiculo.java`.
   - Ejecuta el siguiente comando para compilar el código:
     ```
     javac menu_vehiculo.java
     ```

2. **Ejecutar el Programa**:
   - Después de compilar, ejecuta el programa con:
     ```
     java menu_vehiculo
     ```


