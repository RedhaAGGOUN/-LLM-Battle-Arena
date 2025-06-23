LLM Battle Arena

A Streamlit-based web application to compare the performance of multiple Large Language Models (LLMs) in fact-checking tasks across different audiences, temperatures, and judges. The application allows users to run battles between models, evaluate their responses, and visualize results to determine the best model for specific scenarios.

Features





Model Comparison: Pit two LLMs against each other (e.g., Mistral-7B, Llama-3-70B) to evaluate their fact-checking abilities.



Flexible Configurations: Customize battles by selecting:





Statements from a predefined fact database or custom inputs.



Audiences (Kid, Teenager, Adult).



Temperature settings (Low: 0.3, Mid: 0.7, High: 1.0).



Judge models to evaluate responses.



Fact categories (e.g., Science, Nature, Health).



Multiple Run Modes:





Single battle for a specific statement.



Run all statements in selected categories.



Run all possible combinations of models, judges, statements, audiences, and temperatures.



Evaluation Metrics:





Correctness of responses (True/False).



Quality of explanations (1-5 scale).



Justification provided (Yes/No).



Language appropriateness and neutral tone.



Visualizations: Interactive charts (bar, radar) to compare model performance.



Export Options: Download results and summaries as CSV files.



Debugging Support: Detailed logging to diagnose API or evaluation issues.

Prerequisites





Python 3.8+



Together AI API Key: Required for accessing LLM inference endpoints.



Dependencies:





Install required Python packages listed in requirements.txt.
