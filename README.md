# computeFactorial
computeFactorial(number)
public class Factorial {
    public static void main(String[] args) {
        int number = 5;
        long factorial = computeFactorial(number);
        
        System.out.println("Факториал числа " + number + " равен: " + factorial);
    }
    
    public static long computeFactorial(int n) {
        if (n == 0) {
            return 1;
        } else {
            return n * computeFactorial(n - 1);
        }
    }
}
