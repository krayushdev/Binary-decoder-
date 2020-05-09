# Binary-decoder-
Binary decoder by java

import java.util.*;
import java.math.*;

public class Program
{
    public static void main(String[] args) {
        Scanner s= new Scanner(System.in);
              String[]lines = s.nextLine().split(" ");
             for(String line:lines){
                   BigInteger i = new BigInteger(line,2);
                   System.out.println(i.toString()+ "|" +((char) Integer.parseInt( i.toString())));
             }
    }
}
