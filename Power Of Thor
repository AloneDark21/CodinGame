import java.util.*;
import java.io.*;
import java.math.*;

class Player {

    public static void main(String args[]) {
        Scanner in = new Scanner(System.in);
        int LX = in.nextInt(); // the X position of the light of power
        int LY = in.nextInt(); // the Y position of the light of power
        int TX = in.nextInt(); // Thor's starting X position
        int TY = in.nextInt(); // Thor's starting Y position

        int thorX = TX;
        int thorY = TY;

        // game loop
        while (true) {
             int remainingTurns = in.nextInt(); // The level of Thor's remaining energy, representing the number of moves he can still make.
             String DirectionX = "";
             String DirectionY = "";
             if (thorX > LX)
             {
                DirectionX = "W";
                thorX--;
             } 
             else if (thorX < LX)
             {
                DirectionX = "E";
                thorX++;
             }

             if (thorY > LY)
             {
                DirectionY = "N";
                thorY--;
             }
             else if (thorY < LY)
             {
                DirectionY = "S";
                 thorY++;
             }
            

            String Directions = DirectionY+DirectionX;

            System.out.println(Directions);
            
        }
    }
}
