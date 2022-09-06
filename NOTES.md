# Self Studying 

Now that I am finished with school, 
and do not have any immediate plans to return, 
I would still like a way for me to track any new things that I learn. 
This could relate to topics that I have either seen before and I want to review, 
or are completely new to me. 
These will mainly be focused on subjects that are very mathematical/computational in general, 
(roughly) broken up into the following categories: 

- Applied mathematics (general) 
- Theoretical mathematics (general) 
- Computer science 
- Probability and statistics 
- Quantitative finance 

Notes for the specific areas will encompass **all** aspects, 
from theoretical to computational. 
There clearly will be a lot of overlap in these subjects, 
so as all good programmers do, I will try to make relevant notes 
"higher up" in sections where that material could be used/referenced to later on. 
Some potential examples: 

- Learning about multivariate regression for the first time requires the understanding of 
  linear algebra (matrix-vector products, vector norms) and multivariate calculus. 
  So if I were to make a section about linear regression, it would be worthwhile to first 
  make notes about the pre-requisite material in the Applied Math section, 
  and then in the linear regression notes reference that material. 
  And if linear regression comes up again anywhere else in any notes (e.g. Financial Engineering), 
  then we could reference back to the linear regression notes (perhaps using different notation). 

A list of subjects I want to hit is as follows: 

1. Applied Mathematics (general) 
	- Linear algebra 
		[] Basics 
		[] Matrix and Vector Norms 
		[] Matrix decompositions 
	- Optimization 
		[] Multivariate optimization
		[] Convex optimization 
	- Differential Equations 
2. Theoretical Mathematics (general) 
	- Measure theory 
		[] Sigma algebra 
		[] Borel sets 
		[] Lebesgue integration 
3. Computer Science (focus on using Python and C++) 
	- Data structures 
		[] Basic stuff that everyone should know (arrays, lists, stacks, queues, hash maps, graphs, etc) and implementation of each 
		[] Exploration of Python and C++ specific data structures 
	- Algorithms 
		[] Run-time analysis 
		[] Specific, well-known algorithms 
		[] Exploration of Python and C++ specific algorithms 
	- NOTE: here there will be a lot of overlap, but I feel there is less overlap as you get to more advanced topics 
	- Python/C++ specific notes? 
4. Probability and statistics 
	- Probability 
		[] Theoretical overview 
		[] Examples of distributions 
	- Stochastic processes 
	- Statistics 
		[] CLT and asymptotical statistics 
		[] Confidence intervals and hypothesis tests 
5. Machine Learning 
	- Linear regression 
		[] Basic 
		[] Regularization 
		[] Basis expansion 
	- Neural networks 
		[] Lots of topics here 
	- Gradient boosting 
6. Quantitative Finance 
	- Basics 
	  [] Definitions 
	  [] Overview of all asset classes 
	  [] Things that people even look to do in quant finance 
	- Derivatives pricing 
	- Algorithmic trading 
	- Cryptocurrencies 

For each of the notes sections, 
it will be good to also compile a list of free resources 
(e.g. online course notes, free textbook pdfs, papers available online) 
that other people can use outside of these. 

Have consistent style and notation across entirely different fields is cool and unique. 
Making these notes will also be a good way to "unify" these different topics 
under a single "style"; 
things like notation, presentation, will all be under one theme that is recognizable and clear. 
This brings up the question: how should these notes be made? 
This repo will make use of the following styles: 

1. Making documents in LaTeX: 
these will be more long-form style documents that can go into a lot of detail on the subject. 

2. Making slides in LaTeX: 
these will be more concise and high-level documents that are rigorous yet easy to digest. 

3. Making text files: 
these will be for initial notes, ideas, or thoughts that I have. Kind of like a rough draft. 

4. Code: 
either Jupyter Notebooks, Python scripts, or C++ scripts. 
Whenever anything needs to be implemented (and this will happen a lot, especially in the computer science section), 
I would like to be able to actually implement it as a program. 

Within this, the style type needs to be figured out, 
but it should: 
- Be consistent across all documents 
- Have the ability to update all styles should I need to do so 
