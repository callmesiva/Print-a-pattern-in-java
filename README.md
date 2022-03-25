# Print-a-pattern-in-java

  
                /* *        * 
                   **      ** 
                   ***    *** 
                   ****  **** 
                   **********   To print pattern like this */
 
 
 
 for(int i=1; i<=5; i++)
    {
        for(int j=1; j<=i; j++)
        {
            System.out.print("*");
        }
        for(int j=1; j<=5-i; j++)
        {
           System.out.print(" ");
        }
       
        for(int j=1; j<=5-i; j++)
        {
           System.out.print(" ");
        }
        for(int j=1; j<=i; j++)
        {
           System.out.print("*");
        }
      System.out.println(" ");
    }
