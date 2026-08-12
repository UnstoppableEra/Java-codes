# Java-codes
    //   Variables and Datatypes //

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

Question2: In a program, input the side of a square. You have to output the area of the square.(Hint : area of a square is (side x side))..

import java.util.*;

public class example{
    public static void main(String args[]){

        System.out.println("Enter Number :");
        Scanner sc = new Scanner(System.in);

        int side = sc.nextInt();

        int area = side*side;

        System.out.println("Area of Square is : " + area);
    }
}

Question3:Entercostof3itemsfromtheuser(usingfloatdatatype)-apencil,apenandan eraser. You have to output the total cost of the items back to the user as their bill.(Add on : You can also try adding 18% gst tax to the items in the bill as an advanced problem)

public class example{
    public static void main(String args[]){
        
        int pen = 5;
        int pencil = 5;
        int eraser = 10;

        float Sum = pen + pencil + eraser;

        System.out.println("Total Bill : " + Sum);
        //Add GST
        double newbill = Sum + (Sum * 0.18);
        System.out.println("Bill After Adding GST : " + newbill);
    }
}
