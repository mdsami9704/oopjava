import java.util.Scanner;

class Singleton {

    public String str;
    private static Singleton instance = null;

    private Singleton() {
    }

    public static Singleton getSingleInstance() {
        if (instance == null) {
            instance = new Singleton();
        }
        return instance;
    }
}

public class Solution {

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        Singleton singleton = Singleton.getSingleInstance();
        singleton.str = sc.nextLine();

        System.out.println("Hello I am a singleton! Let me say " + singleton.str + " to you");
    }
}
