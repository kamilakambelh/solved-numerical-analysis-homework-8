Download Link: https://assignmentchef.com/product/solved-numerical-analysis-homework-8
<br>



<ul>

 <li>To get full credit, <em>you must write down sufficient intermediate steps</em>, only giving the final answer earns you no credit!</li>

 <li>Please make sure that your handwriting is recognizable, otherwise you only get partial credit for the recognizable part.</li>

</ul>

<ol start="6">

 <li>Prove Theorem 6.3 by assuming that ∀<em>x </em>∈ (<em>a,b</em>) the weight function <em>ρ</em>(<em>x</em>) <em>&gt; </em></li>

 <li>Consider the Chebyshev polynomials of the firstkind.

  <ul>

   <li>Show that they are orthogonal on [−1<em>,</em>1] with respect to the inner product in Theorem 6.3 with the weight function.</li>

   <li>Normalize the first three Chebyshev polynomialsto arrive at an orthonormal system.</li>

  </ul></li>

</ol>

<ul>

 <li>Least-square approximation of a continuous function.Approximate the circular arc given by the equation√</li>

</ul>

<em>y</em>(<em>x</em>) = 1 − <em>x</em><sup>2 </sup>for <em>x </em>∈ [−1<em>,</em>1] by a quadratic polynomial with respect to the inner product in Theorem

6.3.

with Fourier expansion,

with normal equations,

<ol>

 <li>Discrete least square via orthonormal polynomials.Consider the example on the table of sales record in the notes.

  <ul>

   <li>Starting from the independent list (1<em>,x,x</em><sup>2</sup>), construct orthonormal polynomials by the GramSchmidt process using</li>

  </ul></li>

</ol>

<em>N </em>h<em>u</em>(<em>t</em>)<em>,v</em>(<em>t</em>)i = <sup>X</sup><em>ρ</em>(<em>t<sub>i</sub></em>)<em>u</em>(<em>t<sub>i</sub></em>)<em>v</em>(<em>t<sub>i</sub></em>)              (1)

<em>i</em>=1 as the inner product with <em>N </em>= 12 and <em>ρ</em>(<em>x</em>) = 1.

<ul>

 <li>Find the best approximation ˆ<em>ϕ </em>=such that for all <em>b<sub>i </sub></em>∈ R.</li>

</ul>

Verify that ˆ<em>ϕ </em>is the same as that of the example on the table of sales record in the notes.

<table width="273">

 <tbody>

  <tr>

   <td width="23">x</td>

   <td width="41">0.0</td>

   <td width="33">0.5</td>

   <td width="33">1.0</td>

   <td width="33">1.5</td>

   <td width="40">2.0</td>

   <td width="40">2.5</td>

   <td width="32">3.0</td>

  </tr>

  <tr>

   <td width="23">y</td>

   <td width="41">2.9</td>

   <td width="33">2.7</td>

   <td width="33">4.8</td>

   <td width="33">5.3</td>

   <td width="40">7.1</td>

   <td width="40">7.6</td>

   <td width="32">7.7</td>

  </tr>

  <tr>

   <td width="23">x</td>

   <td width="41">3.5</td>

   <td width="33">4.0</td>

   <td width="33">4.5</td>

   <td width="33">5.0</td>

   <td width="40">5.5</td>

   <td width="40">6.0</td>

   <td width="32">6.5</td>

  </tr>

  <tr>

   <td width="23">y</td>

   <td width="41">7.6</td>

   <td width="33">9.4</td>

   <td width="33">9.0</td>

   <td width="33">9.6</td>

   <td width="40">10.0</td>

   <td width="40">10.2</td>

   <td width="32">9.7</td>

  </tr>

  <tr>

   <td width="23">x</td>

   <td width="41">7.0</td>

   <td width="33">7.5</td>

   <td width="33">8.0</td>

   <td width="33">8.5</td>

   <td width="40">9.0</td>

   <td width="40">9.5</td>

   <td width="32">10.0</td>

  </tr>

  <tr>

   <td width="23">y</td>

   <td width="41">8.3</td>

   <td width="33">8.4</td>

   <td width="33">9.0</td>

   <td width="33">8.3</td>

   <td width="40">6.6</td>

   <td width="40">6.7</td>

   <td width="32">4.1</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Suppose there are other tables of sales record inthe same format as that in the example . Values of <em>N </em>and <em>x<sub>i</sub></em>’s are the same, but the values of <em>y<sub>i</sub></em>’s are different. Which of the above calculations can be reused? Which cannot be reused? What advantage of orthonormal polynomials over normal equations does this reuse imply?</li>

</ul>

The first three problems weigh 6 points each while the last problem weighs 12 points.

<h1>2           C++ programming</h1>

Write a C++ function to perform discrete least square via normal equations. Your subroutine should take two arrays <em>x </em>and <em>y </em>as the input and output three coefficients <em>a</em><sub>0</sub><em>,a</em><sub>1</sub><em>,a</em><sub>2 </sub>that determines a quadratic polynomial as the best fitting polynomial in the sense of least squares with the weight function <em>ρ </em>= 1.

Run your subroutine on the following data.

This programming assignment weighs 10 points. Thus the total point of this homework is thus 40.