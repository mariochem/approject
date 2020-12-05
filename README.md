# Approjecth

Design Recipes for Applications

In this page, we are shown an approach to program design based on recipes. Each design recipe is applicable to certain problems, and systematizes the process of designing solutions to those problems.

There are four core recipes that handle most of the design work, additional recipes handle variations of the core recipes for particular kinds of problems. A list of the recipes presented in this course is shown below; clicking on the links provides a detailed description of the recipe.

Core Recipes	Data Driven Variants	Control Driven Variants	Abstraction
How to Design Functions (HtDF) 
Design any function.	Functions on 2 One-of Data 
Functions where 2 arguments have a one-of in their type comments.	Function Composition	From Examples 
Produce an abstract function given two similar functions.
How to Design Data (HtDD) 
Produce data definitions based on structure of the information to be represented.		Backtracking Search	From Type Comments 
Produce a fold function given type comments.
Data Driven Templates 
Produce template for a data definition based on the form of the type comment.	Generative Recursion	
How to Design Worlds (HtDW) 
Produce interactive programs that use big-bang.	Accumulators: 
 - recover information lost in recursion
 - tail recursion
 - maintain a work list
Using Abstract Functions
for-each Loops	
Template Blending
