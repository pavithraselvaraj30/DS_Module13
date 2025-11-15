# EX 1 You’re creating a health monitoring device which stores several sensor readings in an array. To determine the minimum value (e.g., lowest heartbeat), implement a recursive method.
## DATE:15.11.25
## AIM:
To write a JAVA program To determine the minimum value (e.g., lowest heartbeat), implement a recursive method.

## Algorithm
1. Read matrix dimensions Input the number of rows r and columns c.
2. Read elements of Matrix A Fill the 2D array A[r][c] by reading integers row-wise
3. Read elements of Matrix B Fill the 2D array B[r][c] similarly by reading integers row-wise.
4. Add corresponding elements of both matrices For each position (i, j), compute A[i][j] + B[i][j]. 
5. Print the resulting matrix Output each sum in matrix form, one row per line.  

## Program:
```

/*
Program to ind the nature of resultant matrrix.
Developed by: PAVITHRA S
RegisterNumber: 212223230147
import java.util.*;

public class MatrixAddShort {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int r = sc.nextInt(), c = sc.nextInt();
        int[][] A = new int[r][c], B = new int[r][c];

        for (int i = 0; i < r; i++)  
            for (int j = 0; j < c; j++)
                A[i][j] = sc.nextInt();

        for (int i = 0; i < r; i++)  
            for (int j = 0; j < c; j++)
                B[i][j] = sc.nextInt();

       
        for (int i = 0; i < r; i++) {
            for (int j = 0; j < c; j++)
                System.out.print((A[i][j] + B[i][j]) + " ");
            System.out.println();
        }
    }
}
*/
```

## Output:

<img width="451" height="704" alt="514296362-4100fb70-69a4-4f08-aa17-86d01d55c951" src="https://github.com/user-attachments/assets/c952fa6d-4c54-46c6-8979-eed7f8126498" />


## Result:
Thus the JAVA prograM ti find the minimum value (e.g., lowest heartbeat), implement a recursive method has implemented successfully
