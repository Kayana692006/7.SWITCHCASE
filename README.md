# 7.SWITCHCASE
class Switchcase {
    public static void main(String[] args) {
        int choice = 2;

        switch (choice) {
            case 1:
                System.out.println("hello!");
                break; // Prevent fall-through

            case 2:
                System.out.println("welcome!");
                break; // Prevent fall-through

            case 3:
                System.out.println("invalid choice!");
                break; // Prevent fall-through

            default:
                System.out.println("No matching case found!");
                break;
        }
    }
}


OUTPUT:

PS C:\Users\MY\OneDrive\Pictures\Documents\java emc 1> javac hello.java
PS C:\Users\MY\OneDrive\Pictures\Documents\java emc 1> java hello.java
welcome!
invalid choice!
PS C:\Users\MY\OneDrive\Pictures\Documents\java emc 1> 

