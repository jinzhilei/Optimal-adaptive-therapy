# Optimal-adaptive-therapy

This project include the Matlab codes for the manuscript:

Dujuan Wang, Jinzhi Lei, Optimal adaptive therapeutic schedule for metastatic castrate-resistant prostate cancer based on bilevel optimization problem.

Abstract

Abiraterone acetate has established itself as an effective treatment for metastatic castrate-resistant prostate cancer (mCRPC). However, disease progression remains inevitable with conventional long-term maximum tolerated dose (MTD) therapy due to the development of drug resistance. Adaptive therapy (AT), rooted in Darwinian evolutionary dynamics, offers a novel approach to combat drug resistance. By dynamically adjusting drug doses, AT aims to enhance treatment outcomes. Despite successful clinical trials and extensive theoretical studies on AT, significant challenges persist in determining optimal adaptive therapeutic schedules tailored to individual patients. This study presents a biochemically motivated mathematical model incorporating competition between drug-sensitive and drug-resistant cancer cells, incorporating mutated migration factors identified through prostate-specific antigen (PSA) data. Theoretical analyses, including the stability of equilibrium states and the existence of periodic solutions, validate the model’s interpretability and support the feasibility of adapted periodic therapy. We propose an optimal adaptive periodic therapy framework, formulating a bilevel dynamic optimization problem with constraints to establish personalized adaptive therapeutic schedules for prostate cancer. Optimal solutions identify therapeutic switches and doses under adaptive therapy. We compare our proposed framework with other adaptive strategies regarding overall survival and total drug doses through numerical simulations and quantitative analysis, demonstrating superior performance. Our model presents a promising tool for integration into clinical research trials, offering individualized adaptive therapeutic schedules to enhance precision management of mCRPC.

The codes files include:
1. Model_fitting.zip: The code to fit model parameters for individual patients based on clinical data.
2. Para_Search.zip: The code to search the parameters from the given parameter space
3. PSO_SA.zip: The code to solve the optimization problem with the method of particle swarm optimzation algorithms with siulated annealing (PSO-SA)
4. Sensitivity_analysis.zip: The code to perform sensitivity analysis with respect to key parameters.
5. Suvival_curves_and_campare.zip: The code to calculate the survival curve and compare the results with clinical data.
