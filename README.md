package com.company;

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        Scanner in = new Scanner(System.in);
        Scanner num = new Scanner(System.in);

        System.out.print("Operation:");
        String C = in.nextLine();

        switch (C) {
            case "+":

                System.out.print("First number:");
                int z = num.nextInt();
                System.out.print("Second number:");
                int x = num.nextInt();
                System.out.println(z + x);
                break;

            case "-":
                System.out.print("First number:");
                int c = num.nextInt();
                System.out.print("Second number:");
                int v = num.nextInt();

                System.out.println(c - v);
                break;

            case "*":
                System.out.print("First number:");
                int b = num.nextInt();
                System.out.print("Second number:");
                int n = num.nextInt();
                System.out.println(b * n);
                break;

            case "/":
                System.out.print("First number:");
                int m = num.nextInt();
                System.out.print("Second number:");
                int l = num.nextInt();
                System.out.println(m / l);
                break;

            case "++":
                System.out.print("First number:");
                String A = in.nextLine();
                System.out.print("Second number:");
                String B = in.nextLine();
                System.out.println(A + B);
                break;

            case "random":

        }
    }
}
