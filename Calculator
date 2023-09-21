import java.lang.Math;
import java.util.Scanner;

class HelloWorld {
    
    public static double leakRCalc(double cfmI, double pasI) {
        return cfmI / (Math.sqrt(pasI) * 1.06);
    }
    
    public static void main(String[] args) {
        
        Scanner cfmInput = new Scanner(System.in);
        
        System.out.println("Please enter CFM");
        
        double cfm = cfmInput.nextDouble();
        
        Scanner pasInput = new Scanner(System.in);
        
        System.out.println("\nPlease enter pascals");
        
        double pas = pasInput.nextDouble();
        
        double leakRate = leakRCalc(cfm, pas);
        
        System.out.println("\nAir changes per hour at 50 pascal pressure differential is " + leakRate);
    }
}
