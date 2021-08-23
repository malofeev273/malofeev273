package com.company;
import java.lang.String;
import java.util.Scanner;

public class Main {
public static void main(String[] args) {
    Scanner num = new Scanner(System.in);
    int a, b, c;
    System.out.println("a=");
    a = num.nextInt();
    System.out.println("b=");
    b = num.nextInt();
    c = a + b;
    System.out.println("c="+ c);

}
}
