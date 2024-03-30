# SMILES to Sentences: Capstone Code

Welcome to the SMILES to Sentences Capstone Project! :)
This repository contains all the necessary code and documentation to understand and execute the code for the project. The focus of this project is generating multitragted HIV drugs using a Biagram-transformer model (a method originally develop for natutal lenguage). The project is divided into several sections, including data exploration, NLP approaches, autoencoder model development, and optimization techniques. The codebase is structured to provide a comprehensive understanding of the project's workflow and methodologies.

## How to Run the Code

### Setting Up the Environment

First, you'll need to set up a virtual environment to manage the project's dependencies separately from your global Python setup. Follow these steps:

1. **Create a Virtual Environment:**

   ```bash
   python -m venv .venv
   ```

2. **Activate the Virtual Environment:**

   - **For Windows:**
     ```cmd
     .venv\Scripts\activate
     ```
   - **For macOS/Linux:**
     ```bash
     source .venv/bin/activate
     ```

3. **Install Requirements:**

   Ensure you're in the project's root directory and run:
   ```bash
   pip install -r requirements.txt
   ```

## Folder Organization

The project structure is organized as follows to ensure easy navigation and comprehension:

- **Data:** Contains datasets and related files used and generated throughout the project.
  - **Images:** Storage for images of the parent molecules.
     - **nrtis:** NRTI (Nucleoside Reverse Transcriptase Inhibitors) bioactive molecule data, gathered from ChemLB.
    - **protease:** Protease inhibitors data bioactive molecule data, gathered from ChemLB.
  - It has the data in all of the cleaning stages.
- **Exploratory Analysis:** Jupyter notebooks used for initial data exploration and analysis.
- **structure draft fro NLP code** Draft of the code for the NLP approach. Use as backup if the main code is lost or modified.
- **NLP Approach:** Notebooks and files related to the NLP-based methods used in the project. This is the focus of the project. The analysis and trained models are stored here.
- **Auto Encoder:** Files related to the development and testing of autoencoder models.
- **Tokenization:** Notebooks focusing on the tokenization processes, not used in the code but from part of the exploration.
- **.gitignore:** Specifies intentionally untracked files to ignore.
- **CS64_optimization_final.ipynb:** Notebook detailing the optimization approaches.Part of the optimization class, information about this is in Appendix B of the write up.
- **Model_test_chem.ipynb:** Notebook for testing models with chemical data. *In progress.*
- **requirements.txt:** Lists all dependencies required to run the project.


## Getting Started

To dive into the project:

1. Begin with the **Exploratory Analysis** notebooks to understand the datasets and initial findings. It has the models that were tested (can be analyzed with the **Data** to understand the initial cleaning stages).
- The **Auto Encoder** file forms part of the model analysis, as wwwell as the **Tokenization** files.
2. Explore the **NLP Approach** and sections for insights into the methodology and model development.
- The **Results** has the images of teh gnerated molecules.
- The **Loss** has images of the loss functions accross the epochs.


Thanks for stopping by! If you have any questions or need further assistance, feel free to reach out or read the main write up of the project :)