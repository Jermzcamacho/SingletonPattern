# SingletonPattern
Singleton.java

public enum Singleton {
	//An enum can contain constants, methods etc.
    INSTANCE;
	//Singleton pattern helps us to keep only one instance of a class at any time.
	//The purpose of singleton is to control object creation by keeping private constructor.
    private Singleton() {
        System.out.println("Here");
    }
public static void main(String[] args) {
    System.out.println(Singleton.INSTANCE);
	}
}
