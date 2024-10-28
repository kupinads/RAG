# Project Title: RAG System with NVIDIA and OpenAI Models

## Overview

This project explores the implementation of a Retrieval-Augmented Generation (RAG) system utilizing both NVIDIA and OpenAI models. By integrating these two distinct approaches, the project aims to enhance response generation capabilities and leverage the strengths of each model for improved performance.

## Features

- **Two Distinct Approaches**: This project employs both NVIDIA and OpenAI models, each representing a unique approach to enhance response generation capabilities.
- **Contextual Accuracy**: All responses demonstrate a high level of accuracy and effectively utilize the available context.
- **Conciseness with Reranker**: The application of a reranker refines responses, ensuring they are concise and relevant by eliminating extraneous information not specified in the queries.
- **Experimentation**: A thorough comparison of the query engine's performance with and without the reranker reveals insights into the impact of contextual information on response quality.

## Results

Below are the results of various queries, illustrating the differences between responses generated with and without the reranker. It was observed that while the `similarity_top_k=5` parameter was set during experimentation, the outcomes without the reranker were similar to those achieved with it, indicating that excessive contextual information can lead to vagueness when the reranker is not applied.

## Improvements

The project can be enhanced by integrating image embedding models. For instance, implementing OpenAI's CLIP model would facilitate effective extraction and representation of visual information. Additionally, identifying a comparable model for NVIDIA would further strengthen the project's capabilities.
