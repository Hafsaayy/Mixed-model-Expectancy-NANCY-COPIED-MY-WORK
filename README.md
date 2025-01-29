This women copied my work and use this project as her own work. 
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


Mixed model BAI CREDIBILITY
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


Mixed Model
Model Info
Info	 	 
Model Type	Mixed Model	Linear Mixed model for continuous y
Model	lme	BAI ~ 1 + Expectancy + Time_C + Time_C:Expectancy + ( 1 | Participant )
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
Conditional	0.58	9	172.00	<.001
Marginal	0.33	7	145.84	<.001

 
Additional Indices
Info	Model Value	Comment
LogLikelihood	-998.26	 
AIC	2018.51	Less is better
BIC	2058.34	Less is better

 
Fixed Effects Omnibus Tests
 	F	df	df (res)	p
Expectancy	6.88	1	178.00	0.009
Time_C	55.43	3	178.00	<.001
Expectancy ✻ Time_C	4.98	3	178.00	0.002

 
Parameter Estimates (Fixed coefficients)
	95% Confidence Intervals	
Names	Effect	Estimate	SE	Lower	Upper	df	t	p
(Intercept)	(Intercept)	15.50	0.77	14.63	16.57	178.00	20.22	<.001
Expectancy	Expectancy	-1.13	0.43	-1.84	-0.16	178.00	-2.62	0.009
Time_C1	T1 - T0	-11.35	1.15	-13.80	-8.49	178.00	-9.91	<.001
Time_C2	T2 - T0	-13.12	1.24	-15.26	-10.30	178.00	-10.55	<.001
Time_C3	T3 - T0	-13.29	1.27	-15.67	-10.40	178.00	-10.49	<.001
Expectancy ✻ Time_C1	Expectancy ✻ (T1 - T0)	-3.35	0.88	-5.41	-1.61	178.00	-3.83	<.001
Expectancy ✻ Time_C2	Expectancy ✻ (T2 - T0)	-2.37	0.92	-4.20	-0.72	178.00	-2.58	0.011
Expectancy ✻ Time_C3	Expectancy ✻ (T3 - T0)	-2.40	0.92	-4.27	-0.54	178.00	-2.60	0.010

 
Random Components
Groups	Name	Variance	SD	ICC	Phi
Participant	(Intercept)	31.04	5.57	0.37	0.10
Residual	 	52.52	7.25	 	 
Note. Number of Obs: 284 , Number of groups: Participant 99

 
Simple Effects
ANOVA for Simple Effects of Time_C
Moderator	
Expectancy	F	Num df	Den df	p
Mean-1·SD	12.94	3.00	178.00	<.001
Mean	55.43	3.00	178.00	<.001
Mean+1·SD	37.46	3.00	178.00	<.001

 
Parameter Estimates for simple effects of Time_C
Moderator		95% Confidence Intervals	
Expectancy	Effect	Estimate	SE	Lower	Upper	df	t	p
Mean-1·SD	T1 - T0	-6.42	1.69	-9.75	-3.09	178.00	-3.80	<.001
 	T2 - T0	-9.62	1.81	-13.20	-6.05	178.00	-5.31	<.001
 	T3 - T0	-9.75	1.79	-13.29	-6.22	178.00	-5.44	<.001
Mean	T1 - T0	-11.35	1.15	-13.61	-9.09	178.00	-9.91	<.001
 	T2 - T0	-13.12	1.24	-15.57	-10.67	178.00	-10.55	<.001
 	T3 - T0	-13.29	1.27	-15.79	-10.79	178.00	-10.49	<.001
Mean+1·SD	T1 - T0	-16.29	1.76	-19.77	-12.82	178.00	-9.25	<.001
 	T2 - T0	-16.62	1.87	-20.30	-12.93	178.00	-8.91	<.001
 	T3 - T0	-16.83	1.93	-20.63	-13.03	178.00	-8.74	<.001

 
