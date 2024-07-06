<h5>Square fill pattern</h5>
<h5>Pattern 1</h5>

```Java
import java.util.*; // import Scanner class
public class Pattern {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.print("Enter rows value: ");

        // integer value scanning to return, n
        int n = input.nextInt();
        for(int i = 1; i <= n; i++) {
            for(int j = 1; j <= n; j++) {
                System.out.print(i); // print method continue => print
            }
            System.out.println();
        }
    }
}
```
<h5>Output</h5>

```
Enter rows value: 5
11111
22222
33333
44444
55555
```
<h5>Pattern 2</h5>

```Java
import java.util.*; // import Scanner class
public class Pattern {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.print("Enter rows value: ");

        // integer value scanning to return, n
        int n = input.nextInt();
        for(int i = 1; i <= n; i++) {
            for(int j = 1; j <= n; j++) {
                System.out.print(n); // print method continue => print
            }
            System.out.println();
        }
    }
}
```
<h5>Output</h5>

```
Enter rows value: 5
55555
55555
55555
55555
55555
```
<h5>Square hollow pattern</h5>
<h5>Pattern 1</h5>

```Java
import java.util.*; // import Scanner class

public class Pattern {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.print("Enter rows value: ");

        int i, j; // declaring variables

        // integer value scanning to return, n
        int n = input.nextInt();
        for(i = 0; i < n; i++) {
            for(j = 0; j < n; j++) {
                if(i == 0 || j == 0 || i == n - 1 || j == n - 1) {
                    System.out.print(n); // print a character to form the border
                } else {
                    System.out.print(" "); // use print instead of spaces
                }
            }
            System.out.println(); // move to the next line after each row
        }
    }
}
```
<h5>Output</h5>

```
Enter rows value: 5
55555
5   5
5   5
5   5
55555
```
<h5>Number- increasing pyramid pattern</h5>
<h5>Pattern 1</h5>

```Java
import java.util.*;
class Pattern {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.print("Enter rows: ");

        // Read scanning to store variable
        int n = input.nextInt();

        for(int i = 1; i <= n; i++) { 
            for(int j = 1; j <= i; j++) {
                System.out.print(i);
            }
            System.out.println(); // NextLine allocated
        }
    }
}
```
<h5>Output</h5>

```
Enter rows: 7
1
22
333
4444
55555
666666
7777777
```
<h5>Pattern 2</h5>

```Java
import java.util.*;
class Pattern {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.print("Enter rows: ");

        // Read scanning to store variable
        int n = input.nextInt();

        for(int i = 1; i <= n; i++) { 
            for(int j = 1; j <= i; j++) {
                System.out.print(j);
            }
            System.out.println(); // NextLine allocated
        }
    }
}
```
<h5>Output</h5>

```
Enter rows: 5
1
12
123
1234
12345
```
<h5>Pattern 3</h5>

```Java
import java.util.*;
class Pattern {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.print("Enter rows: ");

        // Declared variable
        int i, j;
        int num = 1;

        // Read scanning to store variable
        int n = input.nextInt();

        for(i = 1; i <= n; i++) { 
            for(j = 1; j <= i; j++) {
                System.out.print(num + " ");
                num++;
            }
            System.out.println(); // NextLine allocated
        }
    }
}
```
<Output>

```
Enter rows: 6
1
2 3 
4 5 6
7 8 9 10
11 12 13 14 15
16 17 18 19 20 21
```
<h5>Triangle pattern</h5>

```Java
class Pattern {
    public static void main(String[] args) {
        int n = 6; // num of rows

        for(int i = 1; i <= n; i++) {
            // print leading spaces
            for(int j = i; j < n; j++) {
                System.out.print(" ");
            }
            // print the number i times
            for(int j = 1; j <= i; j++) {
                System.out.print(i + " ");
            }
            System.out.println();
        }
    }
}
```
<h5>Output</h5>

```
     1 
    2 2
   3 3 3
  4 4 4 4
 5 5 5 5 5
6 6 6 6 6 6
```

