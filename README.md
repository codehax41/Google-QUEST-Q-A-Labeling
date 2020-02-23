# Google-QUEST-Q-A-Labeling
Computers are really good at answering questions with single, verifiable answers. But, humans are often still better at answering questions about opinions, recommendations, or personal experiences.

*Humans are better at addressing subjective questions that require a deeper, multidimensional understanding of context - something computers aren't trained to do well…yet.. Questions can take many forms - some have multi-sentence elaborations, others may be simple curiosity or a fully developed problem. They can have multiple intents, or seek advice and opinions. Some may be helpful and others interesting. Some are simple right or wrong.*

Unfortunately, it’s hard to build better subjective question-answering algorithms because of a lack of data and predictive models. That’s why the CrowdSource team at Google Research, a group dedicated to advancing NLP and other types of ML science via crowdsourcing, has collected data on a number of these quality scoring aspects.

In this competition, you’re challenged to use this new dataset to build predictive algorithms for different subjective aspects of question-answering. The question-answer pairs were gathered from nearly 70 different websites, in a "common-sense" fashion. Our raters received minimal guidance and training, and relied largely on their subjective interpretation of the prompts. As such, each prompt was crafted in the most intuitive fashion so that raters could simply use their common-sense to complete the task. By lessening our dependency on complicated and opaque rating guidelines, we hope to increase the re-use value of this data set. What you see is what you get!

Demonstrating these subjective labels can be predicted reliably can shine a new light on this research area. Results from this competition will inform the way future intelligent Q&A systems will get built, hopefully contributing to them becoming more human-like.

Submissions to this competition must be made through Notebooks. Your Notebook will re-run automatically against an unseen test set, and needs to output a file named submission.csv. You can still train a model offline, upload it as a dataset, and use the notebook exclusively to perform inference. <br>

# In order for the "Submit to Competition" button to be active after a commit, the following conditions must be met:

- CPU Notebooks <= 9 hours run-time
- GPU Notebooks <= 2 hours run-time
- Internet must be turned off

# File descriptions
- train.csv - the training data (target labels are the last 30 columns)
- test.csv - the test set (you must predict 30 labels for each test set row)
- sample_submission.csv - a sample submission file in the correct format; column names are the 30 target labels
