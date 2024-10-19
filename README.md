##Overview
This project involves extracting textual data from articles provided in URLs, performing text analysis, and computing various metrics. The objective is to read the URLs from an input file, extract relevant text, analyze it, and output the results in a structured format.

##Instructions
1. Explaining How You Approached the Solution
I approached the solution by first reading the input URLs from the provided file (Input.xlsx). Using web scraping techniques with requests and BeautifulSoup, I extracted the article titles and text. The extracted text was then saved in individual text files named after their URL_ID. For the data analysis, I performed comprehensive text analysis to compute various metrics such as positive and negative scores, polarity and subjectivity scores, and readability indices. I used the Natural Language Toolkit (nltk) for text tokenization and stop word removal. Finally, the results were compiled into a structured format as specified in Output Data Structure.xlsx.

2. How to Run the .ipynb File to Generate Output
Prepare the Environment:

Ensure Input.xlsx and the stop words files are in the working directory.
If using a cloud-based environment like Google Colab, mount the necessary storage (e.g., Google Drive).
Execute the Notebook:

Open Data_Extraction_and_Text_Analysis.ipynb in a Jupyter Notebook environment or Google Colab.
Run all the cells sequentially.
Check the Output:

The notebook will process the input URLs, extract text, perform text analysis, and generate an output file (Output.xlsx) containing the computed metrics.
3. Include All Dependencies Required
The following Python libraries are required to run the notebook:

pandas
requests
beautifulsoup4
numpy
nltk
openpyxl
To install the dependencies, run:
pip install pandas requests beautifulsoup4 numpy nltk openpyxl
