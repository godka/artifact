## SIGCOMM'21 Artifact (Paper #432)

This is a measurement paper with several types of experiments conducted for different purposes having different methodologies. To help evaluators quickly navigate and have the ability to understand the different pieces, we have created different folders for different experiments. There are README files within each folder that provide instructions on validating the experiment-specific artifacts. At the very top of the README instructions, we also specify which results/plots (e.g. Figure 2 in paper's PDF) the folder is responsible. Lastly, to make it easy here are some generic principles we followed for releasing the artifacts:

#### Dataset size
- If the dataset is small enough, we included the dataset file in this Github repo. itself. 
- If the dataset files are huge, we use a small sample of the dataset in the Github repo. to demonstrate the functionality/correctness. Evaluators can replace the small subset with the full dataset (provided using a link to a Shared Google Drive folder) to further validate. In either case, we provide full processed results as well. See next part for details. 


#### Data Analysis, Model/Plot Generation

- If data analysis is involved, our instructions will contain information on how to process the data. 
- No matter what the dataset size is, we provide the fully generated results and/or plots. If evaluator decides to run the analysis and/or plotting scripts, the outcome of processing will simply replace the existing files in the repository.
- For evaluating artifacts involved in section 5 (ABR video streaming), a lot of computing resources are required. We have therefore provided:
    1. a screencast to show how the results were generated
    2. output logs
    3. if one has their own compute resources, we provide instructions on how to evaluate.
    


As always, if there are any questions, feel free to reach out to us!  