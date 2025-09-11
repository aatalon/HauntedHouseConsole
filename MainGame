package InputProcessingOutput;
import java.util.Scanner;

public class HauntedHouseGame {
  public static void main(String[] args) {
    Scanner scanner = new Scanner(System.in); // INITIATE THE SCANNER

    System.out.println("You wake up in a dark, scary and dusty room of a haunted house in the middle of a forest."); // THE STARTING OF THE STORY
    System.out.println("Do you try the 'door' or the 'window'? Type door or window:"); // FIRST CHOICE QUESTION DOOR
    String firstChoice = scanner.nextLine();

    if (firstChoice.equalsIgnoreCase("door")) { // IF THEY CHOOSE DOOR OPTION
      System.out.println("The door creaks open... You hear footsteps. Do you 'hide' or 'call out'?"); // SECOND CHOICE QUESTION DOOR
      String secondChoice = scanner.nextLine();
      if (secondChoice.equalsIgnoreCase("hide")) { // IF THEY CHOOSE HIDE
        System.out.println("You find a secret passage. Do you 'follow' it or 'stay put'?"); // THIRD CHOICE QUESTION DOOR
        String thirdChoice = scanner.nextLine();
        if (thirdChoice.equalsIgnoreCase("follow")) {
          System.out.println("You escaped through the passage from the Evil Zombie Whitch! You win!");
        } else { // IF YOU STAY PUT
          System.out.println("A evil Zombie Witch finds you in the dark. Game over!");
        }
      } else {
        System.out.println("A evil Zombie Witch is waiting there for... Game over!");
      }

    } else if (firstChoice.equalsIgnoreCase("window")) { // IF THEY CHOOSE WINDOW OPTION
      System.out.println("You climb out into a foggy garden. Do you go to the 'shed' or take the 'path'?"); // FIRST CHOICE QUESTION WINDOW
      String secondChoice = scanner.nextLine();
      if (secondChoice.equalsIgnoreCase("shed")) { // IF THEY CHOOSE THE SHED
        System.out.println("A zombie bursts out of the shed! You trip while running. Game over!");
      } else { // IF THEY CHOOSE THE PATH
        System.out.println("A evil Zombie Witch is waiting there for... Game over!");
      }
    } else {
      System.out.println("Invalid choice. Please restart the game."); // IF THEY PUT INVALID OPTION
    }

    scanner.close();
  }
}
