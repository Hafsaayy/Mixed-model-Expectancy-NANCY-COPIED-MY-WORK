# Mixed-model-Expectancy-Nancy-copy-paste


Task:
I want 4 line-charts in APA7 format. Right now these line-charts are in the form of jamovi outputs from my analysis (indicated as Figure 1- 4 below) that I want to reproduce in APA7 format. I have attached instructions under each figure as well as their simple effects & EMMS tables to reproduce these charts.
For Figures 1-4: Produce all figures in the same style, format, same axis ie for the X-axis use the same time point of 0,4,8,12 months














Figure 1
Effect of Outcome Expectancy on BAI Scores at Post-Treatment and Follow-Up
 
Instructions for APA7 formatting 
Format Figure 1 & 2 to be the same as the following reference plot (from the parent study)









Figure 1 
1.	Use Figure title as provided 
2.	EMMS data provided in file “Mixed Model BAI Expectancy”
3.	Use SE bars (please make them look small and not clutter the plot)
4.	Prefer to have horizontal gridlines (as per reference plot) but not essential
5.	Insert a vertical dotted gridline at 4-month (as per reference plot to signify post-treatment)
6.	Change the legend to:
	Outcome expectancy levels
Low 
Average 
High 
7.	Have the 3 levels of Expectancy in different colours or patterns
8.	Change Y-axis to same as the reference plot (do not use T0 to T3):
Time (months)
0
4
8
12
9.	Change X-axis to same as the reference plot:
Estimated BAI (95% CI)












Figure 2
Effect of Treatment Credibility on BAI Scores at Post-Treatment and Follow-Up
 
Instructions for APA7 formatting 













Figure 2
1.	Use Figure title as provided 
2.	EMMS data provided in file “Mixed Model BAI Credibility”
3.	Use SE bars (please make them look small and not clutter the plot)
4.	Prefer to have horizontal gridlines (as per reference plot) but not essential
5.	Insert a vertical dotted gridline at 4-month (as per reference plot to signify post-treatment)
6.	Change the legend to:
	Treatment credibility levels
Low 
Average 
High 
7.	Have the 3 levels of Credibility in different colours or patterns
8.	Change Y-axis to same as the reference plot (do not use T0 to T3):
Time (months)
0
4
8
12
9.	Change X-axis to same as the reference plot:
Estimated BAI (95% CI)








Figure 3
Effect of Outcome Expectancy on CSR Scores at Post-Treatment and Follow-Up 
Instructions for APA7 formatting 









Figure 3
1.	Use Figure title as provided 
2.	EMMS data provided in file “Mixed Model CSR Expectancy”
3.	Use SE bars (please make them look small and not clutter the plot)
4.	Prefer to have horizontal gridlines (as per reference plot) but not essential
5.	Insert a vertical dotted gridline at 4-month (as per reference plot to signify post-treatment)
6.	Change the legend to:
Outcome expectancy levels
Low 
Average 
High 
7.	Have the 3 levels of Expectancy in different colours or patterns
8.	Change Y-axis to same as the reference plot (do not use T0 to T3). Please note that CSR didn’t collect any data for 8 months follow-up so visually show as per the reference plot (with no mark & SE bars at 8-months)
Time (months)
0
4
8	(Note there is no mark or SE bar at this timepoint)
12
9.	Change X-axis: Estimated CSR (95% CI)








Figure 4
Effect of Treatment Credibility on CSR Scores at Post-Treatment and Follow-Up 

Instructions for APA7 formatting 















Figure 4
1.	Use Figure title as provided 
2.	EMMS data provided in file “Mixed Model CSR Credibility”
3.	Use SE bars (please make them look small and not clutter the plot)
4.	Prefer to have horizontal gridlines (as per reference plot) but not essential
5.	Insert a vertical dotted gridline at 4-month (as per reference plot to signify post-treatment)
6.	Change the legend to:
Treatment credibility levels
Low 
Average 
High 
7.	Have the 3 levels of Credibility in different colours or patterns
8.	Change Y-axis to same as the reference plot (do not use T0 to T3). Please note that CSR didn’t collect any data for 8 months follow-up so visually show as per the reference plot (with no mark & SE bars at 8-months)
Time (months)
0
4
8	(Note there is no mark or SE bar at this timepoint)
12
9.	Change X-axis: Estimated CSR (95% CI)


Mixed Model
Model Info
Info	 	 
Model Type	Mixed Model	Linear Mixed model for continuous y
Model	lme	BAI ~ 1 + Time_C + Credibility + Time_C:Credibility + ( 1 | Participant )
Distribution	Gaussian	Normal distribution of residuals
Direction	y	Dependend variable scores
Residuals	Autoregressive 1	within cluster Participant
Sample size	284	 
Converged	yes	 
Y transform	none	 
C.I. method	Bootstrap percent	10000 bootstrap samples

 
Model Results
Model Fit
Type	R²	df	LRT X²	p
Conditional	0.57	9	167.16	<.001
Marginal	0.31	7	141.00	<.001

 
Additional Indices
Info	Model Value	Comment
LogLikelihood	-1000.68	 
AIC	2023.36	Less is better
BIC	2063.18	Less is better

 
Fixed Effects Omnibus Tests
 	F	df	df (res)	p
Time_C	51.52	3	178.00	<.001
Credibility	5.72	1	178.00	0.018
Time_C ✻ Credibility	2.29	3	178.00	0.080

 
Parameter Estimates (Fixed coefficients)
	95% Confidence Intervals	
