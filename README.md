# hello-world

Hi everyone,

Ananya here, I like learning new things, as well as playing soccer.
I find thrill in many things, I am inquisitve.


import sampleClasses.Cat;

import java.util.Scanner;
public class Main{


     public static void main(String []args) {
          /* Object creation */
          Cat myCat = new Cat( "Ananya" );

          /* Call class method to set puppy's age */
          myCat.setCatAge( 4 );

          /* Call another class method to get puppy's age */
          int age = myCat.getCatAge( );

          /* You can access instance variable as follows as well */
          System.out.println("Variable Value :" + age);
     }
}
