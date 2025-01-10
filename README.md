# EikonRefinitivTools

This repository contains a Jupyter Notebook and associated tools for retrieving financial data from **EIKON Refinitiv** (formerly Reuters) through their API. The notebook provides a comprehensive guide on setting up the necessary libraries, connecting to the API, and querying financial data. Please refer to the notebook for further details.

## Features

- **Library Setup**: Instructions for importing and setting up the required Python libraries, including `pandas`, `eikon`, and `refinitiv-data`.
- **API Connection**: Guidance on establishing a connection to the EIKON Refinitiv API.
- **Data Retrieval**: Examples of retrieving various types of financial data, including ESG variables and emission data.
- **Robust Data Handling**: Techniques for handling the limited data retrieval per request and implementing robust loops for downloading data in multiple steps.

## Notebook Structure

1. **Setting up libraries, API connection, and working paths**:
   - Importing necessary libraries.
   - Printing package versions for verification.

2. **Test Example provided by LSEG guide on EIKON API access**:
   - Example usage of the EIKON API as per the LSEG guide.

3. **Retrieving a list of companies for which desired data are available**:
   - Querying and retrieving a list of companies with available data.

4. **Querying Data through EIKON API**:
   - Importing the list of companies for data retrieval.
   - Querying and downloading the desired financial data.

## Usage

To use the notebook, ensure you have the required Python packages installed (**eikon** and **pandas**) and follow the steps outlined in the notebook. Adjust the API requests according to your specific data needs.

Last EIKON package version used: **1.1.18**.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or additional features to add.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
