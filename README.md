# Java-codes

Question1  :Inaprogram,input3numbers:A,BandC.Youhavetooutputtheaverageofthese 3 numbers.(Hint : Average of N numbers is sum of those numbers divided by N)

import java.util.*;
import java.util.Scanner;

public class example {
    public static void main(String args[]){
        System.out.println("Enter Number :");
        Scanner sc = new Scanner(System.in);

        int a = sc.nextInt(), b = sc.nextInt(), c = sc.nextInt();

        float result = (a + b + c) / 3 ;

        System.out.println("Average is :"+ result);
    }
}