Estimated Marginal Means
Estimate Marginal Means - Expectancy
	95% Confidence Intervals
Expectancy	Mean	SE	df	Lower	Upper
Mean-1·SD	17.17	0.99	98.00	15.41	18.69
Mean	15.50	0.77	98.00	14.63	16.55
Mean+1·SD	13.83	1.00	98.00	12.63	15.62

 
Estimate Marginal Means - Time_C
	95% Confidence Intervals
Time_C	Mean	SE	df	Lower	Upper
T0	24.90	0.94	98.00	22.88	26.67
T1	13.69	1.07	98.00	11.96	15.64
T2	11.88	1.14	98.00	10.40	13.77
T3	11.71	1.16	98.00	10.05	13.72

 
Estimate Marginal Means - Time_C ✻ Expectancy
	95% Confidence Intervals
Time_C	Expectancy	Mean	SE	df	Lower	Upper
T0	Mean-1·SD	23.61	1.20	98.00	20.63	25.89
T0	Mean	24.94	0.95	98.00	22.93	26.72
T0	Mean+1·SD	26.27	1.47	98.00	23.37	29.56
T1	Mean-1·SD	17.20	1.49	98.00	14.22	20.21
T1	Mean	13.59	1.07	98.00	11.87	15.51
T1	Mean+1·SD	9.98	1.40	98.00	7.87	12.48
T2	Mean-1·SD	13.99	1.60	98.00	11.49	16.39
T2	Mean	11.82	1.13	98.00	10.35	13.72
T2	Mean+1·SD	9.65	1.48	98.00	7.80	12.21
T3	Mean-1·SD	13.86	1.57	98.00	11.10	16.39
T3	Mean	11.65	1.16	98.00	10.00	13.65
T3	Mean+1·SD	9.44	1.55	98.00	7.35	12.28

 

 

Mixed Model
Model Info
Info	 	 
Model Type	Mixed Model	Linear Mixed model for continuous y
Model	lme	BAI ~ 1 + Expectancy + Time_C + Time_C:Expectancy + ( 1 | Participant )
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
Conditional	0.58	9	172.00	<.001
Marginal	0.33	7	145.84	<.001

 
Additional Indices
Info	Model Value	Comment
LogLikelihood	-998.26	 
AIC	2018.51	Less is better
BIC	2058.34	Less is better

 
Fixed Effects Omnibus Tests
 	F	df	df (res)	p
Expectancy	6.88	1	178.00	0.009
Time_C	55.43	3	178.00	<.001
Expectancy ✻ Time_C	4.98	3	178.00	0.002

 
Parameter Estimates (Fixed coefficients)
	95% Confidence Intervals	
Names	Effect	Estimate	SE	Lower	Upper	df	t	p
(Intercept)	(Intercept)	15.50	0.77	14.63	16.57	178.00	20.22	<.001
Expectancy	Expectancy	-1.13	0.43	-1.84	-0.16	178.00	-2.62	0.009
Time_C1	T1 - T0	-11.35	1.15	-13.80	-8.49	178.00	-9.91	<.001
Time_C2	T2 - T0	-13.12	1.24	-15.26	-10.30	178.00	-10.55	<.001
Time_C3	T3 - T0	-13.29	1.27	-15.67	-10.40	178.00	-10.49	<.001
Expectancy ✻ Time_C1	Expectancy ✻ (T1 - T0)	-3.35	0.88	-5.41	-1.61	178.00	-3.83	<.001
Expectancy ✻ Time_C2	Expectancy ✻ (T2 - T0)	-2.37	0.92	-4.20	-0.72	178.00	-2.58	0.011
Expectancy ✻ Time_C3	Expectancy ✻ (T3 - T0)	-2.40	0.92	-4.27	-0.54	178.00	-2.60	0.010

 
Random Components
Groups	Name	Variance	SD	ICC	Phi
Participant	(Intercept)	31.04	5.57	0.37	0.10
Residual	 	52.52	7.25	 	 
Note. Number of Obs: 284 , Number of groups: Participant 99

 
Simple Effects
ANOVA for Simple Effects of Time_C
Moderator	
Expectancy	F	Num df	Den df	p
Mean-1·SD	12.94	3.00	178.00	<.001
Mean	55.43	3.00	178.00	<.001
Mean+1·SD	37.46	3.00	178.00	<.001

 
Parameter Estimates for simple effects of Time_C
Moderator		95% Confidence Intervals	
Expectancy	Effect	Estimate	SE	Lower	Upper	df	t	p
Mean-1·SD	T1 - T0	-6.42	1.69	-9.75	-3.09	178.00	-3.80	<.001
 	T2 - T0	-9.62	1.81	-13.20	-6.05	178.00	-5.31	<.001
 	T3 - T0	-9.75	1.79	-13.29	-6.22	178.00	-5.44	<.001
