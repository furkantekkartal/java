# Java | All java codes in the learning process

## 1. General Codes

* Trial

### Printf commands;

```
public class PrintfExample {
    public static void main(String[] args) {
        String name = "John Doe";
        int age = 25;
        double salary = 5000.75;
        boolean isEmployed = true;
        char grade = 'A';

        // Using printf with different variable types
        System.out.printf("Name: %s, Age: %d, Salary: $%.2f, Employed: %b, Grade: %c%n", name, age, salary, isEmployed, grade);
    }
}
```

### for loop;
```
public class PrintfExample {
    public static void main(String[] args) {
          int[] numbers = {10, 20, 30, 40, 50};
          for (int i = 0; i < numbers.length; i++) {
              System.out.println(numbers[i]);
           }
    }
}
```

### if commands;
```
public class OneLineIfExample {
    public static void main(String[] args) {
        int x = 10;

        // One-line if statement
        String message = (x > 5) ? "x is greater than 5" : "x is not greater than 5";
        System.out.println(message);

        // if statement
        if (x > 5) {
            System.out.println("x is greater than 5");
        } else if (x < 5) {
            System.out.println("x is less than 5");
        } else {
            System.out.println("x is equal to 5");
        }
    }
}
```


### Decleration of variables, array, arraylist, object;

```
public class MyVariables {
    public static void main(String[] args) {

        int age = 10; // You are 10 years old!
        long bigNumber = 1234567890; // A really big number
        double pi = 3.14159; // Pi, used for circles
        float smallDecimal = 2.5f; // A smaller decimal number
        char initial = 'A'; // Your first initial
        String name = "Alice"; // Your name
        boolean isHappy = true; // Are you happy?

        int[] scores = {90, 85, 95}; // Arrays (like a list of things)

        // ArrayList (like a flexible list)
        ArrayList<String> colors = new ArrayList<>(); // A flexible list that can grow or shrink (like a list of colors).
            colors.add("red");
            colors.add("blue");

        // Objects (like a toy with properties)
        class Toy {
            String color;
            int size;
        }
        Toy teddy = new Toy();
            teddy.color = "brown";
            teddy.size = 20; // 20 cm tall
    }
}
```



```
   public String toString() {
      return String.format( "%s %s%n"
              +             "%s: %.2f", 
              "base-salaried",super.toString(), 
              "base salary", getBaseSalary());   
   }
```
