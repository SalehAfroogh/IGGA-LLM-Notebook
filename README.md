# <strong>Generative AI and LLMs in Industry: A text- mining Analysis and Critical Evaluation of Guidelines and Policy Statements Across Fourteen Industrial Sectors</strong>
 
The <strong>IGGA Text Analysis Project</strong> is a comprehensive analysis framework designed to process and analyze textual data across diverse industries. Using <strong>Natural Language Processing (NLP)</strong> and advanced visualization techniques, this project extracts meaningful insights from industry-specific text documents.  

Key features include:  
- <strong>Frequency Analysis</strong> to identify the most prominent keywords.  
- <strong>TF-IDF and Cosine Similarity</strong> for cross-industry textual comparison.  
- <strong>Sector-Specific Keyword Matching</strong> to assess domain-specific terminologies.  
- <strong>Sankey Diagrams</strong> for visualizing word relationships and keyword distributions.  

---

<strong>Objectives</strong>  
This project aims to:  
1. Analyze industry-specific textual data to extract dominant keywords and trends.  
2. Compare textual content across industries using <strong>cosine similarity</strong> and <strong>TF-IDF</strong>.  
3. Visualize keyword frequencies and relationships using bar charts and Sankey diagrams.  
4. Provide a replicable NLP pipeline for industry-focused text analysis.  

---

<strong>Project Workflow</strong>  
The project consists of the following steps:

1. <strong>Data Preparation</strong>  
   - Word documents (`.docx`) are processed into plain text files (`.txt`) using `docx2txt`.

2. <strong>Text Processing</strong>  
   - Text cleaning: Removal of symbols, numbers, and stopwords.  
   - Tokenization: Splitting text into meaningful words.  
   - Lemmatization: Converting words to their base forms.

3. <strong>Frequency Analysis</strong>  
   - Identify and visualize the <strong>top 20 keywords</strong> for each industry.
  
     ![image](https://github.com/user-attachments/assets/974d0cdb-f7e9-4abd-853b-14b888dbbdd5)


4. <strong>Sector Keyword Matching</strong>  
   - Match keywords against predefined <strong>industry-specific keyword lists</strong> to highlight key terminologies.

5. <strong>Cosine Similarity and Heatmap</strong>  
   - Use <strong>TF-IDF Vectorization</strong> to compute cosine similarity between industry texts.  
   - Visualize similarity scores as a heatmap.
  
     ![image](https://github.com/user-attachments/assets/1ffe80df-280d-4bf9-89e1-ca3dbccbb018)


6. <strong>Sankey Diagram Visualization</strong>  
   - Display relationships between industries, top words, and domain-specific keywords.
  
     ![image](https://github.com/user-attachments/assets/a6c4e1d1-6881-4e39-8fcf-b142ad39aff6)

     ![image](https://github.com/user-attachments/assets/fa930bcc-2eb3-406c-8e91-36d18bb892ec)

     ![image](https://github.com/user-attachments/assets/a0f0a522-1453-49b8-b6c3-4a7576bc3842)



     


---

<strong>Key Features</strong>  
- <strong>Natural Language Processing</strong>: Uses `nltk` for tokenization, stopword removal, and lemmatization.  
- <strong>Visualization</strong>: Generates:  
   - Frequency bar charts (top keywords per industry)  
   - Cosine similarity heatmaps  
   - Interactive Sankey diagrams using `plotly`  
- <strong>Custom Keyword Matching</strong>: Industry-specific keyword lists allow for tailored domain analysis.  
- <strong>TF-IDF Cosine Similarity</strong>: Quantitative comparison of text documents across industries.

---

<strong>Technologies Used</strong>  
- <strong>Languages</strong>: Python  
- <strong>Libraries</strong>:  
   - `nltk` (text processing)  
   - `re` (regular expressions)  
   - `pandas` and `numpy` (data manipulation)  
   - `matplotlib` and `seaborn` (visualization)  
   - `plotly.graph_objects` (Sankey diagrams)  
   - `sklearn` (TF-IDF and cosine similarity)  

---

<strong>Project Structure</strong>  
The repository is organized as follows:

---

<img width="964" alt="Screenshot 2024-12-18 at 3 05 08 PM" src="https://github.com/user-attachments/assets/185636fb-1fab-4a97-aec9-358bee88ec01" />

<strong>How to Run the Project</strong>  
1. **Clone this repository**:  
   ```bash
   git clone https://github.com/SalehAfroogh/IGGA-LLM-Notebook.git
   cd IGGA-LLM-Notebook
Install the required libraries:

bash
Copy code
pip install nltk pandas matplotlib seaborn plotly scikit-learn docx2txt
Run the Jupyter Notebook:

Open IGGA Text Analysis.ipynb in Jupyter Notebook or VS Code.
Execute all cells to generate visualizations and analysis results.
Optional: If the NLTK stopwords list isn't available, download it in Python:

python
Copy code
import nltk
nltk.download('stopwords')
nltk.download('punkt')
nltk.download('wordnet')
<strong>Outputs</strong>

Bar Charts: Top 20 keywords for each industry.
Cosine Similarity Heatmap: Quantifies textual similarity between industries.
Sankey Diagrams: Visualizes relationships between industries, top keywords, and implementation keywords.
<strong>Use Cases</strong>
This project can be applied to:

Industry-Specific Text Analysis: Identifying trends and key terminologies across sectors.
Content Comparison: Evaluating the textual similarity between industry documents.
Visualizing Insights: Producing intuitive charts and diagrams for data-driven decision-making.
NLP Pipelines: Replicating or extending the methodology for other text analysis projects.

<strong>Contributors</strong>

Kevin Chen and
Saleh Afroogh (Lead Researcher)

<strong>Questions</strong> 

For questions, feedback, or collaborations, contact me at saleh.afroogh@utexas.edu.
<strong>License</strong>
This project is licensed under the MIT License. Feel free to use, modify, and distribute the code.


