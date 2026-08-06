```java
class Developer {
    String name = "Vitor Eskes";
    String profession = "Full Stack Developer";
    
    class Contact {
        String email = "vitoralveseskes@gmail.com";
    }
    
    Contact contact = new Contact();
}

public class Main {
    public static void main(String[] args) {
        Developer dev = new Developer();
        System.out.println(dev.name);
        System.out.println(dev.profession);
        System.out.println(dev.contact.email);
    }
}
```
