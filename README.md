# C-LCIKG
Life Cycle Inventory Knowledge Graph for Critical Chemicals  

This is the repository for our next publication:  

Tang, Z., Dreger, M., Jiang, P., Malek, K., & Tu, Q. (2024) Using Large Language Models and Neo4j to Construct a Knowledge Graph for Life Cycle Inventory of Critical Chemicals  

**Contents**  

This repository contains source code for extracting data from Life Cycle Assessment (LCA) studies. It is particularly designed to extract Life Cycle Inventory (LCI) data and LCA methodological choices, including functional units, system boundaries, impact assessment methods, and impact categories from papers. The extracted data is then used to build a knowledge graph in Neo4j.

* LangChain: Extract LCI inventory and LCA information using OpenAI's GPT-3.5 Turbo or GPT-4 APIs.

* Neo4j: Map tabulated data into Neo4j and query the knowledge graph.

* Text_embedding_classification: Extract table titles from PDFs, train a Random Forest classifier, and use it to determine whether a table is an inventory table.

**Features**

The main features of this pipeline:

* Extraction of table titles and their corresponding page numbers from PDFs.

* Classification of tables as LCI inventory or not.

* Extraction of LCI inventory data and LCA methodological choices from LCA studies.

* Construction of knowledge graphs in Neo4j based on the C-LCI ontology.

* Retrieval of information using Neo4j Cypher or the Q & A system


**Installation**
To install and run the app locally, follow these steps:

1. Clone this repository to your local machine.

2. Install the required dependencies using the provided requirements.txt file.

3. Run the code (using example datasets).
