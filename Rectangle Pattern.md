Write the code to give the below pattern:

Example Input:
n = 6
m = 6

Output:

\*\*\*\*\*\*
\*\*\*\*\*\*
\*\*\*\*\*\*
\*\*\*\*\*\*
\*\*\*\*\*\*

```java

import java.util.Scanner;
class Main{
    public static void main (String args[]){
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int m = sc.nextInt();
        for(int i=0;i<n;i++){
            for(int j = 0; j < m ; j++)
            {
                System.out.print("*");
            }
             System.out.print("\n");
        }
    }
}

```
