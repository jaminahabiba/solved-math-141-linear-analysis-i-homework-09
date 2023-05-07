Download Link: https://assignmentchef.com/product/solved-math-141-linear-analysis-i-homework-09
<br>
<ol>

 <li>(<em>if you did not finish this last week</em>) <em>T </em>: R<em><sup>n </sup></em>→R<em><sup>m </sup></em>is a linear transformation.</li>

</ol>

<ul>

 <li>Is ker(<em>T</em>) a subspace of R<em><sup>n</sup></em>?. Explain your reasoning. If yes, how can you find a basis for ker(<em>T</em>)?</li>

 <li>Is range(<em>T</em>) a subspace of R<em><sup>m</sup></em>?. Explain your reasoning. If yes, how can you find a basis for range(<em>T</em>)?</li>

</ul>

(Hint: Connect ker(<em>T</em>) and range(<em>T</em>) to column space and nullspace of some matrix.) 2. <em>A</em><sub>7×5 </sub>is matrix with 7 rows and 5 columns. The columns of <em>A </em>satisfy

(<em>column</em>-3) = −5(<em>column</em>-2) + (<em>column</em>-4)<em>.</em>

Write down one concrete vector in <em>N</em>(<em>A</em>). Explain your reasoning.

<ol start="3">

 <li>In class, we agreed that <em>N</em>(<em>A</em>), the set of all solutions to, is a vector subspace. What about all solutions to an inhomogeneous system? More precisely, given a fixed matrix <em>A<sub>m</sub></em><sub>×<em>n </em></sub>and fixed right hand side vector <em><sup>~</sup></em>0 6=<em><sup>~</sup></em><em>b </em>in R<em><sup>m</sup></em>, define</li>

</ol>

<em>V </em>= {all solutions to <em>A~x </em><sup>=<em>~</em></sup><em>b</em>}<em>.</em>

Is <em>V </em>a vector subspace of R<em><sup>n</sup></em>?

<ol start="4">

 <li>In class, we discussed to think of matrix multiplication as composition of functions. We thought about how, if you have (<em>AB</em>)<em>~x</em>, where <em>A </em>and <em>B </em>are matrices and <em>~x </em>is a vector, (<em>AB</em>)<em>~x </em>= <em>A</em>(<em>B~x</em>) could be thought of as <em>B </em>transforming <em>~x </em>first, and then <em>A </em>transforming the result of <em>B~x</em>.</li>

</ol>

This exercise reinforces that connection. (a) Given functions <em>f </em>and <em>g </em>below

<em>f</em>(<em>x</em>) = 2<em>x </em>+ 4              <em>g</em>(<em>x</em>) = <em>x</em><sup>2</sup>− 3<em>x</em>

compute

<ol>

 <li><em>f</em>(<em>g</em>(<em>x</em>)) and <em>g</em>(<em>f</em>(<em>x</em>))</li>

 <li><em>f</em>(<em>g</em>(2)) and <em>g</em>(<em>f</em>(2))</li>

</ol>

(b) Let the matrices <em>F </em>and <em>G </em>be defined as below. Answer the following questions accordingly.

<ol>

 <li>Let , and let <em>G~x </em>= <em>~y</em>. Compute <em>G~x </em>and compute <em>F~y</em>.</li>

 <li>Let <em>~x </em>be the same vector as in i., and let <em>F~x </em>= <em>~u</em>. Compute <em>F~x </em>and compute <em>G~u</em>.</li>

</ol>

<ul>

 <li>Compute <em>FG </em>and <em>GF</em>.</li>

</ul>

<ul>

 <li>Summarize, in words, the similarities between matrix multiplication and composition of functions. Point out the equivalence, in terms of compositions of functions <em>f </em>and <em>g</em>, of the various quantities in part (b): <em>G~x</em>, <em>F~y</em>, <em>F~x</em>, <em>G~u</em>, <em>FG </em>and <em>GF</em>. All notations have the same meaning as in parts (a) and (b).</li>

 <li>Is matrix multiplication commutative (That is, <em>AB </em>= <em>BA </em>for any matrices <em>A </em>and <em>B</em>)? Why or why not?</li>

