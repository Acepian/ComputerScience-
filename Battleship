import java.util.Random;
import java.util.Scanner;
import java.util.Arrays;
import java.util.Scanner;
import java.util.*;


public class Battleship {
    public static void main(String[] args) {

        int numRows = 10;
        int numCols = 10;
        int playerShips;
        int computerShips;
        String[][] grid = new String[numRows][numCols];
        int[][] missedGuesses = new int [numRows][numCols];

        Scanner input = new Scanner(System.in);
        Random rand = new Random ();

        System.out.println("** Welcome to Battleship **");

/** Create Ocean map                This will be a typical 10x10 grid game with 5 ships,  I will try to create
 *   Deploy player's ships          a detailed game board further into development, don't want to copy, but will have to
 *   Deploy computer's ships        lookup more code examples to understand how to do this.  maybe I can make cool detail ships
 *   Battle                         also instead of silly keyboard char's ~~~+==#==+~~~
 */


        createOceanMap(); {
            System.out.print(" ");
            for (int i = 0; i < 10; i++) {
                for (int j =0; j < grid[i].length; j++) {
                    grid[i][j] = " ";
                    if (j == 0)
                        System.out.print(i + "|" + grid[i][j]);
                    else if (j == grid[i].length - 1)
                        System.out.print(grid[i][j] + "|" + i);
                    else
                        System.out.print(grid[i][j]);
                }
                System.out.println();
            }
        }
        System.out.print(" ");
        for(int i = 0; i < numCols; i++)
            System.out.print(i);
        System.out.println();
    }

    private static void createOceanMap() {
    }
}