Names	Effect	Estimate	SE	Lower	Upper	df	t	p
(Intercept)	(Intercept)	15.42	0.79	14.51	16.48	178.00	19.57	<.001
Time_C1	T1 - T0	-11.19	1.16	-13.68	-8.28	178.00	-9.68	<.001
Time_C2	T2 - T0	-13.02	1.27	-15.23	-10.13	178.00	-10.27	<.001
Time_C3	T3 - T0	-13.10	1.30	-15.49	-10.26	178.00	-10.10	<.001
Credibility	Credibility	-1.50	0.63	-2.79	-0.21	178.00	-2.39	0.018
Time_C1 ✻ Credibility	(T1 - T0) ✻ Credibility	-3.35	1.30	-6.08	-0.64	178.00	-2.57	0.011
Time_C2 ✻ Credibility	(T2 - T0) ✻ Credibility	-1.59	1.35	-4.20	1.22	178.00	-1.18	0.241
Time_C3 ✻ Credibility	(T3 - T0) ✻ Credibility	-1.77	1.39	-4.50	1.04	178.00	-1.27	0.206

 
Random Components
Groups	Name	Variance	SD	ICC	Phi
Participant	(Intercept)	32.55	5.71	0.37	0.13
Residual	 	54.55	7.39	 	 
Note. Number of Obs: 284 , Number of groups: Participant 99

 
Post Hoc Tests
Post Hoc comparison: Time_C
Comparison		95% Confidence Intervals	
Time_C	vs	Time_C	Difference	SE	Lower	Upper	t	df	p
T0	-	T1	11.11	1.15	.	.	9.62	178.00	<.001
T0	-	T2	12.98	1.27	.	.	10.25	178.00	<.001
T0	-	T3	13.06	1.30	.	.	10.08	178.00	<.001
T1	-	T2	1.88	1.23	.	.	1.53	178.00	0.128
T1	-	T3	1.95	1.31	.	.	1.49	178.00	0.139
T2	-	T3	0.08	1.29	.	.	0.06	178.00	0.952

 
Simple Effects
ANOVA for Simple Effects of Time_C
Moderator	
Credibility	F	Num df	Den df	p
Mean-1·SD	17.29	3.00	178.00	<.001
Mean	51.52	3.00	178.00	<.001
Mean+1·SD	27.52	3.00	178.00	<.001

 
Parameter Estimates for simple effects of Time_C
Moderator		95% Confidence Intervals	
Credibility	Effect	Estimate	SE	Lower	Upper	df	t	p
Mean-1·SD	T1 - T0	-7.79	1.71	-11.15	-4.42	178.00	-4.57	<.001
 	T2 - T0	-11.41	1.81	-14.98	-7.83	178.00	-6.29	<.001
 	T3 - T0	-11.30	1.86	-14.98	-7.63	178.00	-6.08	<.001
Mean	T1 - T0	-11.19	1.16	-13.47	-8.91	178.00	-9.68	<.001
 	T2 - T0	-13.02	1.27	-15.52	-10.52	178.00	-10.27	<.001
 	T3 - T0	-13.10	1.30	-15.66	-10.54	178.00	-10.10	<.001
Mean+1·SD	T1 - T0	-14.59	1.81	-18.16	-11.02	178.00	-8.07	<.001
 	T2 - T0	-14.64	1.92	-18.43	-10.84	178.00	-7.61	<.001
 	T3 - T0	-14.90	1.98	-18.81	-11.00	178.00	-7.53	<.001

 
Estimated Marginal Means
Estimate Marginal Means - Time_C
	95% Confidence Intervals
Time_C	Mean	SE	df	Lower	Upper
T0	24.74	0.97	98.00	22.59	26.47
T1	13.63	1.09	98.00	11.85	15.48
T2	11.76	1.16	98.00	10.22	13.70
T3	11.68	1.18	98.00	10.06	13.70

 
Estimate Marginal Means - Credibility
	95% Confidence Intervals
Credibility	Mean	SE	df	Lower	Upper
Mean-1·SD	16.94	1.03	98.00	15.42	18.57
Mean	15.42	0.79	98.00	14.44	16.43
Mean+1·SD	13.89	1.00	98.00	12.38	15.56

 
Estimate Marginal Means - Time_C ✻ Credibility
	95% Confidence Intervals
Time_C	Credibility	Mean	SE	df	Lower	Upper
T0	Mean-1·SD	24.57	1.19	98.00	21.57	27.05
T0	Mean	24.74	0.97	98.00	22.59	26.49
T0	Mean+1·SD	24.92	1.47	98.00	21.29	27.86
T1	Mean-1·SD	16.78	1.54	98.00	14.05	19.49
T1	Mean	13.56	1.09	98.00	11.79	15.39
T1	Mean+1·SD	10.33	1.42	98.00	7.91	12.89
T2	Mean-1·SD	13.16	1.62	98.00	10.63	16.02
T2	Mean	11.72	1.15	98.00	10.19	13.65
T2	Mean+1·SD	10.28	1.51	98.00	8.16	12.89
T3	Mean-1·SD	13.26	1.67	98.00	10.86	15.88
T3	Mean	11.64	1.18	98.00	10.02	13.66
T3	Mean+1·SD	10.02	1.57	98.00	7.51	12.76

 
Results Plots
 
Assumption Checks
Test for Normality of residuals
Test	Statistics	p
Kolmogorov-Smirnov	0.06	0.212
Shapiro-Wilk	0.98	<.001
Note. ties should not be present for the one-sample Kolmogorov-Smirnov test

 
Q-Q Plot
 
 
 
![fig 1 bw](https://github.com/user-attachments/assets/c49266e9-867c-45cf-9b64-847ce014709b)

![figure1](https://github.com/user-attachments/assets/a0943a92-7600-420d-a0b1-74c863d566e1)

