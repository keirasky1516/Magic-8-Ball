# Magic-8-Ball
This is my Magic 8 Ball repo

public class Magic8Ball {

   public static void main(String[] args) {
       //Declare
       Scanner keyboard;
       int testing;
       String question;


       //Initializing
       keyboard = new Scanner(System.in);


       System.out.println("Would you like to ask the magic 8 ball a question?");
       keyboard.nextLine();
       System.out.println("Now ask a question");
       question=keyboard.nextLine();
       System.out.println("Input a number from 1 to 100");
       testing = keyboard.nextInt();


        if (testing<=10) {
            System.out.println("Most Likely");

        }else if (testing<=20) {

            System.out.println("All signs point to yes");

        }else if (testing<=30){

            System.out.println("possibly");

       }else if (testing<=40){

            System.out.println("yes");

       }else if (testing<=50){

           System.out.println("You wish");

       }else if(testing<=60){

           System.out.println("Most definitely");

       }else if(testing<=70){

           System.out.println("no");

       }else if (testing<=80){

           System.out.println("Try again later");

       }else if (testing<=90){

           System.out.println("I doubt it");

       }else if (testing<=100){

           System.out.println("yeah, no");


       }
       System.out.println("Thank you for using magig 8 ball");
