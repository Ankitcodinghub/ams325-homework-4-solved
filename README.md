# ams325-homework-4-solved
**TO GET THIS SOLUTION VISIT:** [AMS325 Homework 4 Solved](https://www.ankitcodinghub.com/product/ams325-homework-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94157&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;5&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (5 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;AMS325 Homework 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (5 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

In this homework, you will write Python scripts (.py files, instead of Jupyter Notebook) using NumPy, SciPy, and Matplotlib. As in Homework #2, you will also need to use github for the version control and submission of your source code (bonus).

1 Tasks

There are two tasks (mini-projects) for this assignment.

1.1 Task 1: Mandelbrot Sets

The Mandelbrot set is the set of complex numbers c for which the function fc(z) = z2 +c does not diverge when iterated from z = 0. In other words, the sequence fc(0), fc(fc(0)), etc. remains bounded in absolute value. In this task, you will write a Python script mandelbrot.py to compute the Mandelbrot fractal with the following Mandelbrot iteration on each point:

N_max = 50 threshold = 50 c = x + 1j∗y

z=0

for j in range(N_max):

z = z∗∗2 + c

A point (x, y) belongs to the Mandelbrot set if |z| &lt; threshold computed from the above iteration starting

with c = x + yi. Do this computation as follows:

1. constructann×ngrid(2Darray)ofpoints(x,y)inrange[−2,1]×[−1.5,1.5](e.g.,usingnumpy.meshgrid)

and corresponding complex values c = x + yi (note that the imaginary unit in Python is 1j); 1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<ol start="2">
<li>perform the iteration as outlined above to compute z for each complex value in the grid;</li>
<li>form a 2-D boolean array mask indicating which points are in the set (i.e., |z| &lt; threshoold);</li>
<li>save the result to an image using the commands:
import matplotlib . pyplot as plt

plt .imshow(mask.T, extent=[−2, 1, −1.5, 1.5]) plt . gray ()

p l t . s a v e f i g ( ’ mandelbrot . png ’ )
</li>
<li>organize the statements into a function that takes n, N_max, and threshold as input, add docstring and comments to the function, and experiment the function with different n so that you get an image resembling the one above.</li>
</ol>
1.2 Task 2: Markov Chain

The following diagram depicts a set of states and the transition between each pair of states, where pi denotes the probability within the ith state and Pij is the probability for state i to transition into state j.

Mathematically, we can represent the diagram with a vector p and a matrix P. The vector p of size n would describe the probability distribution on n states, with

0 ≤ p[i] ≤ 1 and 􏰀 p[i] = 1. i

Matrix P is a Markov chain transition matrix of size n × n, where 0 ≤ P[i,j] ≤ 1,

with the sum of each row equal to 1 (i.e., 􏰄j P[i,j] = 1 for all i). Given an old state pold, the new state is then given by PTpold.

In this task, you need to write a Python script named markov_chain.py to perform the following:

<ol>
<li>Construct a random n-vector with non-negative entries and scale its entries so that the sum is 1. This
computation gives us a probability distribution p.
</li>
<li>Construct a random n × n (say n = 5) matrix with non-negative entries, and scale the entries so that
the sum for each row is 1. This computation gives us a transition matrix P .
</li>
<li>Starting from p as the initial state, compute the transition for N (say N = 50) steps (i.e., compute
p←PTpforN times).
</li>
<li>Use the function np.linalg.eig to compute the eigenvector of P.T corresponding to the largest eigenvalue. Rescale the entries of the eigenvector so that its sum is equal to 1. Let the resulting vector be pstationary (or p_stationary).</li>
<li>Change the loop in step 3 to compute the norm of p − pstationary and plot the norms against i. Check whether the difference diminishes as the number of iterations increases.</li>
<li>Organize your code into a function so that it would take n and N as input and call the function by passing in n = 5 and N = 50. Document the function and test it with some other values of n and N.</li>
</ol>
You might find the following functions useful: np.random.rand, np.dot, np.sum, np.linalg.eig, np.argmax, etc.

</div>
</div>
</div>