Mean	T1 - T0	-11.35	1.15	-13.61	-9.09	178.00	-9.91	<.001
 	T2 - T0	-13.12	1.24	-15.57	-10.67	178.00	-10.55	<.001
 	T3 - T0	-13.29	1.27	-15.79	-10.79	178.00	-10.49	<.001
Mean+1·SD	T1 - T0	-16.29	1.76	-19.77	-12.82	178.00	-9.25	<.001
 	T2 - T0	-16.62	1.87	-20.30	-12.93	178.00	-8.91	<.001
 	T3 - T0	-16.83	1.93	-20.63	-13.03	178.00	-8.74	<.001

 
Estimated Marginal Means
Estimate Marginal Means - Expectancy
	95% Confidence Intervals
Expectancy	Mean	SE	df	Lower	Upper
Mean-1·SD	17.17	0.99	98.00	15.41	18.69
Mean	15.50	0.77	98.00	14.63	16.55
Mean+1·SD	13.83	1.00	98.00	12.63	15.62

 
Estimate Marginal Means - Time_C
	95% Confidence Intervals
Time_C	Mean	SE	df	Lower	Upper
T0	24.90	0.94	98.00	22.88	26.67
T1	13.69	1.07	98.00	11.96	15.64
T2	11.88	1.14	98.00	10.40	13.77
T3	11.71	1.16	98.00	10.05	13.72

 
Estimate Marginal Means - Time_C ✻ Expectancy
	95% Confidence Intervals
