## Instrucciones de Instalación

1. **Descargar e Instalar el JDK**:
   - Visita la página de descargas de Oracle Java SE: [Oracle JDK Downloads](https://www.oracle.com/cl/java/technologies/javase/javase-jdk8-downloads.html).
   - Descarga e instala la versión correspondiente del JDK para tu sistema operativo.

2. **Documentación de Cada Línea de Código**:
import java.util.Scanner; // Importa la clase Scanner para leer la entrada del usuario
public class Main {
    public static void main(String[] args) {
        // Crear un objeto Scanner permite al programa leer datos de entrada desde el teclado
        Scanner scanner = new Scanner(System.in);

        // Solicitar los datos al usuario
        System.out.println("Ingrese la marca del vehículo:");
        String marca = scanner.nextLine();

        System.out.println("Ingrese el modelo del vehículo:");
        String modelo = scanner.nextLine();

        System.out.println("Ingrese la cilindrada del vehículo:");
        String cilindrada = scanner.nextLine();

        System.out.println("Ingrese el tipo de combustible del vehículo:");
        String combustible = scanner.nextLine();

        System.out.println("Ingrese la capacidad en pasajeros del vehículo:");
        int capacidadPasajeros = scanner.nextInt();

        // Mostrar los datos ingresados
        System.out.println("La marca que ha ingresado es: " + marca);
        System.out.println("El modelo que ha ingresado es: " + modelo);
        System.out.println("La cilindrada que ha ingresado es: " + cilindrada);
        System.out.println("El tipo de combustible es: " + combustible);
        System.out.println("Tiene una capacidad de " + capacidadPasajeros + " pasajeros.");
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


