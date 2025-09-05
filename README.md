     #Riddle-game
    import java.util.Scanner;

    public class RiddleGame {
    public static void main (String[] args) {
    Scanner sc = new Scanner(System.in);
      System.out.println("Riddle: I speak without a mouth and hear without ears. "
                         + "I have no body, but I come alive with the wind.");
      String answer ="";
      
     while(true) {
          System.out.print("Think about it and give the answer: ");
          answer = sc.nextLine().trim().toLowerCase();
          
     if(answer.equals("echo") || answer.equals("ai")) {
              System.out.println("Congratulations ! you guessed Correct ");
              break;
              
    } else if(answer.equals("quite")) {
              System.out.println("Game exited ! the correct answer is echo.");
              break; 
              
        } else {
              System.out.println("Wrong! Try again or(type 'quite' to exite) ");
          }
      }
            
       }
     }
     
