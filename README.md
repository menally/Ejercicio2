import java.util.Scanner;
public class Main {
    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);
//Scanner:Permite recibir el número del usuario.//

        System.out.print("Introduce un número entero positivo: ");

        int x = scanner.nextInt();
//int x: Guarda el número ingresado.//

        int y = 0;
//int y = 0 : Inicializa el resultado en cero//

        while (x > 0) {
            y += x;
            x--;
            //while (x > 0): Repite mientras x sea mayor que cero//
           // y += x: Va acumulando los valores//
            // x--: Disminuye x en uno//
        }

        System.out.println("El valor final calculado es: " + y);
// println: Muestra el resultado//

        scanner.close();
    }
}
//El programa recibe un número entero positivo y suma todos los
// números desde ese valor hasta uno//