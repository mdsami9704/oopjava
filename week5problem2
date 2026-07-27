class Vehicle {
    void move() {
        System.out.print("vehicle with pedals.");
    }
}

class Cycle extends Vehicle {
    void move() {
        System.out.print("cycle who is a ");
        super.move();
    }
}

class Motorcycle extends Cycle {
    void move() {
        System.out.print("I am a motorcycle, I am a cycle with an engine.\n");
        System.out.print("My ancestor is a ");
        super.move();
    }
}

public class Solution {
    public static void main(String[] args) {
        Motorcycle bike = new Motorcycle();
        System.out.print("Hello ");
        bike.move();
    }
}
