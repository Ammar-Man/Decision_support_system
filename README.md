Build a decision tree for HR that supports application filtering using historical data from 'hr_train_1.csv'. The decision tree should set the 'ignore' flag to True for applicants who are not of interest to the HR department. You can start with the provided code or use the code from the 'Data Science from Scratch' resource, available on Google Colab or GitHub. Test your decision tree with four sample applicants and present the results. Analyze the rules within your decision tree.

Provide justifications for your insights relevant to the HR department, such as:

1. Total number of results with the current dataset.
2. The shortest path in the decision tree for accepting/rejecting an applicant.
3. Any trends or advantages that an applicant might have within your decision tree.

Consider utilizing data exploration (EDA) to uncover these insights.

Imagine that the HR department has begun collecting additional data, specifically the applicant's gender. Add a 'gender' column to your dataset and populate it with random values (0, 1, 2). Develop a test to demonstrate potential bias in your decision tree, showing that approximately two-thirds of applicants with a 'gender' value of 2 will be flagged as 'ignore: True'. Present this bias to the HR department and provide an explanation either for or against it.

To achieve this:

1. Add the 'gender' column to your dataset and fill it with random values.
2. Prove that roughly two-thirds of applicants with 'gender' 2 are flagged as 'ignore: True' in your test.
3. Explain or counter-explain this bias using data exploration and provide a justification to the HR department.

Consider splitting your data into test and train sets (e.g., 20% for testing and 80% for training) to conduct this analysis.