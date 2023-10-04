---
layout: post
title: "Quadrea of a Projective Quadrangle Theorem"
subtitle: "Employing Archimedes function to help discover and prove exact formulas for the quadrea of a projective quadrangle and the corresponding dual, the quadreal of a projective quadrilateral, in Universal Hyperbolic Geometry"
date: 2023-10-04 10:52:13 -0400
background: '/assets/images/SOA_Archimedes.jpg'
---

## Quadrea of a Projective Quadrangle in Universal Hyperbolic Geometry

Here is the main theorem that we will prove for a general projective quadrangle in UHG consisting of projective points $a_{1}$, $a_{2}$, $a_{3}$ and $a_{4}$ as depicted in the following diagram.

<img src="/blog/assets/images/UHGModel.png"  width="60%" height="60%">

### Quadrea of a Projective Quadrangle Theorem


 Suppose $a_{1}$, $a_{2}$, $a_{3}$ and $a_{4}$ are distinct points of a general projective quadrangle with quadrances $q_{12} \equiv q(a_1,a_2)$, $q_{23} \equiv q(a_2,a_3)$, $q_{34} \equiv q(a_3,a_4)$ and  $q_{41} \equiv q(a_4,a_1)$ and spreads $S_1 \equiv S(a_{4}a_{1},a_{1}a_{2})$, $S_2 \equiv S(a_{1}a_{2},a_{2}a_{3})$, $S_3 \equiv S(a_{2}a_{3},a_{3}a_{4})$ and $S_4 \equiv S(a_{3}a_{4},a_{4}a_{1})$ and quadrea $\mathcal{B}$. Then the quadrea of the projective quadrangle is the common solution to the following pair of compatible quadratic equations


$$\begin{split}
(\mathcal{B}-q_{12}q_{23}S_{2} - q_{34}q_{41}S_{4})^2 &= q_{12}q_{23}q_{34}q_{41}(1-S_{1})(1-S_{3})\\
(\mathcal{B}-q_{41}q_{12}S_{1} - q_{23}q_{34}S_{3})^2 &= q_{12}q_{23}q_{34}q_{41}(1-S_{2})(1-S_{4})
\end{split}$$

If $q_{12}q_{23}S_{2} + q_{34}q_{41}S_{4} -q_{41}q_{12}S_{1} - q_{23}q_{34}S_{3} \neq 0$ then the quadrea is precisely 

$$\begin{split}\mathcal{B} = \frac{q_{12}q_{23}S_{2} + q_{34}q_{41}S_{4} + q_{41}q_{12}S_{1} + q_{23}q_{34}S_{3}}{2}\quad + \\ \frac{q_{12}q_{23}q_{34}q_{41}((1-S_{1})(1-S_{3}) - (1-S_{2})(1-S_{4}))}{2(q_{12}q_{23}S_{2} + q_{34}q_{41}S_{4} - q_{41}q_{12}S_{1} - q_{23}q_{34}S_{3})}\end{split}$$
   

| Triangulation 1  | &nbsp; &nbsp; Triangulation 2 |
| :---: | :---: | 
| <img src="/blog/assets/images/QuadrangleTriangulation1.png"  width="40%" height="40%"> | <img src="/blog/assets/images/QuadrangleTriangulation1.png"  width="40%" height="40%"> |
| $$\begin{split}
(\mathcal{B}-q_{12}q_{23}S_{2} - q_{34}q_{41}S_{4})^2 = \hspace{0.5in} \\ q_{12}q_{23}q_{34}q_{41}(1-S_{1})(1-S_{3})
\end{split}$$   | $$\begin{split}
(\mathcal{B}-q_{41}q_{12}S_{1} - q_{23}q_{34}S_{3})^2 = \hspace{0.5in} \\ q_{12}q_{23}q_{34}q_{41}(1-S_{2})(1-S_{4})
\end{split}$$   |





##### Using full url

