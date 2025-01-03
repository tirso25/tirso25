### <h1 align="center"><b>Hi, I'm [Tirso!](https://www.linkedin.com/in/tirso-morat%C3%B3-miguel/)<img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="35px"></b></h1>

## Who am I?
 ```java
import java.util.ArrayList;
import java.util.List;

public class WhoAmI {
    private String user = "Tirso Morató Miguel";
    
     public String getCurrentEdu() {
        List<String> ambitions = new ArrayList<>();

        currentEdu.add("Microcomputer Systems and Network");
        currentEdu.add("Web application development");

        return currentEdu;
    }

    public List<String> getAmbitions() {
        List<String> ambitions = new ArrayList<>();

        ambitions.add("Learn new technologies");
        ambitions.add("Grow as a programmer");

        return ambitions;
    }

    public void displayDetails() {
        System.out.println("User: " + user);
        System.out.println("Current Education: " + currentEdu);
        System.out.println("Ambitions: " + String.join(", ", getAmbitions()));
    }

    public static void main(String[] args) {
        WhoAmI whoAmI = new WhoAmI();
        whoAmI.displayDetails();
    }
}
