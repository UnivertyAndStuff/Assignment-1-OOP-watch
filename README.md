# Assignment-1-OOP-watch
We have to make a program base on the topic that we've chosen. in our case we chose the topic watch were we have tp define the brand name model size
import java.util.Scanner;

public class MyClass {
    public static void main(String args[]) {
        Scanner scanner = new Scanner(System.in);
        
        while(true){
            System.out.println("Enter brand name 1, 2, 3, 4: ");
            String brand = scanner.nextLine();
            if(brand.equals("1")){
                System.out.println("G-Shock, " + "Sports");
            }
            else if(brand.equals("2")){
                System.out.println("Swiss, " + "high-end");
            }
            else if(brand.equals("3")){
                System.out.println("Ice Watch, " + "Regular");
            }
            else if(brand.equals("4")){
                System.out.println("Apple Watch," + "High-end");
            }
            else if(brand.equals("x")){
                break;
            }
        }
    }
}
