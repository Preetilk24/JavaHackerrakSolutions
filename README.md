# JavaHackerrakSolutions


Java Stdin and Stdout I

import java.util.*;


      public class Solution {
    public static void main(String[] args) {    
        Scanner scanner = new Scanner(System.in);           
        while (scanner.hasNext()) {
            System.out.println(scanner.nextInt());
        }
        scanner.close();
    }
}
