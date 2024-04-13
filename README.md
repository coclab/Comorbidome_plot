# Comorbidome_plot

## Introduction
This work is part of the results published in [our article](https://link.springer.com/article/10.1007/s13555-023-00986-0)

<i>Buja A, Miatton A, Cozzolino C, Brazzale AR, Lo Bue R, Mercuri SR, Proft FN, Kridin K, Cohen AD, Damiani G. The Prevalent Comorbidome at the Onset of Psoriasis Diagnosis. Dermatol Ther (Heidelb). 2023 Sep;13(9):2093-2105. doi: 10.1007/s13555-023-00986-0. Epub 2023 Aug 5.</i>

If you enjoy this project, you are welcome to cite our article and sustain my GitHub profile leaving a ⭐!


## Aim

The aim of this code is to obtain a graphical representation of commonly used clinical statistics such as prevalences and odd ratios (ORs) is the form of a <i> comorbidome plot</i>.
![](https://github.com/coclab/Comorbidome_plot/blob/main/comorbidome_plot.png)
The comorbidome plot graphically represents all comorbidities (or generally factors) as bubbles in the Cartesian plane where the origin represents a certain health condition or outcome (in our study, psoriasis). The size of each bubble is proportional to the prevalence of the comorbidity, while proximity to the center expresses the strength of the association between the comorbidity and the health outcome (this is numerically obtained inverting the odd or hazard ratios). All circles relating to a comorbidity with an increased odd or risk fall inside the dashed orbit or radius 1 (if 1/OR < 1), outside otherwise (1/OR > 1).

## Data and code
The notebook ```Comorbidome_plot.ipynb``` contains all the steps to process the statistics and plot all the graphical objects. A complete working example is presented using the data ```example_data_pso.xlsx``` resulting from our study.

## Contacts
For any comment or enquiry fell free to contact me at claudia.cozzolino@studenti.unipd.it or on [LinkedIn](https://www.linkedin.com/in/claudia-cozzolino-7b11661b8/)
I will be happy to receive your suggestions. Do you think it might be useful to develop a python library with the whole pipeline for this purpose?

Thank you ❤️

<br>

<i>Claudia Cozzolino </i>

