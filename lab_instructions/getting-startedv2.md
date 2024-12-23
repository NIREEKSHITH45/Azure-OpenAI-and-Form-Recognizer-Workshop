# Create and Deploy a Document Intelligence Custom Model

### Overall Estimated Duration: 1 hour

## Overview

In this lab focuses on creating and utilizing a custom Document Intelligence solution in Azure to analyze and process documents effectively. The implementation includes resource setup, model training, pipeline integration, and search optimization.

## Objective

Participants should have:

- Use a sample training data set to train a custom model in the Azure Document Intelligence Studio.

- Label the training data documents with custom fields of interest.

- Test the trained model on test data, visualized results, and confidence scores in the studio.

- Use the custom model in the BPA pipeline.


## Pre-requisites

- The accelerator is deployed and ready in the resource group.

- You have an Azure subscription and permission to create a Document Intelligence Resource.

- You have access to the sample invoices folder with the invoices to upload.

## Architecture

The architecture leverages Azure Document Intelligence for document analysis and data extraction. A custom project is set up with storage for training data, and the trained model is integrated into a Business Process Automation (BPA) pipeline. Azure Cognitive Search connects to Azure Blob Storage, creating an index and indexer for efficient data processing and search. This setup enables seamless document processing, automation, and advanced search capabilities.

## Architecture Diagram

