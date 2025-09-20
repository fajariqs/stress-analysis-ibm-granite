# Student Stress Level Classification & Summarization using IBM Granite LLM

This project demonstrates how to leverage **IBM Granite LLM (`ibm-granite/granite-3.3-8b-instruct`)** together with **LangChain** and **Replicate** to perform:

- Classification of student stress levels (Low, Normal, High)  
- Summarization of key insights from the dataset  

The dataset used is **`StressLevelDataset.csv`**, which contains student demographic data, lifestyle habits, and self-reported stress levels.

---

# Project Files
- `Fajar_LLM_Ai.ipynb` → Main Jupyter Notebook with full implementation  
- `StressLevelDataset.csv` → Dataset of student stress levels  
- `README.md` → Project documentation (this file)  

---

# Installation & Setup

1. Clone this repository or download the files.
2. Install dependencies:
   ```bash
   pip install langchain langchain-experimental replicate pandas
   
3. Setup your Replicate API Token (replace with your key)
   export REPLICATE_API_TOKEN=your_api_key_here

---

How to Run

1. Open the notebook:
   jupyter notebook Fajar_LLM_Ai.ipynb
2. Load the dataset with Pandas.
3. Initialize the Granite LLM via Replicate inside LangChain.
4. Use create_pandas_dataframe_agent to enable natural language interaction with the dataset.

`## Author`
- Name: Fajar  
- Project: Stress Analysis with IBM Granite LLM  
- GitHub: [fajariqs](https://github.com/fajariqs)




