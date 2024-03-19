# Certificate_Generator_using_Python

This Python script is designed to automate the generation of certificates for members listed in an Excel workbook. The script reads data from the workbook, including member names and unique identifiers, and dynamically inserts this information into a pre-existing certificate template. Both image (PNG) and PDF versions of the certificates are generated and saved in designated directories.

Key Features:
Utilizes libraries such as openpyxl for Excel file handling, Pillow for image processing, and img2pdf for image-to-PDF conversion.
Provides a user-friendly interface for selecting the input Excel workbook file.
Dynamically inserts member names into a certificate template and generates both image and PDF versions.
Organizes generated certificates into separate directories for images and PDFs.

Instructions:
Install necessary Python packages by running the provided install function or manually install the required packages.
Run the script and select the Excel workbook containing member information.
Follow the on-screen prompts to generate certificates.
Find the generated certificates in the specified directories (All_Certificates/Images and All_Certificates/PDFs).

Requirements:
Python 3.x
Required Python packages (img2pdf, openpyxl, Pillow)

Note:
Ensure that a certificate template named certificates.png is available in the working directory.
Adjust font styles and sizes as per your preference by replacing the provided font file (Lora-Bold.ttf) or specifying your own.
