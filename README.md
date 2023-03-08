# Assignment-1-OOP-watch
We have to make a program base on the topic that we've chosen. in our case we chose the topic watch were we have tp define the brand name model size
import java.util.Scanner;

class HelloWorld {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        while(true){
        System.out.println("Enter type name 1, 2, 3, 4: ");
        String type = scanner.nextLine();
        double price;
        
        if(type.equals("1")){
            System.out.println("Plase enter the brand name in the list below:");
            System.out.println("G-shock, Swiss, Ice watch, Apple Watch");
            String brand = scanner.nextLine();
            if(brand == "G-shock" || brand == "gshock"){
                System.out.println("Plase enter colour of A, B, C, D: ");
                String colour = scanner.nextLine();
                if(colour == "A"){
                    price = 100;
                    System.out.println("Your choose " + type + brand + colour + price );
                }
            }
        }
        else if(type.equals("2")){
            System.out.println("Plase enter the brand name in the list below:");
            System.out.println("G-shock, Swiss, Ice watch, Apple Watch");
            String brand = scanner.nextLine();
            if(brand == "G-shock" || brand == "gshock"){
                System.out.println("Plase enter colour of A, B, C, D: ");
                String colour = scanner.nextLine();
                if(colour == "A"){
                    price = 100;
                    System.out.println("Your choose " + type + brand + colour + price );
                }
            }
        }
        else if(type.equals("3")){
             System.out.println("Plase enter the brand name in the list below:");
            System.out.println("G-shock, Swiss, Ice watch, Apple Watch");
            String brand = scanner.nextLine();
            if(brand == "G-shock" || brand == "gshock"){
                System.out.println("Plase enter colour of A, B, C, D: ");
                String colour = scanner.nextLine();
                if(colour == "A"){
                    price = 100;
                    System.out.println("Your choose " + type + brand + colour + price );
                }
            }
        }
        else if(type.equals("4")){
             System.out.println("Plase enter the brand name in the list below:");
            System.out.println("G-shock, Swiss, Ice watch, Apple Watch");
            String brand = scanner.nextLine();
            if(brand == "G-shock" || brand == "gshock"){
                System.out.println("Plase enter colour of A, B, C, D: ");
                String colour = scanner.nextLine();
                if(colour == "A"){
                    price = 100;
                    System.out.println("Your choose " + type + brand + colour + price );
                }
            }
        }
        else if(type.equals("x")){
            break;
        }
        else{
            System.out.println("Invalid please try again");
        }
    }
  }
}
