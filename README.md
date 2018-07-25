# inefficiently-messing-with-strings---misc
public class JavaApplication14 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        System.out.println(Math.PI);
        String text = "hello";
        
        int myInt = 22;
        
        String blank = " ";
        
        String name = "ok";
        
        String blank1 = " ";
        
        String greet = text + blank + name;
        
       String a = "yo";
       String b = "ho";
       String c = "ho";
       String one = "Yarr";
       
       String pirate = one + blank + a + blank1 + b + blank + c + blank + " \n" + a + blank + b + blank1 + c + blank + "\n" + one;
       
        System.out.println(pirate + blank + a + blank1 + b + blank + c + blank1 + "\n" + one);
        System.out.println("Text.\nnext line.\ta tab\n" + one + "\nmore text");
        
        StringBuilder s = new StringBuilder();
        
        s.append("that was Piratey\n")
        .append("yarp");
        
        System.out.println(s.toString());
        
        System.out.printf("Total cost %d \nQuantity is %d \nModel number is %d-%d\n", 3, 87, 1337, 2);
        
        for (int i=0; i < 8; i++) {
            System.out.printf("%5d: here are 8 lines of repeating text\n", i);
    
    }
    
    
}