Time_C	Expectancy	Mean	SE	df	Lower	Upper
T0	Mean-1·SD	23.61	1.20	98.00	20.63	25.89
T0	Mean	24.94	0.95	98.00	22.93	26.72
T0	Mean+1·SD	26.27	1.47	98.00	23.37	29.56
T1	Mean-1·SD	17.20	1.49	98.00	14.22	20.21
T1	Mean	13.59	1.07	98.00	11.87	15.51
T1	Mean+1·SD	9.98	1.40	98.00	7.87	12.48
T2	Mean-1·SD	13.99	1.60	98.00	11.49	16.39
T2	Mean	11.82	1.13	98.00	10.35	13.72
T2	Mean+1·SD	9.65	1.48	98.00	7.80	12.21
T3	Mean-1·SD	13.86	1.57	98.00	11.10	16.39
T3	Mean	11.65	1.16	98.00	10.00	13.65
T3	Mean+1·SD	9.44	1.55	98.00	7.35	12.28


 ![fig 2 bw](https://github.com/user-attachments/assets/80f33133-5927-419b-b3c3-a141880963cf)

 ![figure 2](https://github.com/user-attachments/assets/0bc94e50-98f6-4e00-af5c-ddad4f2de575) 

  MIXED MODEL CSR CREDIBILITY
  Mixed Model
Model Info
Info	 	 
Model Type	Mixed Model	Linear Mixed model for continuous y
Model	lme	CSR ~ 1 + TimeC + Credibility + TimeC:Credibility + ( 1 | Participant )
Distribution	Gaussian	Normal distribution of residuals
Direction	y	Dependend variable scores
Residuals	Autoregressive 1	within cluster Participant
Sample size	224	 
Converged	yes	 
Y transform	none	 
C.I. method	Bootstrap percent	10000 bootstrap samples

 
Model Results
Model Fit
Type	R²	df	LRT X²	p
Conditional	0.51	7	166.40	<.001
Marginal	0.51	5	162.40	<.001

 
Additional Indices
Info	Model Value	Comment
LogLikelihood	-434.33	 
AIC	886.67	Less is better
BIC	917.13	Less is better

 
Fixed Effects Omnibus Tests
 	F	df	df (res)	p
TimeC	105.42	2	120.00	<.001
Credibility	14.41	1	120.00	<.001
TimeC ✻ Credibility	4.74	2	120.00	0.010

 
Parameter Estimates (Fixed coefficients)
	95% Confidence Intervals	
Names	Effect	Estimate	SE	Lower	Upper	df	t	p
(Intercept)	(Intercept)	4.06	0.14	3.87	4.27	120.00	29.66	<.001
TimeC1	T1 - T0	-2.94	0.24	-3.48	-2.38	120.00	-12.34	<.001
TimeC2	T3 - T0	-3.54	0.28	-4.04	-2.99	120.00	-12.79	<.001
Credibility	Credibility	-0.47	0.12	-0.67	-0.14	120.00	-3.80	<.001
TimeC1 ✻ Credibility	(T1 - T0) ✻ Credibility	-0.50	0.26	-1.15	-0.11	120.00	-1.95	0.054
TimeC2 ✻ Credibility	(T3 - T0) ✻ Credibility	-0.84	0.27	-1.45	-0.46	120.00	-3.07	0.003

 
Random Components
Groups	Name	Variance	SD	ICC	Phi
Participant	(Intercept)	0.00	0.00	0.00	0.28
Residual	 	2.93	1.71	 	 
Note. Number of Obs: 224 , Number of groups: Participant 99

 
Post Hoc Tests
Post Hoc comparison: TimeC
Comparison		95% Confidence Intervals	
TimeC	vs	TimeC	Difference	SE	Lower	Upper	t	df	p
T0	-	T1	2.93	0.24	.	.	12.30	120.00	<.001
T0	-	T3	3.52	0.28	.	.	12.74	120.00	<.001
T1	-	T3	0.59	0.26	.	.	2.25	120.00	0.026

 
Simple Effects
ANOVA for Simple Effects of TimeC
Moderator	
Credibility	F	Num df	Den df	p
Mean-1·SD	32.42	2.00	120.00	<.001
Mean	105.42	2.00	120.00	<.001
Mean+1·SD	69.13	2.00	120.00	<.001

 
Parameter Estimates for simple effects of TimeC
Moderator		95% Confidence Intervals	
Credibility	Effect	Estimate	SE	Lower	Upper	df	t	p
Mean-1·SD	T1 - T0	-2.43	0.35	-3.13	-1.74	120.00	-6.95	<.001
 	T3 - T0	-2.68	0.39	-3.46	-1.91	120.00	-6.88	<.001
Mean	T1 - T0	-2.94	0.24	-3.42	-2.47	120.00	-12.34	<.001
 	T3 - T0	-3.54	0.28	-4.08	-2.99	120.00	-12.79	<.001
Mean+1·SD	T1 - T0	-3.45	0.36	-4.16	-2.74	120.00	-9.64	<.001
 	T3 - T0	-4.39	0.39	-5.17	-3.61	120.00	-11.14	<.001

 
Estimated Marginal Means
Estimate Marginal Means - TimeC
	95% Confidence Intervals
TimeC	Mean	SE	df	Lower	Upper
T0	6.22	0.18	98.00	5.95	6.50
T1	3.28	0.21	98.00	2.89	3.78
T3	2.70	0.22	98.00	2.31	3.10

 
Estimate Marginal Means - Credibility
	95% Confidence Intervals
Credibility	Mean	SE	df	Lower	Upper
Mean-1·SD	4.54	0.19	98.00	4.16	4.84
Mean	4.06	0.14	98.00	3.88	4.28
Mean+1·SD	3.58	0.18	98.00	3.33	4.00

 
Estimate Marginal Means - TimeC ✻ Credibility
	95% Confidence Intervals
TimeC	Credibility	Mean	SE	df	Lower	Upper
T0	Mean-1·SD	6.24	0.23	98.00	5.65	6.52
T0	Mean	6.22	0.18	98.00	5.96	6.50
T0	Mean+1·SD	6.20	0.28	98.00	5.88	6.87
T1	Mean-1·SD	3.81	0.30	98.00	3.29	4.34
T1	Mean	3.27	0.20	98.00	2.89	3.77
T1	Mean+1·SD	2.74	0.27	98.00	2.12	3.44
T3	Mean-1·SD	3.56	0.33	98.00	2.98	4.17
T3	Mean	2.68	0.22	98.00	2.30	3.09
T3	Mean+1·SD	1.81	0.29	98.00	1.29	2.40

 
Results Plots
 
Assumption Checks
Test for Normality of residuals
Test	Statistics	p
Kolmogorov-Smirnov	0.08	0.087
Shapiro-Wilk	0.99	0.118
Note. ties should not be present for the one-sample Kolmogorov-Smirnov test

 
Q-Q Plot
 


![fig 3 bw](https://github.com/user-attachments/assets/450d7e89-055b-40bd-9b9b-9de82441bc71)

![figure 3](https://github.com/user-attachments/assets/9c3313d7-0f14-4084-a389-2b108620e63b)




MIXED MODEL CSR EXPECTANCY
Mixed Model
Model Info
Info	 	 
Model Type	Mixed Model	Linear Mixed model for continuous y
Model	lme	CSR ~ 1 + TimeC + Expectancy + TimeC:Expectancy + ( 1 | Participant )
Distribution	Gaussian	Normal distribution of residuals
Direction	y	Dependend variable scores
Residuals	Autoregressive 1	within cluster Participant
Sample size	224	 
Converged	yes	 
Y transform	none	 
C.I. method	Bootstrap percent	10000 bootstrap samples

 
Model Results
Model Fit
Type	R²	df	LRT X²	p
Conditional	0.53	7	171.74	<.001
Marginal	0.53	5	167.74	<.001

 
Additional Indices
Info	Model Value	Comment
LogLikelihood	-431.66	 
AIC	881.33	Less is better
BIC	911.79	Less is better

 
Fixed Effects Omnibus Tests
 	F	df	df (res)	p
TimeC	111.62	2	120.00	<.001
Expectancy	18.22	1	120.00	<.001
TimeC ✻ Expectancy	6.97	2	120.00	0.001

 
Parameter Estimates (Fixed coefficients)
	95% Confidence Intervals	
Names	Effect	Estimate	SE	Lower	Upper	df	t	p
(Intercept)	(Intercept)	4.05	0.13	3.86	4.26	120.00	30.28	<.001
TimeC1	T1 - T0	-2.94	0.23	-3.44	-2.36	120.00	-12.54	<.001
TimeC2	T3 - T0	-3.60	0.27	-4.05	-3.02	120.00	-13.28	<.001
Expectancy	Expectancy	-0.36	0.09	-0.49	-0.18	120.00	-4.27	<.001
TimeC1 ✻ Expectancy	(T1 - T0) ✻ Expectancy	-0.58	0.17	-0.96	-0.25	120.00	-3.31	0.001
TimeC2 ✻ Expectancy	(T3 - T0) ✻ Expectancy	-0.63	0.19	-0.96	-0.29	120.00	-3.33	0.001

 
Contrast Coefficients
Factor: TimeC
Level=T0	Level=T1	Level=T3	Name	Contrast
-0.33	0.67	-0.33	TimeC1	T1 - T0
-0.33	-0.33	0.67	TimeC2	T3 - T0

 
Random Components
Groups	Name	Variance	SD	ICC	Phi
Participant	(Intercept)	0.00	0.00	0.00	0.28
Residual	 	2.83	1.68	 	 
Note. Number of Obs: 224 , Number of groups: Participant 99

 
Post Hoc Tests
Post Hoc comparison: TimeC
Comparison		95% Confidence Intervals	
TimeC	vs	TimeC	Difference	SE	Lower	Upper	t	df	p
T0	-	T1	2.91	0.23	.	.	12.43	120.00	<.001
T0	-	T3	3.57	0.27	.	.	13.19	120.00	<.001
T1	-	T3	0.66	0.26	.	.	2.57	120.00	0.011

 
Simple Effects
ANOVA for Simple Effects of TimeC
Moderator	
Expectancy	F	Num df	Den df	p
Mean-1·SD	29.66	2.00	120.00	<.001
Mean	111.62	2.00	120.00	<.001
Mean+1·SD	78.26	2.00	120.00	<.001

 
Parameter Estimates for simple effects of TimeC
Moderator		95% Confidence Intervals	
Expectancy	Effect	Estimate	SE	Lower	Upper	df	t	p
Mean-1·SD	T1 - T0	-2.09	0.34	-2.77	-1.42	120.00	-6.12	<.001
 	T3 - T0	-2.68	0.38	-3.42	-1.93	120.00	-7.10	<.001
Mean	T1 - T0	-2.94	0.23	-3.40	-2.47	120.00	-12.54	<.001
 	T3 - T0	-3.60	0.27	-4.13	-3.06	120.00	-13.28	<.001
Mean+1·SD	T1 - T0	-3.78	0.35	-4.47	-3.09	120.00	-10.82	<.001
 	T3 - T0	-4.51	0.40	-5.30	-3.73	120.00	-11.42	<.001

 
Estimated Marginal Means
Estimate Marginal Means - TimeC
	95% Confidence Intervals
TimeC	Mean	SE	df	Lower	Upper
T0	6.23	0.17	98.00	5.94	6.49
T1	3.32	0.20	98.00	2.92	3.74
T3	2.66	0.22	98.00	2.27	3.09

 
Estimate Marginal Means - Expectancy
	95% Confidence Intervals
Expectancy	Mean	SE	df	Lower	Upper
Mean-1·SD	4.58	0.18	98.00	4.24	4.86
Mean	4.05	0.13	98.00	3.85	4.26
Mean+1·SD	3.52	0.18	98.00	3.26	3.86

 
Estimate Marginal Means - TimeC ✻ Expectancy
	95% Confidence Intervals
TimeC	Expectancy	Mean	SE	df	Lower	Upper
T0	Mean-1·SD	6.17	0.23	98.00	5.75	6.49
T0	Mean	6.23	0.17	98.00	5.94	6.49
T0	Mean+1·SD	6.29	0.28	98.00	5.82	6.78
T1	Mean-1·SD	4.08	0.29	98.00	3.56	4.70
T1	Mean	3.29	0.20	98.00	2.90	3.72
T1	Mean+1·SD	2.51	0.26	98.00	1.96	3.15
T3	Mean-1·SD	3.49	0.31	98.00	2.91	3.99
T3	Mean	2.63	0.22	98.00	2.23	3.06
T3	Mean+1·SD	1.77	0.29	98.00	1.28	2.38

 
Results Plots
 
Assumption Checks
Test for Normality of residuals
Test	Statistics	p
Kolmogorov-Smirnov	0.10	0.031
Shapiro-Wilk	0.99	0.091
Note. ties should not be present for the one-sample Kolmogorov-Smirnov test

 


![fig 4 bw](https://github.com/user-attachments/assets/61a14d0a-d5c2-4bb9-a3db-c66cabb5ded8)

![figure 4](https://github.com/user-attachments/assets/c98ab601-ef61-489e-af02-169be70ca093)





