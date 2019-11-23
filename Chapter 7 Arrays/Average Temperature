/**
 * Read a series of high temperatures and report the average
 * and the number of days above average.
 */

import java.util.Scanner;
public class AverageTemp {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.print("How many days temperature? ");
        int daysNum = input.nextInt();
        int[] temps = new int[daysNum];
        int sum = 0;

        // record temperatures and find average
        for ( int i = 0; i < temps.length; i++) {
        System.out.print("Day" + (i + 1) + "'s high temp: ");
        temps[i] = input.nextInt();
        sum += temps[i];
    }
        double average =  (double)sum/ daysNum;

        // count days above average
        int above = 0;
        for ( int i = 0; i < temps.length; i++) {
           if (temps[i] > average) {
               above++;
           }
        }

        //report results
        System.out.println();
        System.out.println("Average = " + average);
        System.out.println(above + " days above average.");
    }
}
