# PDF Splitter for "Arrêt Jurisprudence"
## This project provides a Python script that splits a large PDF file containing multiple legal rulings ("Arrêts Jurisprudence") into individual PDF files. 

### Each output file corresponds to one ruling, and the file names are based on the ruling number found in the document.

## Features
Automatic Detection: Detects the start of each new "Arrêt" using the pattern Arrêt n°.
Page Number Removal: Automatically removes any page numbers in the format Page X sur Y.
Individual Output Files: Splits and saves each ruling as a separate PDF file with the naming format arrest_number_X.pdf, where X is the ruling number.
Directory Management: Saves the output files to an output_pdf folder, which is created if it doesn't exist.

**Prerequisites**

Before running the script, you need to install the following dependencies:

- Python 3.x
- PyPDF2 (for PDF handling)
 
To install the required Python packages, run the following command:

`pip install PyPDF2`

**How to Use**

Clone the Repository:

`git clone https://github.com/your-username/arret-jurisprudence-pdf-splitter.git`

`cd arret-jurisprudence-pdf-splitter`

- Place Your PDF File

- Place your large PDF file (e.g., LivreRecueil_2009_all.pdf) in the directory.

- Run the Script

**Replace the pdf_path with the path to your PDF file and run the script:**