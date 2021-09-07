<!-- ABOUT THE PROJECT -->
## About The Project

Commit  messages  are  short,  natural  language  descriptions  of  changes  made  in  the  sourcecode.   The  typical  pipeline  of  committing  to  a  change  ends  with  uploading  updated  filesto a version control system with a short commit message to describe the intent behind the change. Maintaining high-quality documentation is critical to aid timely and  efficient  software  development. Unfortunately, developers  themselves  seem  to  neglect writing  high  quality  commit  messages.   As  a  result,  automated  generation  of  commit messages has been proposed as an alternative to the manual effort of writing commit messages. 

Our work for the GRM program involved finding ways to improve on the state-of-the-art LogGen model in order to generate better log messages. Our lines of work were as follows:
1. Improving the dataset by correctly conveying the rationale behind the commit
2. Reduce anisotropy in embedding space of vectors by incorporating context of code changes in CC2Vec vectors
3. For an unknown code change, summarize top k most similar code changes into a single output log message 
4. Improving the evaluation metric used for assessing quality of test data log messages

This repository in particular records my experiments done during 12th June 2021 and 8th September 2021. 

<!-- EXPERIMENTS -->
## Experiments

For both the experiments, I've used the Liu et al. dataset in tandum with the afrementioned LogGen model. The dataset is a standard benchmarking dataset that has been used over the years fot comparitive studies.

Experiment-1 deals with clustering the commits based on their cosine distance while experiment-2 deals with analysing the dataset syntactics.
