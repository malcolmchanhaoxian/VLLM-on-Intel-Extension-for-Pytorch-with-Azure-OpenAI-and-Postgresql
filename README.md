# VLLM-on-Intel-Extension-for-Pytorch-with-Azure-OpenAI-and-Postgresql
Continuation of vLLM on IPEX (adding integration to Azure Postgresql and Azure OpenAI) 

## Introduction

This is a continuation of the Intel optimised Pytorch Extension (IPEX) on vLLM Model Serving Engine.
You can visit the previous repo here - [link](https://github.com/malcolmchanhaoxian/VLLM-on-Intel-Extension-for-Pytorch-.git)
This project achieves following outcomes:
1. Expand the client code base to perform Retrieval-Augmented-Generation (RAG)
2. Integrate the use of Azure OpenAI embeddings to perform the text extraction from the provided pdf document
3. Utilise Azure Database for Postgresql Flexible Servers to store the vector embeddings (with the use of pgvector extension)
<br>
Following framework has been updated to reflect the changes we are implementing.
<p align="center">
<img src = "https://github.com/user-attachments/assets/82bcb049-bc32-4733-bc1e-7b2143980a31" width = "700">
</p>

