# **Document Understanding Automation with UiPath**

## **Overview**
This project demonstrates how to use UiPath’s **Document Understanding** capabilities to classify and extract data from various document types, including **1014x forms**, **invoices**, and **W-4 forms** in both **PDF** and **.ng** formats. The extracted information is saved into a **new Excel file** for further processing.

## **Technologies Used**
- **UiPath Studio**
- **UiPath Document Understanding**
  - **Taxonomy Manager** for defining document types.
  - **Classifier** to distinguish between different documents.
  - **Form Extractor** for structured document data extraction.
  - **Machine Learning Extractor** for extracting data using AI models.
- **Excel Automation** for saving extracted data.

## **Features**
- Automated classification of documents (Invoices, 1014x, W-4).
- Extraction of key data using **Form Extractor** and **Machine Learning Extractor**.
- Saving extracted data into an organized **Excel** file.

## **Project Workflow**
1. **Document Classification**:
   - Documents are classified based on a predefined taxonomy that includes different types such as 1014x, invoices, and W-4 forms.
2. **Data Extraction**:
   - The **Form Extractor** is used for structured documents (e.g., invoices), while the **Machine Learning Extractor** handles unstructured documents.
3. **Save to Excel**:
   - Extracted data is saved in a new **Excel file** for easy review and further analysis.

## **How to Use**
1. Clone the repository:
   ```bash
   git clone https://github.com/YourGitHubUsername/YourRepoName.git
