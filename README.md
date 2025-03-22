# DSA_Crossword_Puzzle - Question Statement.

You have an ``` N x N ``` matrix filled with letters ```(A-Z)``` and an array of ```M``` strings. <br>
Your task is to check if each of the ```M``` strings can be found in the matrix. 


## Input Format

The matrix dimension ```N``` is between ```2``` and 10<sup>8</sup>. <br>
The array ```M``` has 1 to 100 strings. 


## Output Format

Output ```'Yes'``` for each string that exists in the matrix, and ```'No'``` if it doesn't.



### Example 1

```Input matrix```

Idx&nbsp;&nbsp; 1&nbsp;   2&nbsp;   3&nbsp;   4&nbsp;   5&nbsp;   6&nbsp;   7&nbsp;   8&nbsp;   <br>
1&nbsp;&nbsp;   C&nbsp;   O&nbsp;   M&nbsp;   A&nbsp;   T&nbsp;   F&nbsp;   B&nbsp;   S&nbsp;   <br>
2&nbsp;&nbsp;   R&nbsp;   O&nbsp;   G&nbsp;   A&nbsp;   A&nbsp;   O&nbsp;   A&nbsp;   A&nbsp;   <br>
3&nbsp;&nbsp;   E&nbsp;   G&nbsp;   M&nbsp;   L&nbsp;   S&nbsp;   A&nbsp;   L&nbsp;   M&nbsp;   <br>
4&nbsp;&nbsp;   E&nbsp;   G&nbsp;   O&nbsp;   P&nbsp;   H&nbsp;   S&nbsp;   L&nbsp;   P&nbsp;   <br>
5&nbsp;&nbsp;   D&nbsp;   Y&nbsp;   W&nbsp;   H&nbsp;   U&nbsp;   M&nbsp;   E&nbsp;   L&nbsp;   <br>
6&nbsp;&nbsp;   D&nbsp;   J&nbsp;   E&nbsp;   A&nbsp;   Y&nbsp;   T&nbsp;   R&nbsp;   E&nbsp;   <br>
7&nbsp;&nbsp;   O&nbsp;   K&nbsp;   U&nbsp;   A&nbsp;   Z&nbsp;   D&nbsp;   E&nbsp;   R&nbsp;   <br>
8&nbsp;&nbsp;   M&nbsp;   E&nbsp;   T&nbsp;   A&nbsp;   D&nbsp;   A&nbsp;   T&nbsp;   R&nbsp;   <br>

```Input m Array ```

```js
const m = ["COMPUTER", "ALPHA", "META", "METADATA"]
```

```Output```

```js
res = ["Yes","Yes","Yes","No"]
```

```Solution```

Idx&nbsp;&nbsp; 1&nbsp;   2&nbsp;   3&nbsp;   4&nbsp;   5&nbsp;   6&nbsp;   7&nbsp;   8&nbsp;   <br>
1&nbsp;&nbsp;   ```C```&nbsp;   O&nbsp;   M&nbsp;   A&nbsp;   T&nbsp;   F&nbsp;   B&nbsp;   S&nbsp;   <br>
2&nbsp;&nbsp;   R&nbsp;   ```O```&nbsp;   G&nbsp;   ```A```&nbsp;   A&nbsp;   O&nbsp;   A&nbsp;   A&nbsp;   <br>
3&nbsp;&nbsp;   E&nbsp;   G&nbsp;   ```M```&nbsp;   ```L```&nbsp;   S&nbsp;   A&nbsp;   L&nbsp;   M&nbsp;   <br>
4&nbsp;&nbsp;   E&nbsp;   G&nbsp;   O&nbsp;   ```P```&nbsp;   H&nbsp;   S&nbsp;   L&nbsp;   P&nbsp;   <br>
5&nbsp;&nbsp;   D&nbsp;   Y&nbsp;   W&nbsp;   ```H```&nbsp;   ```U```&nbsp;   M&nbsp;   E&nbsp;   L&nbsp;   <br>
6&nbsp;&nbsp;   D&nbsp;   J&nbsp;   E&nbsp;    ```A```&nbsp;   Y&nbsp;   ```T```&nbsp;   R&nbsp;   E&nbsp;   <br>
7&nbsp;&nbsp;   O&nbsp;   K&nbsp;   U&nbsp;   A&nbsp;   Z&nbsp;   D&nbsp;   ```E```&nbsp;   R&nbsp;   <br>
8&nbsp;&nbsp;   ```M```&nbsp;   ```E```&nbsp;   ```T```&nbsp;   ```A```&nbsp;   D&nbsp;   A&nbsp;   T&nbsp;   ```R```&nbsp;   <br>