![example image](https://raw.githubusercontent.com/jcoady/blog/master/assets/uhg1.jpg "An exemplary image")

<img src="https://raw.githubusercontent.com/jcoady/blog/master/assets/uhg1.jpg"  width="60%" height="60%">
<img src="https://raw.githubusercontent.com/jcoady/blog/master/assets/uhg1.jpg"  width="30%" height="30%">


![example image](https://raw.githubusercontent.com/jcoady/blog/master/assets/images/SOA_tiling3.png "An exemplary image")  
<img src="https://raw.githubusercontent.com/jcoady/blog/master/assets/images/SOA_tiling3.png"  width="60%" height="60%">
![hyperbolic image](https://raw.githubusercontent.com/jcoady/blog/master/assets/images/SOA_tiling3.png "Hyperbolic School Of Athens")  
![example image](https://raw.githubusercontent.com/jcoady/blog/master/assets/images/BeltramiKleinModel.png "An exemplary image")  
![example image](https://raw.githubusercontent.com/jcoady/blog/master/assets/images/QuadrangleTriangulation1.png "An exemplary image")  
![example image](https://raw.githubusercontent.com/jcoady/blog/master/assets/images/QuadrangleTriangulation2.png "An exemplary image")  
![example image](https://raw.githubusercontent.com/jcoady/blog/master/assets/images/UHGModel.png "An exemplary image")  

##### Using pathname

![example image](/blog/assets/uhg1.jpg "An exemplary image")

<img src="/blog/assets/uhg1.jpg"  width="60%" height="60%">
<img src="/blog/assets/uhg1.jpg"  width="30%" height="30%">


![example image](/blog/assets/images/SOA_tiling3.png "An exemplary image")  
<img src="/blog/assets/images/SOA_tiling3.png"  width="60%" height="60%">
![hyperbolic image](/blog/assets/images/SOA_tiling3.png "Hyperbolic School Of Athens")  
![example image](/blog/assets/images/BeltramiKleinModel.png "An exemplary image")  
![example image](/blog/assets/images/QuadrangleTriangulation1.png "An exemplary image")  
![example image](/blog/assets/images/QuadrangleTriangulation2.png "An exemplary image")  
![example image](/blog/assets/images/UHGModel.png "An exemplary image")  

Inline math equations go in like so: $\omega = d\phi / dt$. Display
math should get its own line and be put in in double-dollarsigns:

$$I = \int \rho R^{2} dV$$

When $a \ne 0$, there are two solutions to $(ax^2 + bx + c = 0)$ and they are 
$$ x = {-b \pm \sqrt{b^2-4ac} \over 2a} $$

The quadrance between points: 
  $$q(a_1,a_2) \equiv 1 - \frac{(x_1x_2 + y_1y_2 - z_1z_2)^2}{(x_1^2 + y_1^2 - z_1^2)(x_2^2 + y_2^2 - z_2^2)}$$

The spread between lines S(L_1,L_2): 
  $$S(L_1,L_2) \equiv 1 - \frac{(l_1l_2 + m_1m_2 - n_1n_2)^2}{(l_1^2 + m_1^2 - n_1^2)(l_2^2 + m_2^2 - n_2^2)}$$

The quadrance between points:   
  \[q(a_1,a_2) \equiv 1 - \frac{(x_1x_2 + y_1y_2 - z_1z_2)^2}{(x_1^2 + y_1^2 - z_1^2)(x_2^2 + y_2^2 - z_2^2)}\]

The spread between lines S(L_1,L_2): 
  \[S(L_1,L_2) \equiv 1 - \frac{(l_1l_2 + m_1m_2 - n_1n_2)^2}{(l_1^2 + m_1^2 - n_1^2)(l_2^2 + m_2^2 - n_2^2)}\]


Quadrea of a triangle $\mathcal{A}(\overline{a_1a_2a_3}) = q_1q_2S_3 = q_2q_3S_1 = q_1q_3S_2$ by symmetry.$$q_2q_3S_1 = -\frac{(x_1y_2z_3-x_1y_3z_2+x_2y_3z_1-x_3y_2z_1+x_3y_1z_2-x_2y_1z_3)^2}{(x_1^2+y_1^2-z_1^2)(x_2^2+y_2^2-z_2^2)(x_3^2+y_3^2-z_3^2)}$$  
This turns out to be the most important triangle invariant [<cite> Norman Wildberger</cite>][njwildberger_2011_UHG27]
under scaling of any one of the coordinates $a_1, a_2$ or $a_3$.  

 $q_1, q_2, q_3, q_4, S_1, S_2, S_3 and S_4$


$$q_1 = quadrance(a_1, a_2) = 1 - \frac{(x_1x_2 + y_1y_2 - z_1z_2)^2}{(x_1^2 + y_1^2 - z_1^2)(x_2^2 + y_2^2 - z_2^2)}$$

$$S_1 = quadrance(L_{41}, L_{12}) = 1 - \frac{(x_1x_2 + y_1y_2 - z_1z_2)^2}{(x_1^2 + y_1^2 - z_1^2)(x_2^2 + y_2^2 - z_2^2)}$$

[njwildberger_2011_UHG27]: https://www.youtube.com/watch?v=Qy8qpTtowYA&list=PLIljB45xT85CN9oJ4gYkuSQQhAtpIucuI&index=29


| Syntax      |   &nbsp; &nbsp; Description |
| :---------: | :------------: |
| :heavy_check_mark: | :x: |
| :x: | :heavy_check_mark: |
| :heavy_check_mark: | :x: |


| Formula     |  Affine Geometry &nbsp; &nbsp; &nbsp; &nbsp; <br> (Rational Trigonometry)  | &nbsp; &nbsp; Projective Geometry &nbsp; &nbsp;<br> (Universal Hyperbolic Geometry) |
| :--- | :---: | :---: | 
| Pythagoras | $Q_1 + Q_2 = Q_3$ | $q_3 = q_1 + q_2 - q_1q_2$ |
| Triple quad formula | $$(Q_1 + Q_2 + Q_3)^2 = 2(Q_1^2 + Q_2^2 + Q_3^2)$$ | $$\begin{split}(q_1 + q_2 + q_3)^2 = \hspace{1in} \\ 2(q_1^2 + q_2^2 + q_3^2) + 4q_1q_2q_3\end{split}$$ |
|Spread <br>law | $$\frac{s_1}{Q_1} = \frac{s_2}{Q_2} = \frac{s_3}{Q_3}$$  |  $$\frac{S_1}{q_1} = \frac{S_2}{q_2} = \frac{S_3}{q_3}$$  |
| Cross Law | $$(Q_1 + Q_2 - Q_3)^2 = 4Q_1Q_2(1-s_3)$$ | $$\begin{split}(q_1q_2S_3 - q_1 - q_2 - q_3 + 2)^2 = \hspace{0.5in} \\ 4(1-q_1)(1-q_2)(1-q_3)\end{split}$$ |
| Triple spread  formula | $$\begin{split}(s_1 + s_2 + s_3)^2 = \hspace{1in} \\ 2(s_1^2 + s_2^2 + s_3^2) + 4s_1s_2s_3\end{split}$$ | not applicable |  

Table 1: Main Laws of Rational Trigonometry and Universal Hyperbolic Geometry


|---------+---------+---------|
| Header1 | Header2 | Header3 |
|---------|:--------|--------:|
| 1       | 2       | 3       |
| 4       | 5       | 6       |
|---------+---------+---------|
| 8       | 95      | 106     |
| 894     | 345     | 866     |
|=========+=========+=========|
| Foot1   | Foot2   | Foot3   |
|---------+---------+---------|



<script src="https://giscus.app/client.js"
        data-repo="jcoady/blog"
        data-repo-id="R_kgDOKZDDqA"
        data-category="blog comments"
        data-category-id="DIC_kwDOKZDDqM4CZzR4"
        data-mapping="pathname"
        data-strict="0"
        data-reactions-enabled="1"
        data-emit-metadata="0"
        data-input-position="top"
        data-theme="preferred_color_scheme"
        data-lang="en"
        data-loading="lazy"
        crossorigin="anonymous"
        async>
</script>

