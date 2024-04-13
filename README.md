# Comorbidome_plot

## Introduction
This work is part of the results published in [our article](https://link.springer.com/article/10.1007/s13555-023-00986-0)

<i>Buja A, Miatton A, Cozzolino C, Brazzale AR, Lo Bue R, Mercuri SR, Proft FN, Kridin K, Cohen AD, Damiani G. The Prevalent Comorbidome at the Onset of Psoriasis Diagnosis. Dermatol Ther (Heidelb). 2023 Sep;13(9):2093-2105. doi: 10.1007/s13555-023-00986-0. Epub 2023 Aug 5.</i>

If you enjoy this project, you are welcome to cite our article and sustain my GitHub profile leaving a ⭐!

Thank you ❤️,

<br>

<i>Claudia Cozzolino </i>

For any enquiry contact claudia.cozzolino@studenti.unipd.it or on [LinkedIn](https://www.linkedin.com/in/claudia-cozzolino-7b11661b8/)


## Aim

The aim of this code is to obtain a graphical representation of commonly used clinical statistics such as prevalences and odd rations (ORs) is the form of a <i> comorbidome plot</i>.

In our article, the prevalence rates for each pre-existing morbidity were calculated as percentages. Univariate logistic regression was insted performed to assess the odds ratio (OR) for each comorbidity in psoriatic subjects compared with non-psoriatic subjects. Results were considered statistically significant at $0.001$, which takes into account the multiple tests performed.

The comorbidome plot graphically represents all comorbidities that had a statistically significant association with psoriasis onset ($p < 0.001$). The size of each bubble is proportional to the prevalence of the disease in the psoriatic cohort, while proximity to the center (psoriasis) expresses the strength of the association between the comorbidity and psoriasis diagnosis (this was numerically obtained as the inverse of the OR, $1/OR$). All circles relating to a disease with an increased occurrence in the psoriatic group fall inside the dashed orbit ($1/OR < 1$), while morbidities with a decreased prevalence are outside ($1/OR > 1$).


![comorbidity_before_interactive_plot1%20-%20Copia.png](attachment:comorbidity_before_interactive_plot1%20-%20Copia.png)
