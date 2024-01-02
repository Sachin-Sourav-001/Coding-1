# Coding-1
This is my first Repository.
<br>
Author - Sachin Sourav.
<br>
// Guess my Number Game(JAVA).
<br>
import java.util.Scanner;

class Game{

    public static void main(String[] args ){
        Scanner sc = new Scanner(System.in);

        int myNumber = (int)(Math.random()*100);
        int userNumber = 0;

        do{
            System.out.println("Guess the number(1-100) :");
            userNumber = sc.nextInt();

            if(userNumber == myNumber){
                System.out.println("YAY!  you are CORRECT BINGO!");
                break;}

            else if(userNumber > myNumber){
                System.out.println("your guessed number is higher plz try again!");

                }
             else{
                System.out.println("your guessed number is lesser than actual");
             }
        } 
             while(userNumber >= 0);

             System.out.print("My number was:");
             System.out.println(myNumber);

      }
    }

