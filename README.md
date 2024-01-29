# Topsis-Text-Classification

### Name: Raghav Dargan
### Roll No. 102103042

##  Overview

Text classification involves automatically categorizing textual documents into predefined labels. The process begins with data preparation, where a labeled dataset is collected. Text preprocessing follows, cleaning and transforming the text into numerical features. A machine learning model is then selected and trained on the labeled dataset

## Models

I have selected the following 5 pre-trained models from [Hugging Face](https://huggingface.co/):

1. [FlagEmbedding](https://huggingface.co/BAAI/bge-large-en-v1.5) - BAAI/bge-large-en-v1.5

2. [Cohere Embed V3](https://huggingface.co/Cohere/Cohere-embed-multilingual-v3.0) - cohere/Cohere-embed-multilingual-v3.0 

3. [Universal AnglE Embedding](https://huggingface.co/WhereIsAI/UAE-Large-V1) - WhereIsAI/UAE-Large-V1

4. [sf_model_e5](https://huggingface.co/jamesgpt1/sf_model_e5) - jamesgpt1/sf_model_e5

5. [E5-mistral-7b-instruct](https://huggingface.co/intfloat/e5-mistral-7b-instruct) - intfloat/e5-mistral-7b-instruct


## Dataset

I have used this dataset

   [ac](https://huggingface.co/datasets/mteb/amazon_counterfactual/viewer/en) - mteb/amazon_counterfactual


## Library 

I have refered to [MTEB: Massive Text Embedding Benchmark](https://arxiv.org/abs/2210.07316) research paper. I have used the scripts available at their [GitHub](https://github.com/embeddings-benchmark/mteb/tree/main) to calculate the metrics.

I have used my own topsis python package uploaded to PyPi to perform the topsis ananlysis on the data. To check out my package click [here](https://pypi.org/project/Topsis-Raghav-102103042/1.1.2/)


## BARGRAPH

Graph showing topsis score vs models

<image  width="600px" src="image1.png">

 ## Metrics

Table showing result of the topsis package on output.csv

<image  width="600px" src="image2.png">

##  TOPSIS Score Calculation
Utilized the custom 'Topsis-Raghav-102103042' package to compute TOPSIS scores based on the model performance metrics.
[Link to Topsis-Raghav-102103042 Package](https://pypi.org/project/Topsis-Raghav-102103042/)

   <section id="key-features">
        <h2>Key Features</h2>
        <ul>
            <li>
                <strong>Model Selection and Integration:</strong> Incorporates popular pretrained models, such as sf_model_e5 and
                UAE-Large-V1, to capture intricate patterns and semantic nuances within textual data.
            </li>
            <!-- Add other key features here -->
        </ul>
    </section>


   <section id="evaluation-metrics">
        <h2>Evaluation Metrics</h2>
        <ul>
            <li>Accuracy</li>
            <li>ap</li>
            <li>F1 Score (Macro and Micro)</li>
        </ul>
    </section>
    
 ## Analysis

sf_model_e5 has recieved **1st Rank** in this evaluation dataset. 

## Disclaimer

 *Note: I have given equal weightage to all the parameters  but depending on your task there may be more important metrics and their weightage may be different.*

