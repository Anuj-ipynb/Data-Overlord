# Data-Overlord

## Overview

The Data Overlord Agent is a powerful tool designed to assist users in analyzing various file formats, including `.csv`, `.xlsx`, `.pdf`, `.txt`, `.docx`, and image files. Leveraging the capabilities of the `meta-llama/Llama-4-Maverick-17B-128E-Instruct-FP8` model from Together.ai, this agent can:

- Analyze tabular data and generate insightful visualizations.
- Extract text from different file types for further analysis.
- Provide intelligent question answering, including follow-up queries.

## Features

- **File Upload**: Users can upload multiple file formats for analysis.
- **Data Analysis**: Automatically summarizes and analyzes the content of uploaded files.
- **Natural Language Queries**: Users can ask questions about the document's content in natural language.
- **Visualization Generation**: Create visual representations of data upon request.

## How It Works

1. **Upload Your Document**: Users can upload their documents through the interface.
2. **Backend Processing**: The backend parses the uploaded file and generates a summarized prompt for the LLaMA-4 model.
3. **Query the Document**: Users can interact with the document using natural language queries.
4. **Generate Visualizations**: Users can request visualizations based on the analyzed data.

## Installation

To set up the Data Analyst Agent, ensure you have Python installed, then install the required packages using the following command:


pip install pandas numpy matplotlib seaborn plotly openpyxl python-docx pytesseract pdfplumber fitz pillow together


## Usage

1. **Open the Jupyter Notebook**: Launch the `agent.ipynb` file in Jupyter Notebook.
2. **Set Your API Key**: Replace `"your-api-key"` in the notebook with your actual Together.ai API key to enable model access.
3. **Upload Files**: Use the provided interface to upload your documents.
4. **Ask Questions**: After processing, you can ask questions related to the content of the uploaded files.
5. **Request Visualizations**: Generate visualizations based on the data analysis.

## Example Workflow

1. Upload a `.csv` file containing sales data.
2. Ask questions like "What is the total sales for Q1?" or "Show me a trend of sales over the last year."
3. Request visualizations such as bar charts or line graphs to better understand the data.

#