</ul>

When we solved the Italicizing N Task 1 problem in class, some groups have written all the input vectors side by side into a matrix and all the output vectors the same way:

We used that as an example to introduce one interpretation of matrix multiplication—-each column of the product matrix <em>AB </em>is the product of matrix <em>A </em>with the corresponding column vector of matrix <em>B</em>. Keep this interpretation in mind when answering following questions.

<ol start="5">

 <li>In order for us to be able to multiply two matrices <em>A </em>and <em>B </em>together, what conditions do we have to put on the shapes of <em>A </em>and <em>B</em>? What is the shape of the product matrix <em>AB</em>?</li>

 <li>(a) Fill in the blanks and explain your reasoning: Each column vector of the product matrix <em>AB </em>is a linear combination of , and so each column vector of <em>AB </em>is in the span of</li>

</ol>

(b) As a consequence of part (a), what can you say about the relation among three column spaces <em>C</em>(<em>AB</em>), <em>C</em>(<em>A</em>), and <em>C</em>(<em>B</em>)?

<ol start="7">

 <li>Assume that <em>AB </em>is defined. Determine the following statements true or false. If true, provide a justification. If false, provide a counterexample.</li>

</ol>

Hint: You may start by applying the definition of (in)dependence to columns of <em>A </em>or <em>B </em>and then try to multiply the equation by the other matrix.

<ul>

 <li>If the columns of <em>B </em>are linearly dependent, then so are the columns of <em>AB</em>.</li>

 <li>If the columns of <em>A </em>are linearly independent, then so are the columns of <em>AB</em>.</li>

</ul>

<ol start="8">

 <li>True of false? If true, explain why. If false, provide a counterexample. <em>A </em>and <em>B </em>are matrices of appropriate shape so that each addition or multiplication is defined.

  <ul>

   <li>If columns 1 and 3 of <em>B </em>are the same, so are columns 1 and 3 of <em>AB</em>.</li>

   <li>If <em>AB </em>and <em>BA </em>are defined then <em>A </em>and <em>B </em>are square.</li>

   <li>If <em>AB </em>and <em>BA </em>are defined then <em>AB </em>and <em>BA </em>are square.</li>

   <li>(<em>AB</em>)<sup>2 </sup>= <em>A</em><sup>2</sup><em>B</em><sup>2</sup>. (e) (<em>A </em>+ <em>B</em>)<sup>2 </sup>= <em>A</em><sup>2 </sup>+ 2<em>AB </em>+ <em>B</em><sup>2 </sup>(f) If <em>AB </em>= <em>B </em>then <em>A </em>= <em>I</em>.</li>

  </ul></li>

 <li>(<em>Strang, </em><em>1.6, #25</em>) Suppose that <em>A </em>is a 3×3 matrix with (Row-1)+(Row-2)=(Row-3).

  <ul>

   <li>Explain why cannot have a solution.</li>

   <li>Which right-hand sides might allow a solution to <em>A~x </em>=<em><sup>~</sup></em><em>b</em>?</li>

   <li>What happens to Row-3 if we perform forward elimination on <em>A</em>?</li>

   <li>Explain why each of the above three situations leads to the conclusion that <em>A </em>is not invertible? (Hint: Think in terms of the linear transformation <em>L<sub>A </sub></em>that <em>A </em>)</li>

  </ul></li>

 <li>(<em>Strang, </em><em>1.6, #40</em>) True or False. If true, explain why. If false, <strong><em>show a concrete counterexample</em></strong>. (Hint: Use the fact that <em>A </em>is invertible if and only if the linear transformation <em>L<sub>A </sub></em>which it defines is invertible.)

  <ul>

   <li>A 4×4 matrix with a row of zeros is not invertible.</li>

   <li>A matrix with 1’s down the main diagonal is invertible.</li>

   <li>If <em>A </em>is invertible, then <em>A</em><sup>−1 </sup>is invertible.</li>

  </ul></li>

</ol>