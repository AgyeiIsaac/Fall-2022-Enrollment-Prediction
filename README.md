# Fall-2022-Enrollment-Prediction
The goal of this project is to forecast the number of students who will enroll in math classes at Ohio University. A five-year enrollment record was employed as the data source.
The first goal was to use the Python pandas module to clean up the data set. Following that, various models for predicting course enrollment were used. The initial prediction model was a null prediction, which predicted the exact same enrollment number as the enrollment number immediately before it. The average of the enrollment number for the previous two years and the average for all five available years were also utilized as prediction models in the second prediction model, which was a linear prediction. The final prediction model was developed using the confirmation ratio for incoming students over the previous two years. The findings reached using these prediction models were to determine the percentage of math course enrollment to overall university enrollment and freshman math course enrollment to total freshman enrollment. In addition, a graph depicting the pattern of prior enrollment figures as well as the anticipated enrolment number for the coming year was shown.
However, as of April 2020, confirmation for Fall 2020 was 2725 which was less than the actual enrollment for that particular year, 3126.  Also, confirmation as of May 2020 was greater than the actual enrollment for Fall 2020. This analysis holds for Fall 2021. Based on this analysis, we could predict that enrollment for Fall 2022 should fall within confirmation for April 2022(3579) and May 2022(4662).
Looking at our aforementioned prediction model, you can see that our confirmation model gives us a predicted value of 4554 which falls within confirmation as of April (3579) and May(4662).
Based on this model, we are able to predict the enrollment for each  Math course in 2022:
MATH1060 - 193;
MATH1101 - 150;
MATH1200 - 913;
MATH1300 - 551;
MATH1350 - 465;
MATH1500 - 71;
MATH2301 - 367;
MATH2500 - 83;
MATHD00 - 179;
