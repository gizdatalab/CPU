This repo serves as the code-base which underlines all the work pertianing to [**Climate Policy Transformer: Utilizing NLP to track the coherence of Climate Policy Documents in the Context of the Paris Agreement**](https://aclanthology.org/2024.climatenlp-1.1/) 
paper presented at ACL2024 Climate Change and AI sub-group. The repo contians two major dir:
- Dataset: This repo has all the codebase used to process the [Climate Watch Sectoral Data](https://www.climatewatchdata.org/data-explorer/historical-emissions?historical-emissions-data-sources=climate-watch&historical-emissions-gases=all-ghg&historical-emissions-regions=All%20Selected&historical-emissions-sectors=total-including-lucf%2Ctotal-including-lucf&page=1)
           For more details on why, please visit the paper link proivded above.
- Classifiers: Climate Watch team has set-up a taxonomy based on which the climate policy documents are analyzed. The classiifers are trianed on these taxonomy to identify if the paragraph belongs to these catogories or not.
- *RAG (coming soon): We have used RAG where the Retirever step is replaced by Classifiers to perform the relevant information extraction from policy documents.*
