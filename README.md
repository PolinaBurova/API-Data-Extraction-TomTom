# TomTom Data Extraction Project


## Objective
The objective of this project is to extract data from the TomTom Maps API and analyze the information related to cafes in the Baixa Pombalina (Lisbon) area.

## Description
This project involves:
- Sending HTTP requests to the TomTom Maps API.
- Parsing the JSON responses to retrieve data.
- Extracting and displaying information about cafes.
- Identifying discrepancies and potential issues in the data.

## Code Overview
The code consists of the following steps:
1. **API Key Verification**:
   - Send a simple request to verify if the API key is working.

2. **Data Extraction**:
   - Use the TomTom Maps API to search for cafes in the Baixa Pombalina area.
   - Parse the JSON response to extract information about cafes.

3. **Results Display**:
   - Print the total number of cafes found.
   - Display detailed information about each cafe.

## Requirements
The project requires the following Python packages:
- `requests`

Create a `requirements.txt` file with the necessary dependencies.

## How to Run the Notebook
1. Clone the repository.
2. Install the dependencies using:
   ```bash
   pip install -r requirements.txt
