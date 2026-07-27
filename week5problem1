import java.util.Scanner;

class Sports {
    String getName() {
        return "Generic Sports";
    }
    void getNumberOfTeamMembers() {
        System.out.println("Each team has n players in " + getName());
    }
}

class Soccer extends Sports {
    @Override
    String getName() {
        return "Soccer Class";
    }
    
    @Override
    void getNumberOfTeamMembers() {
        System.out.println("Each team has 11 players in " + getName());
    }
}

public class Solution {
    public static void main(String[] args) {
        Sports mySports = new Sports();
        System.out.println(mySports.getName());
        mySports.getNumberOfTeamMembers();

        Soccer mySoccer = new Soccer();
        System.out.println(mySoccer.getName());
        mySoccer.getNumberOfTeamMembers();
    }
}
