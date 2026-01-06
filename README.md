# Hybrid Structural and Textual Similarity Analysis for Flowchart Plagiarism Detection

## Overview
This project focuses on detecting and analyzing similarities between flowcharts by combining **structural** and **textual** analysis techniques. The system is designed to compare flowcharts in a meaningful and automated way, making it useful for applications such as academic evaluation, plagiarism detection, and process analysis.

## Key Features
- Structural similarity analysis of flowcharts
- Textual similarity analysis using OCR
- Graph-based modeling and comparison
- Research-oriented design and implementation

## Methodology
- Trained a **custom YOLOv8 model** to detect flowchart components such as shapes and arrows, enabling accurate extraction of the flowchart structure.
- Integrated **Optical Character Recognition (OCR)** to extract textual content from flowcharts and map it to the corresponding shapes and arrows.
- Modeled flowcharts using **graph-based data structures**, where nodes represent flowchart elements and edges represent relationships and flow.
- Applied **graph isomorphism techniques** to compare flowcharts based on node similarity, edge relationships, spatial layout, and textual content.

## Research Contribution
- Authored a research paper detailing the system’s design, implementation, and evaluation, highlighting its effectiveness in flowchart similarity detection.

## Technologies Used
- YOLOv8
- OCR
- Graph-based algorithms
- Python (for model training and analysis)

## Applications
- Academic flowchart comparison
- Automated grading systems
- Plagiarism detection
- Process and workflow analysis
