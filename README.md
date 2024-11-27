# Total Perspective Vortex

## Overview

**Total Perspective Vortex** is a project focused on creating a brain-computer interface (BCI) based on electroencephalographic (EEG) data using machine learning algorithms. The goal is to interpret a subject's brain activity to predict an action or thought, such as imagining or performing a hand or foot movement, within a defined time frame.

## Objectives

- **EEG Data Processing**: Parse and filter raw EEG signals to prepare them for analysis.
- **Dimensionality Reduction**: Implement an algorithm to reduce the complexity of the data while preserving critical information.
- **Pipeline Integration**: Utilize the `Pipeline` object from scikit-learn to streamline the processing and classification workflow.
- **Real-Time Classification**: Develop a system capable of classifying EEG data streams in real-time.

## Context

The dataset originates from a motor imagery experiment where participants were instructed to perform or imagine specific movements (e.g., hand or foot) corresponding to visual symbols displayed on a screen. The dataset contains EEG signals labeled with the task the participant was performing at the time.

## Key Instructions

1. **Data Processing**: 
   - Use Python and the [MNE library](https://mne.tools/stable/index.html) for EEG data processing.
   - Parse and filter raw data to eliminate noise and artifacts.

2. **Dimensionality Reduction**: 
   - Implement a custom dimensionality reduction algorithm.
   - Integrate the algorithm into scikit-learn to leverage its classification and validation tools.

3. **Machine Learning**: 
   - Train and validate machine learning models to classify EEG data.
   - Evaluate performance using scikit-learn's scoring mechanisms.

4. **Real-Time Stream**: 
   - Build a pipeline that processes and classifies data in real time.

## Tools and Libraries

- **Python**: The primary programming language for this project.
- **MNE**: Specialized library for EEG data processing.
- **scikit-learn**: Machine learning library for building pipelines, dimensionality reduction, and classification.

## Getting Started

1. Clone the repository:
   ```bash
   git clone git@github.com:TMdoubleGit/total_perspective_vortex.git
   cd total_perspective_vortex

2. Prepare the dataset:

- Place the EEG dataset in the appropriate directory (datasets/ by default).

3. Run the pipeline:

- python total_perspective_vortex.py

4. Deliverables:

- A functional brain-computer interface capable of processing EEG data streams.
- A custom dimensionality reduction algorithm integrated into scikit-learn.
- A detailed report documenting the implementation, experiments, and results.

5. References

- [MNE Documentation](https://mne.tools/stable/index.html)
- [scikit-learn Documentation](https://scikit-learn.org/stable/index.html)
- [EEG Motor movement/Imagery Dataset](https://physionet.org/content/eegmmidb/1.0.0/)