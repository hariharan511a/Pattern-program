<h5>Triangle pattern</h5>
<p>Increasing triangle</p>
<ol>
  <li>Left increasing triangle</li>
  <li>Right increasing triangle</li>
</ol>
<p>Decreasing triangle</p>
<ol>
  <li>Left decreasing triangle</li>
  <li>Right decreasing triangle</li>
</ol>

<p>Left increasing triangle</p>

```Java
class Pattern {
    public static void main(String[] args) {
        int n = 6;

        for (int i = 1; i <= n; i++) {
            for (int j = 1; j <= i; j++) {
                System.out.print("*");     
            }
            System.out.println();
        }
    }
}
====================================================

* 
* * 
* * * 
* * * * 
* * * * * 
```
