# Advanced Plagiarism Detection System

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](CONTRIBUTING.md)

It's designed for ease of use and provides detailed analysis without sending your data to a server.

## Key Features

- Operates entirely in your browser. Your documents never leave your computer.
- dentifies matching paragraphs, sentences, and phrases.
- Simple drag-and-drop or paste-text input.
- Highlights similar sections directly in the document displays.
- Easily generate reports of the analysis.

### Usage

**Input Documents:**

*  Drag and drop `.txt`, `.doc`, `.docx`, or `.pdf` files into the designated areas.
*  Alternatively, paste text directly into the provided text areas.
*  Click the "Compare Documents" button.
*  The analysis results, including the overall similarity percentage and highlighted text comparisons, will be displayed.
*  Generate a report of the plagiarism analysis for your records.

## Understanding the Analysis

The system breaks down the comparison into several key metrics:

*  A percentage indicating the total similarity between the two documents based on shared vocabulary.
*  The number of paragraphs with a high degree of similarity.
*  The number of sentences that are highly similar between the documents.
*  The count of identical or near-identical short phrases.

## Acknowledgements

*   Uses the `diff-match-patch` library for efficient text comparisons.

