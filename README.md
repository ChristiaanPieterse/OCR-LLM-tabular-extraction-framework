# OCR-LLM Tabular Extraction Framework - Custom Dataset

## Overview
This repository contains a custom test dataset designed to evaluate the performance of an OCR-LLM framework for table extraction. The dataset comprises tables extracted from various text-rich sources, including academic papers and business documents, ensuring diversity in content and structure. It serves as a benchmark for assessing the accuracy and robustness of intelligent document processing systems.

## Dataset Description
The dataset is carefully curated to include a variety of table formats, covering differences in:
- **Layouts & Structures**: From simple two-row or two-column tables to complex structures featuring multiple sub-columns and open cells.
- **Content Complexity**: Includes numerical data, text, binary indicators (e.g., check marks for correctness), and matrix-based operations.
- **Orientation Variability**: Some tables appear in rotated formats (e.g., 90-degree alignment).

An illustrative example of the dataset is provided in *Tables with Associated Q&As.pdf*, which showcases the tables along with their associated questions and ground-truth answers.

## Dataset Composition
- **Number of Tables**: 31
- **Number of Questions**: 62 (2 per table)
Each table is paired with two specific questions, ensuring that answers can be directly extracted from the table. The manually annotated ground-truth answers enable rigorous evaluation of extraction performance.

## Usage
This dataset can be used for:
- **Benchmarking OCR-LLM systems** for table extraction
- **Evaluating table understanding models** in document processing
- **Developing intelligent document processing solutions** for diverse tabular data

## Files in this Repository
- **`Test data/Tables`**: Contains all tabular data in structured formats
- - **`Test data/Questions`**: Contains all tabular questions in structured _.txt_ formats
- **`Tables with Associated Q&As.pdf`**: Displays all tables along with their associated questions and ground-truth answers
- **`README.md`**: This document, providing dataset details
