# Comorbidome_plot

## Introduction
This work is part of the results published in [our article](https://link.springer.com/article/10.1007/s13555-023-00986-0)

<i>Buja A, Miatton A, Cozzolino C, Brazzale AR, Lo Bue R, Mercuri SR, Proft FN, Kridin K, Cohen AD, Damiani G. The Prevalent Comorbidome at the Onset of Psoriasis Diagnosis. Dermatol Ther (Heidelb). 2023 Sep;13(9):2093-2105. doi: 10.1007/s13555-023-00986-0. Epub 2023 Aug 5.</i>

If you enjoy this project, you are welcome to cite our article and sustain my GitHub profile leaving a ⭐!


## Aim

The aim of this code is to obtain a graphical representation of commonly used clinical statistics such as prevalences and odd rations (ORs) is the form of a <i> comorbidome plot</i>.

The comorbidome plot graphically represents all comorbidities (or generally factors) as bubbles in the Cartesian plane where the origin represents a certain health condition or outcome (in our study, psoriasis). The size of each bubble is proportional to the prevalence of the comorbidity, while proximity to the center expresses the strength of the association between the comorbidity and the health outcome (this is numerically obtained inverting the odd ratio or hazard ratio). All circles relating to a comorbidity with an increased odd or risk fall inside the dashed orbit ($1/OR < 1$), otherwise they are outside ($1/OR > 1$).


## Data
The code presented below does not include the calculation of prevalence and odd ratios.
The datasheet to obtain the comorbidome plot from this script has one row for each comorbidity and the following mandatory variables:
- ```comorbidity_html_name```: the clean name of each comorbidity eventually formatted with HTML tags style
- ```perc```: prevalence percentage ($\in [0, 1]$) of each comorbidity in the case group (here psoriatic subjects)
- ```OR_ref_control```: logistic regression OR of association with condition or health outcome defining a case (here psoriasis) for each comorbidity. 
- ```signif```: boolen variable defining whether the OR p-value is below the level of significance (here ```True``` if $p<0.001$).

Additionally, a grouping variable ```group``` could be defined to personalize color scheme according to a certain criterion (here disease macro-classification).



## Plot
Finally plot all the elements as Plotly Graphical Objects:

- central diamond representing the condition or health outcome under study (here psoriasis)
- orbit of radius $1$
- comorbidity bubbles.

## 

Thank you ❤️,

<br>

<i>Claudia Cozzolino </i>

For any enquiry contact claudia.cozzolino@studenti.unipd.it or on [LinkedIn](https://www.linkedin.com/in/claudia-cozzolino-7b11661b8/)



![comorbidity_before_interactive_plot1%20-%20Copia.png](attachment:comorbidity_before_interactive_plot1%20-%20Copia.png)
