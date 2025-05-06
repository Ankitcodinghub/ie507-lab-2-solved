# ie507-lab-2-solved
**TO GET THIS SOLUTION VISIT:** [IE507 Lab 2 Solved](https://www.ankitcodinghub.com/product/ie507-lab-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97660&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;IE507 Lab 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Instructions:

In this session, we will continue to use Pyomo modeling language and software. We will see more useful constructs which will help in modelling problems which have many variables and constraints. Please follow the instructions given below:

<ul>
<li>Please use different notebooks for solving different problems.</li>
<li>The name of your notebook for Exercise 1 should be YOURROLLNUMBER IE507 Lab2 Ex1.ipynb. Similarly, The name of your notebook for Exercise 2 should be YOURROLLNUMBER IE507 Lab2 Ex2.ipynb, etc.</li>
<li>Please post your doubts in MS Teams or Moodle so that TAs can clarify.
For more details on pyomo, please consult https://pyomo.readthedocs.io/en/stable/index. html.

For details on numpy python package, please consult https://numpy.org/doc/stable/numpy-ref. pdf. This file has been uploaded in moodle as well.

There are only 3 exercises. Try to solve all problems on your own. If you have difficulties, ask the Instructors or TAs.

Only the questions marked [R] need to be answered in the notebook. You can either print the answers using print command in your code or you can write the text in a separate text tab. To add text in your notebook, click +Text.

After completing this lab’s exercises, click File → Download .ipynb and save your files to your local laptop/desktop. Create a folder with name YOURROLLNUMBER IE507 Lab2 and copy your .ipynb files to the folder. Then zip the folder to create YOURROLLNUMBER IE507 Lab2.zip. Then upload only the .zip file to Moodle. These instructions are also provided in the video.

The deadline for today’s lab submission is tomorrow, 11.59 PM IST.
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
IE507, Modeling and Computation Lab

Lab 02 26-August-2020

Exercise 1: [6 Marks]

In the practice problem, we saw that python numpy arrays can be used to store the coefficients of the objective function and constraints. In this exercise, we will consider a slight variation and consider the problem given below.

</div>
</div>
<div class="layoutArea">
<div class="column">
min c1x1 +c2x2 +…+cNxN, x1+x2+…+xN ≤b1, w1x1+…+wNxN =b2, xi ≤ ui,

xi ≥ li,

</div>
<div class="column">
i = 1,…,N, i = 1,…,N.

</div>
</div>
<div class="layoutArea">
<div class="column">
1. Now suppose we want to solve the problem with 10 variables. Modify the code in practice problem so that you can solve the problem given above with 10 variables. You may assume that

b1 = 151.2,

b2 = 44.6,

c = [−10.1, 20.15, 60.5, 80.05, 0.15, 40.5, −0.05, −30.02, 40.65, 0.125]; w = [0, 1.6, −2.02, 0, 1.01, −2.005, 0, 1.39, 1, −1.214];

l = [−∞,1,0,0,7,0,−∞,−∞,1,1],

u = [4,3,+∞,2,10,+∞,13,20,+∞,21]

2. [R] Solve the new problem and report the optimal solution and the value of the objective function (or cost).

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
IE507, Modeling and Computation Lab

Lab 02 26-August-2020

Exercise 2: [8 Marks] We will now consider another general formulation of the form given below:

min c⊤x,

s.t Ax≤b

l ≤ x ≤ u.

wherec,x,landuareN×1vectorsandc⊤x=􏰁Ni=1cixi. AisaM×N matrixandbisM×1 vector. Ax ≤ b results in M constraints and note that i-th row of Ax ≤ b can be written as a constraint of the form:

ai1x1 +ai2x2 +…+aiNxN ≤bi. We will solve the general form using concrete values given below:

c = [8.6, −20.35, 61.5, 39.05, −0.15, 40.5, −0.05, −30.02, 40.65, 5.125];

0 1−20 1−2011−1 A=−1 1 −3 2.5 0 1.4 0 −2 1 −1.5 −0.45 4.78 −2 −3.22 −1.3 1 −1 0 0 0.25 

1100110110 b = [55.4, 67.9, 21.43, 12.7]

l = [−∞,−∞,0,0,−57,0,−∞,−3,4,1], u = [4,∞,+∞,2,10,45,13,20,+∞,+∞]

We will now see some instructions to prepare your code to solve this general formulation.

Preparing the code for solving the general formulation:

<ul>
<li>Recall that we created a variable N to denote the number of variables. Similarly create a variable M to denote the number of constraints. Use appropriate value for M based on the concrete problem given above.</li>
<li>Recall that we used two arrays named constr1 coef p and constr2 coef q for storing the coefficients of the two constraints. Now, instead we will create a single two-dimensional numpy array with name constr coef A to store the coefficients of all constraints. Check the numpy documentation and see how to create a two-dimensional numpy array. Create the array with the values given in the matrix A given above.</li>
<li>Similarly we used two variables constr1 rhs b1 and constr1 rhs b2 for storing the values used in RHS of first and second constraints respectively. Now, instead we will create a single numpy array constr rhs b and store the values in b array given above.</li>
<li>Also recall that we used a ConstraintList() for adding the constraints. We added each constraint separately. Instead of adding each constraint separately, we will try to add the constraints in a loop. For this purpose, let us create a list using the following command
row_indices = np.arange(M)

Check the contents of this list using a print statement. Now create a for loop to load the

constraint to the list ConstraintList(). Your code should be of the form as given below:

<pre>      for &lt;fill in appropriate syntax&gt;:
          model.constraints.add(&lt;fill in appropriate syntax&gt;)
</pre>
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
IE507, Modeling and Computation Lab

Lab 02 26-August-2020

<ul>
<li>Modify the upper bound and lower bound arrays in your code appropriately with the values given above in l and u arrays.</li>
<li>Print the model to check if the constraints have been added properly.</li>
<li>You are now ready to answer the questions. Question:</li>
</ul>
<ul>
<li>[R] Solve the problem and report the optimal solution and the value of the objective function (or cost).</li>
<li>[R] Which constraints are active and which constraints are inactive? Explain with proper reasons.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
IE507, Modeling and Computation Lab

Lab 02 26-August-2020

Exercise 3: Alloy Mix Problem. [15 Marks]

Kekra Metal Co. produces 250 tons of metallic alloy product of composition: 45% Chromium, 35% Zinc, and 20% Silver. In order to produce this alloy, it can mix 10 available alloys: A-1, A-2, . . . , A-10. The alloys have the following composition and costs.

</div>
</div>
<div class="layoutArea">
<div class="column">
% of Chromium

% of Zinc

% of Silver

in-house stock (Tons) in-house cost (per Ton) purchase cost (per Ton)

</div>
<div class="column">
A-8 A-9 A-10 30 30 30 55 40 15 0 9 35 40 60 84

</div>
</div>
<div class="layoutArea">
<div class="column">
A-1 80 15 5 10 35 72

</div>
<div class="column">
A-2 A-3 75 75 15 10 10 15

7 8 50 58 95 110

</div>
<div class="column">
A-4 A-5 A-6 A-7

60 55 55 40 35 20 25 10 50 15 20 20 35 10 50 15 8 15 12 10 60 44 39 45 55

</div>
</div>
<div class="layoutArea">
<div class="column">
125 88 74 95 115

</div>
</div>
<div class="layoutArea">
<div class="column">
The company can either use the

them from market. The stocks available in the company are limited while the quantity available in market is unlimited. You are given the task of finding how much of each raw-material should be put in the final mix to obtain 250 Tons of the product.

<ol>
<li>[R] Formulate an LP model that can be solved to find the optimal mix of raw-material alloys.</li>
<li>Modify the code used in Exercise 2 with appropriate number of variables, number of con- straints, coefficient arrays, lower bound and upper bound arrays to construct a model for this problem.</li>
<li>[R] Solve the model and report the optimal value and the optimal solution.</li>
<li>[R] Among the alloys that need to be bought from the market, which three alloys are ranked
high in terms of the quantities to be bought and which three alloys are ranked low?
</li>
<li>[R] Is there any alloy whose stock is completely utilized? Why?</li>
<li>[R] Is there any alloy which need not be acquired from market? Why?</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
stocks of raw material alloys available in the company or purchase

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
