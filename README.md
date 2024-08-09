"# LLM-Science-Exam" 
The objective of this project was to predict correct answers for multiple-choice questions using a publicly available dataset from the Kaggle competition, "LLM Science Exam". The dataset comprised questions based on scientific knowledge, and our focus was on utilizing large language models (LLMs) for answer prediction and keep improving the performance using different strategies. The key areas of emphasis were prompt engineering and in-context learning using models like GPT-3.5-turbo, GPT-4o-mini, and GPT-4-turbo. 

For detailed information about the project, please refer to the following files:

          "PhdStandupBoard.xlsx": Contains comprehensive details about the project.
          "Kaggle Project Workflow": Outlines the study design and overall approach.
          "Kaggle Project Progress": Documents the steps taken in performing experiments, including the inputs used and some results.
          "Important Points": Provides clarifications and tips for running the Jupyter notebooks.

Startup dataset file for analysis: "train.csv"

Few-Shot Experiments: Various experiments are conducted using Jupyter notebooks, named with the pattern "2shotphysics1each.ipynb". The corresponding output files are named with the experiment file name followed by "-results", for example, "2shotphysics1each-results.csv".

In the "Updated" folder, the final experiments were conducted using zero-shot inference and Prompt 5 with a temperature setting of 0 across all three GPT models. The outputs from these models were combined using an ensemble method in "majority_voting.ipynb". The final experiment, with files zeroshot_tempset, was performed with GPT-4-turbo at a temperature setting of 0.8743, achieving an 86% performance.




 
