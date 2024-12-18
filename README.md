IGGA Text Analysis Project
Project Overview
The IGGA Text Analysis Project is a comprehensive analysis framework designed to process and analyze textual data across diverse industries. Using Natural Language Processing (NLP) and advanced visualization techniques, this project aims to extract meaningful insights from industry-specific text documents.

Key features include:

Frequency Analysis to identify the most prominent keywords.
TF-IDF and Cosine Similarity for cross-industry textual comparison.
Sector-Specific Keyword Matching to assess domain-specific terminologies.
Sankey Diagrams for visualizing word relationships and keyword distributions.
Objectives
This project aims to:

Analyze industry-specific textual data to extract dominant keywords and trends.
Compare textual content across industries using cosine similarity and TF-IDF.
Visualize keyword frequencies and relationships using bar charts and Sankey diagrams.
Provide a replicable NLP pipeline for industry-focused text analysis.
Project Workflow
The project consists of the following steps:

Data Preparation:

Word documents (.docx) are processed into plain text files (.txt) using docx2txt.
Text Processing:

Text cleaning: Removal of symbols, numbers, and stopwords.
Tokenization: Splitting text into meaningful words.
Lemmatization: Converting words to their base forms.
Frequency Analysis:

Identify and visualize the top 20 keywords for each industry.
Sector Keyword Matching:

Match keywords against predefined industry-specific keyword lists to highlight key terminologies.
Cosine Similarity and Heatmap:

Use TF-IDF Vectorization to compute cosine similarity between industry texts.
Visualize similarity scores as a heatmap.
Sankey Diagram Visualization:

Display relationships between industries, top words, and domain-specific keywords.
Key Features
Natural Language Processing: Uses nltk for tokenization, stopword removal, and lemmatization.
Visualization: Generates:
Frequency bar charts (top keywords per industry)
Cosine similarity heatmaps
Interactive Sankey diagrams using plotly
Custom Keyword Matching: Industry-specific keyword lists allow for tailored domain analysis.
TF-IDF Cosine Similarity: Quantitative comparison of text documents across industries.
Technologies Used
Languages: Python
Libraries:
nltk (text processing)
re (regular expressions)
pandas and numpy (data manipulation)
matplotlib and seaborn (visualization)
plotly.graph_objects (Sankey diagrams)
sklearn (TF-IDF and cosine similarity)
Project Structure
The repository is organized as follows:

IGGA/
│
├── Advertising_Marketing.docx       # Example Word document
├── Advertising_Marketing.txt        # Processed text file
├── combined_frequency_charts.png    # Generated keyword frequency visualization
├── IGGA Text Analysis.ipynb         # Main project code (Jupyter Notebook)
├── ...                              # Additional industry files
├── similarity_heatmap.png           # Cosine similarity heatmap output
└── keyword_frequencies.png          # Industry keyword frequency charts



How to Run the Project
Clone this repository:

bash
Copy code
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
Outputs
Bar Charts: Top 20 keywords for each industry.
Cosine Similarity Heatmap: Quantifies textual similarity between industries.
Sankey Diagrams: Visualizes relationships between industries, top keywords, and implementation keywords.
Use Cases
This project can be applied to:

Industry-Specific Text Analysis: Identifying trends and key terminologies across sectors.
Content Comparison: Evaluating the textual similarity between industry documents.
Visualizing Insights: Producing intuitive charts and diagrams for data-driven decision-making.
NLP Pipelines: Replicating or extending the methodology for other text analysis projects.
Contributors
Saleh Afroogh (Lead Developer and Researcher)
For questions, feedback, or collaborations, contact me at [your-email@example.com].
License
This project is licensed under the MIT License. Feel free to use, modify, and distribute the code.

