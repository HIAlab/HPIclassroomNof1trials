# HPIclassroomNof1trials
Repository containing study information and protocol, data, and scripts of analysis of the N-of-1 trial seminar in summer semester 2023 at Hasso Plattner Institute in Potsdam, Germany.

The folder /study_protocol contains the study protocol and consent forms that were prepared in class by all participating students.

The folder /data_Nof1trials contains the de-identified data of the N-of-1 trials which were done using the StudyU platform. The data was downloaded from the StudyU website (https://designer.studyu.health) formatted and then uploaded here.

The folder /data_feasibility contains the de-identified data collected through anonymized online questionnaires on the feasibility of using StudyU to perform the trials mentioned above.

The folder /analysis contains the code used to produce the results in the paper.

## N-of-1 Trials Analysis
The code to produce the results in the paper was written in Python in a Jupyter Notebook format. The code was run on the data files (.csv) in the /data_Nof1trials folder.

For the individual analysis code, all 10 trials of participants, investigating 6 different interventions, were analyzed following pre-processing and descriptive statistics. A linear regression model with autocorrelated errors was used to estimate the treatment effect of each intervention per participant.

For the aggregated analysis code, the herbal and tea trials were combined as an overall tea trial dataset which was analyzed following pre-processing and descriptive statistics. A normal linear regression model, a mixed model with AR1 correlation and a linear regression model with autocorrelated errors were used to estimate the treatment effect.
