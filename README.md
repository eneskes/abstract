# abstract
public abstract class C04 {
   
    public abstract void absMethod();
    public void concreteMethod(){
        System.out.println("C04 concrete method");
    }
    public static void concreteStaticMethod(){
        System.out.println("C04 concrete static method");
    }
    public static void main(String[] args) {
       
        // C04 obj=new C04();
        System.out.println("Bu class abstract");
        concreteStaticMethod();
    }
