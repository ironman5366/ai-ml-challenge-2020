
# AI/ML Challenge 2020
Below are the instructions for your Github submission. Everything must be submitted prior to the challenge deadline of August 20th, 2020. For more information, please visit the [challenge website](https://www.challenge.gov/challenge/GSA-artificial-intelligence-AI-machine-learning-ML-challenge/).
 
## General Instructions:
 
1. [Fork this repository](https://help.github.com/en/articles/fork-a-repo) to your GitHub account.
2. Build your solution according to the Submission Requirements below and commit it to your fork.
3. When you are ready to submit your solution, [create a pull request](https://help.github.com/en/articles/creating-a-pull-request-from-a-fork) from your fork to this repository (GSA/ai-ml-challenge-2020; base: master).
4. Name your pull request “TeamName Submission” and feel free to write a short description of your submission. Make sure to uncheck “Allow edits by maintainers” before creating your pull request.
 
## Submission Requirements:
 
1. Create a folder in the “submissions” folder of your forked repository that contains all components of your solution and name it “YourTeamName_Submission.”
2. Within your solution folder, upload all relevant files (Add file > Upload files) to your forked repository according to the Submission Details below.
 
## Submission Details:
 
1. **Validation Data File (CSV document)**

* Name of the file: “TeamName Validation Data File”
* Includes classification of clauses contained in Validation File, along with confidence scores.
  * Clause ID
  * Clause Text
  * Prediction: 0 - acceptable, 1 - unacceptable
  * Prediction Probability - percent 
 
2. **Description of Methods Document (PDF, MS Word, or Jupyter Notebook document)** <br/>
*IMPORTANT: DO NOT INCLUDE ANY SENSITIVE INFORMATION IN THIS FILE.*

* Name of the file: “TeamName Description of Methods”
* Provides a comprehensive description of the data, methods and software used to complete the solution.
* Provides a demonstration of the process used to complete the model used in the solution, including data inputs and visualizations.
* Clearly explains the reasons for predictions made in the Validation Data File submission.
* Contains self-reported metrics of the solution, by providing:
  * Brier score
  * F1 score (also known as F-Measure)
 
3. **Folder containing Source Code, Input Data, and Compiled Models**<br/>
*Note: if any of these are unavailable, explain the reason in the Description of Methods Document.*

* Name of the folder: “TeamName Code and Data” with subfolders named “TeamName Source Code,” “TeamName Input Data,” and “TeamName Compiled Models”
* “TeamName Source Code” contains all source code used in the creation of the solution.
* “TeamName Input Data” contains all input data used in the creation of the solution.
* “TeamName Compiled Models” contains all compiled versions of models used in the solution.

## Additional Reference Information
Several additional references have beeen provided that teams may optionally use for the challenge. For more information, view the [Reference](reference/readme.md) section of this repository.
