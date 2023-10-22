# Method
public class tst2 {
    public static void main(String[] args) {
        testMake("from Martian");
        examResults("Taleh Hasanov", 13);
        examResults("Other Person", 15);



    }

    private static void testMake(String names){
        System.out.println("I will back " + names);
    }
    private static void testMath(int a){
        System.out.println(a);
    }

    private static void examResults(String ad, int c){
        System.out.println("Your result is " + ad + c);
    }

}
