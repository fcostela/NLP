# NLP
NLP with Python with a Cognitive database 
There are 4 cognitive status cases (normal, impaired not MCI, MCI, dementia). 
Dataset used in one of my publications: "Narrative video scene description task discriminates between levels of cognitive impairment in Alzheimer’s disease." https://psycnet.apa.org/record/2020-05494-001 

- Notebook to check what can be done using NLP (TF-IDF approach)
I predicted the cognitive status by using number of words in the descriptions and also apply a NLP approach that examines the vocabulary using the TF-IDF metric.

- Notebook to calculate new metric comparable to the information acquisition score and prediction using the new model using Random Forest classifier. The new model is based on 4 features:
    **Matches with the top words (N=28) for that clip;
    
    **Number of words not mentioned in any of the descriptions for that clip;
    
    **Length of the description;
    
    **Averaged speech rate;
