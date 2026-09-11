## Variable Selection Strategy

The first analysis will focus on baseline demographic, blood, and cerebrospinal fluid variables that could support early differentiation between bacterial and viral meningitis.

The raw dataset contains additional variables whose meanings are unclear, as well as treatment-related, follow-up, second lumbar puncture, and diagnostic confirmation variables. These variables will not be used in the first baseline analysis.

Diagnostic confirmation variables such as culture, antigen testing, and blood culture results are excluded from the first predictive analysis because they may directly contribute to the final classification of bacterial versus viral meningitis. Including them could introduce outcome leakage.

Gram stain will be handled separately. Since Gram stain may be available earlier than culture, it may be evaluated in a secondary model, while the primary model will focus on baseline blood and CSF cell count/chemistry variables.