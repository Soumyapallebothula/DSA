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

Print Below Pattern:

1<br>
2 2 <br>
3 3 3<br>
4 4 4 4<br>
5 5 5 5 5<br>

```java
import java.util.Scanner;
class Main{
    public static void main (String args[]){
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        for(int i=0;i<n;i++){
            
            for(int j = 0; j <=i; j++)
            {
                System.out.print(i+1);
            }
             System.out.println();
        }
    }
}
```

Print the below pattern:

*****<br>
****<br>
***<br>
**<br>
*

``` JAVA
import java.util.Scanner;
class Main
{
    public static void main (String args[]){
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        for(int i = 1;i<=n;i++){
            
            for(int j = 0; j < n-i+1; j++)
            {
                System.out.print("*");
            }
             System.out.println();
        }
    }
}
```
Print the below pattern:

12345<br>
1234<br>
123<br>
12<br>
1<br>


```java
import java.util.Scanner;
public class Main
{
	public static void main(String[] args) {
	    Scanner sc = new Scanner(System.in);
	    int n = sc.nextInt();
	    for(int i=1;i<=n;i++){
	     for(int j = 0 ; j<n-i+1;j++){
	         System.out.print(j+1);
	     }
	     System.out.println();
	 }
	}
}
```


