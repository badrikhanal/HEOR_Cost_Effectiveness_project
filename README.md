# HEOR_Cost_Effectiveness_project
I used MEPS real-world data to construct a cohort of diabetic patients, applied propensity score matching to address confounding, estimated treatment effects on cost and hospitalization using regression and survival models, and conducted a cost-effectiveness analysis using ICER.

Preliminary Findings

Using data from the Medical Expenditure Panel Survey (MEPS), a real-world cohort of 2,508 U.S. adults with diabetes was constructed by linking diagnosis, demographic, healthcare utilization, expenditure, and prescription medication data.

Patients were classified into:

Diabetes medication treatment group: 1,842 patients
Comparison group: 666 patients

Initial Descriptive Findings

Preliminary comparisons show differences in healthcare utilization and expenditures between the two groups:

Measure	|Treated	|Comparison
-------------------------------
Mean annual healthcare expenditure |	$15,598 |	$23,288
Median annual healthcare expenditure|$7,875 |	$11,292
Hospitalization rate|	18.35% |	23.72%
Mean age |	62.34 years |	59.03 years
--------------------------------------

The treated group had lower average and median annual healthcare expenditures and a lower hospitalization rate than the comparison group, despite being older on average. These findings are descriptive and do not yet establish a causal treatment effect, as differences in patient characteristics and disease severity may influence both treatment assignment and outcomes.

Further analysis will adjust for relevant patient characteristics and evaluate the effectiveness and cost-effectiveness of diabetes medication treatment using regression and economic evaluation methods.
