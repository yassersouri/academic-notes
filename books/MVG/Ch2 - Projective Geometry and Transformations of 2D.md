#Projective Geometry and Transformations of 2D

##The 2D Projective plane

**Row and Column Vectors.** Geometric entities will by default be represented by column vectors. A bold-face symbol such as $x$ always represents a column vector. In accordance with this convention a point in the plane will be represented by the column vector $(x,y)^T$.

###Points and lines

**Homogeneous representation of lines.** A line in the plane is represented by an equation such as $ax + by + c = 0$, thus a line may naturally be represented by the vector $(a,b,c)^T$. The correspondence between lines and vectors is not one-to-one, since the lines $ax + by + c = 0$ and $(ka)x + (kb)y + (kc) = 0$ are the same, for any non-zero constant $k$. The set of equivalence classes of vectors in $\rm I\!R^3 - (0,0,0)^T$ forms the _projective_ space $\rm I\!P^2$.

**Homogeneous presentation of points.** An arbitrary homogeneous vector representative of a point is of the form $\textbf{x} = (x_{1}, x_{2}, x_{3})^T$, representing the point $(x_{1}/x_{3}, x_{2}/x_{3})$ in $\rm I\!R^2$. Points, then, as homogeneous vectors are also elements of $\rm I\!P^2$. 

**Result 1.** The point $\textbf{x}$ lies on the line $\textbf{l}$ if and only if $\textbf{x}^T\textbf{l} = 0$.

**Degrees of freedom (dof).**