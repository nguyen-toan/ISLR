_**Support vector machine (SVM)**_ is an approach for classification developed in the 1990s and considered on of the best "out of the box" classifiers. It is a further extension of *maximal margin classifier* and *support vector classifier*.

<br>

#### 9.1 Maximal Margin Classifier

##### 9.1.1 What is a HyperPlane?
In a _p_-dimensional space, a _hyperplane_ is a flat affine subspace of dimension _p_-1 which is defined by the equation

<p align="center">
\(\beta \)<sub>0</sub> + \(\beta \)<sub>1</sub>X<sub>1</sub> + \(\beta \)<sub>2</sub>X<sub>2</sub> + ... + \(\beta \)<sub>p</sub>X<sub>p</sub> = 0   (9.2)
<p>

We can see that the hyperplace divides _p_-dimensional space into two halves and by simply calculating the sign of the left hand side of (9.2), one can determine on which side of a hyperplane a point X = (X<sub>1</sub>,X<sub>2</sub>,...,X<sub>p</sub>)<sup>T</sup> lies.

<figure align="center">
  <img src="../figures/Chapter9/9.1.pdf" width=300 height=300>
  <figcaption>**FIGURE 9.1**. _The hyperplane 1 + 2X<sub>1</sub> + 3X<sub>2</sub> = 0 is shown. The blue region is the set of points for which 1 + 2X<sub>1</sub> + 3X<sub>2</sub> > 0, and the purple region is the set of points for which 1 + 2X<sub>1</sub> + 3X<sub>2</sub> < 0._
  </figcaption>
</figure>
