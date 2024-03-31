# Shopify Bulk Inventory Update Tool (SKU Based)

This repository contains two versions of the Shopify Bulk Inventory Update Tool: one designed for use in Google Colab and another for running on your local machine. This tool facilitates the bulk updating of Shopify inventory based on SKU information, a feature not directly supported by Shopify's interface.

## Overview

The Shopify Bulk Inventory Update Tool enables users to efficiently update inventory quantities based on SKU information from a new inventory file. The tool supports operations that Shopify's interface lacks, providing a convenient solution for managing inventory updates.

- **Google Colab Version**: Suitable for users looking for a cloud-based solution with interactive file upload and download capabilities.
- **Local Machine Version with File Dialogs**: Ideal for users running the tool on their local environment, offering file dialogs for easy file selection and saving.

## Getting Started

### Prerequisites

- For the Google Colab version: A Google account and internet access.
- For the Local Machine version: Python, pandas, and tkinter installed. JupyterLab or Jupyter Notebook for notebook execution.

### Using the Tool

#### Google Colab Version

1. Navigate to `Shopify_Inventory_Update_using_SKU_Colab.ipynb` in this repository.
2. Open the notebook in Google Colab.
3. Follow the in-notebook instructions to upload your Shopify Inventory Export File and New Inventory File, then process the inventory update.
4. Download the updated inventory file for re-importation into Shopify.

#### Local Machine Version with File Dialogs

1. Ensure your local environment is set up with Python, pandas, and tkinter.
2. Clone or download this repository to your local machine.
3. Navigate to `Shopify_Inventory_Update_using_SKU_Local_Machine.ipynb` and open it in JupyterLab or Jupyter Notebook.
4. Follow the notebook's instructions, using the file dialogs to select your inventory files and to specify the save location for the updated inventory file.

## Features

- **SKU-Based Inventory Updates**: Enables inventory updates based on SKU information, addressing a limitation of Shopify's interface.
- **Cloud-Based and Local Solutions**: Offers flexibility in how and where the tool can be used, accommodating different user preferences.
- **Interactive File Handling**: Utilizes file upload/download dialogs in Google Colab and file dialogs in the local version for an enhanced user experience.

## Contributing

Contributions to the Shopify Bulk Inventory Update Tool are welcome. Feel free to fork the repository, make your changes, and submit a pull request with your improvements.

## License

This project is open source and available under the [MIT License](LICENSE).

---

I hope you find the Shopify Bulk Inventory Update Tool useful for your e-commerce management needs. For questions, suggestions, or contributions, please feel free to open an issue or submit a pull request.
