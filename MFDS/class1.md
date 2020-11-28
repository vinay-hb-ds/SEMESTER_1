Scalar
Vectors
Rank of a matrix
Upper triangular matrix
Transpose of a matrix
###Matrix
A matrix is a rectangular array of numbers enclosed in a bracket.
It is represented as A or [A]
### Vector
```
Matrix which has single row or sinngle columnn is called vector annd its entries are called as components of vectos.
Matrix which has single row is called row vector and the component which has single column is called as column vector.  
```
### Square matrix
` A matrix which has same number of rows and columns is called as square matriz `
### Matrix operation rules
```
[A] = [B] if and only if a[i][j] = b[i][j] for all the i,j

Matrix Addition
[C] = [A] + [B] --> c[i][j] = a[i][j] + b[i][j]

Matrix substraction
[C] = [A] - [B] --> c[i][j] = a[i][j] - b[i][j]

The commutative property states that the numbers on which we operate can be moved or swapped from their position without making any difference to the answer.
This property holds for Addition and Multiplication not on substraction and division.

Matrix Addition and substraction are commutative and associative

[A] + [B] = [B] + [A] 
[A] - [B] = -[B] + [A]

Associative property states that you can add or multiply regardless of how the numbers are grouped(how you use parenthesis).
[A] + ( [B] + [C] ) = ( [A] + [B] )+ [C]  

Multiplication of matrix by a scalar
[A] =   a11 a12 a13
        b11 b12 b13
        c11 c12 c13
[B] = [A] g =   a11*g a12*g a13*g
                b11*g b12*g b13*g
                c11*g c12*g c13*g
Matrix multiplication
Matrix multiplications can only be performed if the inner dimensions are equal

[A] m*n can be only be multiplied with [B] n*l i.e columns of first matrix should be equal to rows of second column.

[A] m*n * [B] n*l = [C]m*l

[A] * [B] != [B] [A]
If [A]*[B] = 0 does not imply [A]=0 or [B] = 0
[B]*[A]=0
if [A]*[C] = [A]*[D] does not imply [C] = [D]

```
##Special matrices
###Zero matrix or null matrix
Zero matrix or null matrix is a matrix all of whose elements are zeros.
###Diagonal matrix
In linear algebra, a diagonal matrix is a matrix in which the entries outside the main diagonal are all zero, the term usually refers to a square matrix.
###Identity matrix
Identity matrix is a diagonal matrix in which all the diagonal elements are one.        

Diagonal matrix [A] and identity matrix [I]
[A] * [I] = [I] * [A] =[A]
### Lower triangular matrix
If all the elements in a lower diagonal of a square matrix are non zeros and all the elements above main diagonal are zeros

### Upper triangular matrix
If all the elements below main diagonal of a square matrix are zeros and all the elements above main diagonal are non zeros

### Transpose of a matrix
In linear algebra, the transpose of a matrix is an operator which flips a matrix over its diagonal, that is it switches the rows and column indices.
[A]`T`

### Trace of a matrix
Its the sum of diagonal elements of a square matrix

### Symmetric matrix
Symmetric matrix is a square matrix that is equal to its transpose.
Only square matrix can be symmetric
[A] =  [A]`T`
a[i][j] = a[j][i]

### Skew Symmetric matrix
Skew symmetric is a square matrix whose transpose is equal to its negative.
[A] = -[A]`T`
a[i][j] = -a[j][i]
that means a[j][j]=0 all diagonal values should be zero

### Determinant of a matrix
Scalar is a an element of a field which is used to define the vector space.
The determinant is a scalar value that can be computed from the elements of a square matrix
Determinant of matrix A is denoted by det(A), det A, |A|

[A] =   2   5
        4   3
|A| = 2*3 - 4*5 = 6 - 20 = -14
### Minor of an elemenet in square matrix
```
Consider [A] =  a11   a12   a13
                a21   a22   a23
                a31   a32   a33

Determinant of this matrix 
|A| = a11 { (-1 power of 1(row#)+1(column#)) (a22*a33 - a32*a23)} +  a12 { (-1 power of 1+2) (a21*a33 - a31*a23) } + a13 { (-1 popwer of 1+3) (a12*a32 - a31*a22)}

Here for a11 (a22*a33 - a32*a23) is minor and { (-1 power of 1(row#)+1(column#)) (a22*a33 - a32*a23)} is cofactor
```
### Rank of a matrix
Rank of a matrix is order of the highest order non zero minor.
Denoted by p(A) or Rank(A)


