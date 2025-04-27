# IP_Model
Interpersonal Skill Evaluation Model

The structured summary of resumes is fed directly to this model. 
The model architecture for evaluating candidates' interpersonal skills is designed to analyze structured summaries of resumes and produce an overall interpersonal skill score. Here's an overview of the process: 
1.	Input:
•	Structured summary of resumes containing details about skills, projects, leadership roles, and activities.
2.	Model Process:
•	Quantitative Analysis:
	Count the presence of key interpersonal skills such as communication, leadership, and teamwork.
	Use NLP methods to map skill occurrences into a matrix, summarizing the candidate's skill profile.
•	Fuzzy Logic Scoring:
	Apply fuzzy logic to assign qualitative scores (e.g., Poor, Moderate, Good, Excellent).
	Use membership functions to interpret skill counts and provide a flexible, nuanced grading.
•	Weighted Aggregation:
	Combine individual skill scores using category-specific weights.
	Aggregate the scores to produce an average that forms the overall evaluation.
	Classify the overall score using fuzzy categories (e.g., "Good (75%)", "Excellent (90%)").
3.	Output:
•	An overall score that reflects the candidate's interpersonal skill level.
•	The score is presented as a qualitative label and percentage, allowing for quick assessment and comparison.
•	This architecture ensures a thorough analysis that quantifies skill presence, uses flexible grading for better interpretation, and integrates scores meaningfully to reflect overall interpersonal competency.

