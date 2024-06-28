<h5>Square fill pattern</h5>

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
                System.out.print("*"); // print method continue => print
            }
            System.out.println();
        }

    }
}
```
<h5>Output</h5>

```
Enter rows value: 7
*******
*******
*******
*******
*******
*******
*******
```

