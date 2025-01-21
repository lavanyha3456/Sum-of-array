# Sum-of-array
public class SumOfArray {
public static void main(String[] args) {

int[] numbers = {5, 10, 15, 20, 25};

int sum = 0;

for (int num : numbers) {

sum += num;

}

System.out.println("Sum of elements: " + sum);

}

}

OUTPUT:

Sum of elements: 75

29. Matrix Addition

CODING:

public class MatrixAddition {

public static void main(String[] args) {

int[][] matrixA = {

{1, 2, 3},

{4, 5, 6}

};

int[][] matrixB = {

{7, 8, 9},

{10, 11, 12}

};

int[][] result = new int[2][3];

for (int i = 0; i < matrixA.length; i++) {

for (int j = 0; j < matrixA[i].length; j++) {

result[i][j] = matrixA[i][j] + matrixB[i][j];

}

}

System.out.println("Resultant matrix after addition:");

for (int[] row : result) {
for (int element : row) {

System.out.print(element + " ");

}

System.out.println();

}

}

}

OUTPUT:

Resultant matrix after addition:

8 10 12

14 16 18
