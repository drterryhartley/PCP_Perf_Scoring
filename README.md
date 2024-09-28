# PCP_Perf_Scoring
Ranking system to develop PCP performance scoring based on quality and efficiency

What the code does - 
Data Aggregation: Multiple patients are assigned to each PCP. The patient-level quality and efficiency measures are averaged per PCP.
PCP-Level Data: After aggregating, the performance score is calculated for each PCP based on their patients' metrics.
Performance Ranking: Each PCP is ranked according to their performance score, which is derived from the aggregated quality and efficiency measures.


Quality Measures (60% total weight):
Preventive Care Compliance – 40% of the total quality score
Chronic Disease Management – 40% of the total quality score
Patient Satisfaction – 20% of the total quality score
Combined, these three quality measures make up 60% of the total performance score.

Efficiency Measures (40% total weight):
Time per Visit – 30% of the total efficiency score (inverted, as lower is better)
Cost per Patient – 30% of the total efficiency score (inverted, as lower is better)
Referral Rate – 40% of the total efficiency score (inverted, as lower is better)
Combined, these efficiency measures make up 40% of the total performance score.

Summary of Weights:
60% weight is given to Quality (Preventive Care Compliance, Chronic Disease Management, and Patient Satisfaction).
40% weight is given to Efficiency (Time per Visit, Cost per Patient, and Referral Rate).
This balance gives more importance to quality but still considers efficiency measures as a significant factor. 
