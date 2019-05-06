# Linear-Algebra
![Linear Algebra](https://raw.githubusercontent.com/BasileBron/Linear-Algebra/master/img/banner_github.jpg)

This repository was made during my personal preparation for the "Computer Science and Artificial Intelligence BSc (Hons)" at the university of Sussex. **Linear Algebra** being one of the **main pillar** of **machine learning** I had to get a better grasp than I had learned in school.

Linear Algebra is a branch of mathematics that deals with linear equations and linear functions which are represented through **matrices** and **vectors**. In simpler words, LA helps you understand geometric terms such as planes, in higher dimensions, and perform mathematical operations on them. By definition, algebra deals primarily with scalars (one-dimensional entities), but LA has vectors and matrices (entities which possess two or more dimensional components) to deal with linear equations and functions.


## Vector
vectors are a combination of two value **x and y** in a 2 Dimension space.
or a combination of tree value **x ,y and z** in a 3 Dimensional space.

### Notation

#### Magnitude
The **Magnitude is the lenght** of a vector
**i.g** the "hypotenuse" of a triangle that a 2d Vector would form is the magnitude.

#### Unit Vector / Identity Vector
Unit vectors are vectors whose magnitude is exactly 1 unit. They are very useful for different reasons. Specifically, the unit vectors [0,1] and [1,0] can **form** together **any other vector**.

**i.e** the unit û of the vector (a,b) will be ![Magnitude](https://raw.githubusercontent.com/BasileBron/Linear-Algebra/master/img/magnitude.png)

basically just divide each number by the magnitude of the vector.
**i.g** the unit û of the vector (3,4) will be (⅗,⅘)

#### Scalar
A scalar is a value that will **scale** the vector by multiplying it.

### Basic Concept
#### Linear dependency
##### Linear dependent
A linearly dependent vector can be a combination of other vector of the set.

**i.g** the set of vectors **[1,2] [3,2] [2,1]** is linearly dependent because we have 3 vector in two dimension and none of them are collinear or null. which means that you can already represent any point in the two dimension by using a combination of only two vector of this set.

**i.e** You can prove this mathematically by scaling each of this vector by a constant and if one of the content is not equals to zero then the set is linearly dependent.
(c1*[1,2]+c2[3,2]+c3[2,1])

[example on linearly dependence](https://www.khanacademy.org/math/linear-algebra/vectors-and-spaces/linear-independence/v/more-on-linear-independence)

##### Linear independent
A linearly independent vector **cannot be** a **combination** of other vector of the set.

**i.e** You can prove this by doing the same thing as above and if all of the constant must be equals to zero in order of the equation to be true then the set is linearly independent.
#### collinear
Two vetor that are on the same line.
**i.e** Have the same direction.
#### vector multiplication
##### Cross product
![dot product](https://raw.githubusercontent.com/BasileBron/Linear-Algebra/master/img/cross_product_formula.PNG)

The cross product tell you how much **perpendicular** the vectors are.

![hand cross product](https://raw.githubusercontent.com/BasileBron/Linear-Algebra/master/img/hand_cross_product.png)![cross product](https://raw.githubusercontent.com/BasileBron/Linear-Algebra/master/img/cross_product.gif)

[video explanation](https://www.youtube.com/watch?v=eu6i7WJeinw&t)
##### Dot product / Scalar product / Inner Product
![dot product](https://raw.githubusercontent.com/BasileBron/Linear-Algebra/master/img/dot_product_equation.PNG)
The dot product tell you how much **parallel** the vectors are.
or the "degree of correlation" between two vectors

![dot product](https://raw.githubusercontent.com/BasileBron/Linear-Algebra/master/img/dot_product.PNG)

[video explanation](https://www.youtube.com/watch?v=LyGKycYT2v0&t)


### Vector flashcard
___________________________________________________________
## Matrix
### Notation
#### Rank of a matrix
Maximum number of vector needed to represent any point in the space of the matrix
“basically number of dimension“
or more precisely the number of linearly independent vector

#### Basis of a matrix

#### Span of a matrix

### Method and equation
#### Matrix multiplication

#### gauss elimination
#### development of Laplace
#### method Cramer

## Acknowledgement

A huge thank to [khanacademy](https://www.khanacademy.org/) and [3 brown 1 blue](https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw/videos).
You make the education system look like an arrogant clown that isn't funny (and you pay 10k a year wasting your time everyday to hear him say that student are stupid #salt).

I couldn't have done this without you.
A thousand thanks!
