Print below pattern:

*<br>
**<br>
***<br>
****<br>
*****<br>

```java

import java.util.Scanner;
class Main{
    public static void main (String args[]){
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        for(int i=0;i<n;i++){
            
            for(int j = 0; j <=i; j++)
            {
                System.out.print("*");
            }
             System.out.print("\n");
        }
    }
}
```


Print Below Pattern:

1<br>
1 2 <br>
1 2 3<br>
1 2 3 4<br>
1 2 3 4 5<br>


```java
import java.util.Scanner;
class Main{
    public static void main (String args[]){
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        for(int i=0;i<n;i++){
            
            for(int j = 0; j <=i; j++)
            {
                System.out.print(j+1);
            }
             System.out.println();
        }
    }
}
```

