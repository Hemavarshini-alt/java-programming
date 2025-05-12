import java.util.*;

class Animals {
    void sound() {
        System.out.println("Animals sound");
    }
}

class Bird extends Animals {
    void sound() {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter the bird sound: ");
        String birdsound = scanner.nextLine();
        System.out.println("Bird sound: " + birdsound);
    }
}
class Cat extends Animals {
    void sound() {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter the Cat sound: ");
        String catsound = scanner.nextLine();
        System.out.println("Bird sound: " + catsound);
    }
}


public class Main {
    public static void main(String[] args) {
        Animals animal = new Animals();
        Bird bird = new Bird();
        Cat cat = new Cat();
        bird.sound(); 
        cat.sound();
}
}
