# kaggle-arc-2024
 AI systems to efficiently learn new skills and solve open-ended problems


### Description
Current AI systems can not generalize to new problems outside their training data, despite extensive training on large datasets. LLMs have brought AI to the mainstream for a large selection of known tasks. However, progress towards Artificial General Intelligence (AGI) has stalled. Improvements in AGI could enable AI systems that think and invent alongside humans.

The Abstraction and Reasoning Corpus for Artificial General Intelligence (ARC-AGI) benchmark measures an AI system's ability to efficiently learn new skills. Humans easily score 85% in ARC, whereas the best AI systems only score 34%. The ARC Prize competition encourages researchers to explore ideas beyond LLMs, which depend heavily on large datasets and struggle with novel problems.

This competition includes several components. The competition as described here carries a prize of $100,000 with an additional $500,000 available if any team can beat a score of 85% on the leaderboard. Further opportunities outside of Kaggle are also available with associated prizes- to learn more visit ARCprize.org.

Your work could contribute to new AI problem-solving applicable across industries. Vastly improved AGI will likely reshape human-machine interactions. Winning solutions will be open-sourced to promote transparency and collaboration in the field of AGI.



# Evaluation
This competition evaluates submissions on the percentage of correct predictions. For each task, you should predict exactly 2 outputs for every test input grid contained in the task. (Tasks can have more than one test input that needs a predicted output.) Each task test output has one ground truth. For a given task output, any of the 2 predicted outputs matches the ground truth exactly, you score 1 for that task test output, otherwise 0. The final score is the sum averaged of the highest score per task output divided by the total number of task test outputs.
