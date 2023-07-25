# LegalText - Automated Written Statement Generator

LegalText is a groundbreaking automated written statement generator that empowers insurance companies and legal professionals to efficiently counter third-party claims. This project utilizes cutting-edge Natural Language Processing (NLP) and Optical Character Recognition (OCR) technologies to streamline the claims resolution process and enhance legal defenses.

## Features

- **Graphical User Interface (GUI)**: LegalText comes with an intuitive GUI that facilitates easy uploading of petition files and investigation reports, ensuring a seamless user experience. The GUI allows users to interact with the application and obtain the generated written statements effortlessly.

- **OCR Technology**: Advanced OCR technology enables LegalText to accurately extract data from scanned image-based PDFs, providing a reliable data source for analysis. This feature saves time and effort by automating the extraction process.

- **PyPDF2 Integration**: The project seamlessly handles various document types, utilizing the PyPDF2 library for text extraction from standard PDFs. This allows the application to process a wide range of file formats commonly encountered in legal proceedings.

- **Data Preprocessing with NLTK**: LegalText employs the Natural Language Toolkit (NLTK) for comprehensive data preprocessing, laying the groundwork for effective data analysis and generation. This ensures that the generated written statements are clear, coherent, and credible.

- **Cutting-edge NLP and GPT API**: Leveraging the power of NLP and the GPT model, LegalText generates well-crafted and persuasive written statements to effectively counter third-party claims. The application utilizes the OpenAI GPT-3.5 engine for high-quality language generation.


## Architecture
![Architecture](https://github.com/rokithkumar/LegalText/assets/75007002/5e74e576-13d8-47a4-ab30-29545be4cf66)



## How It Works

LegalText's workflow involves multiple steps to achieve efficient and accurate results:

1. **Data Upload**: Users can upload petition files and investigation reports via the Graphical User Interface (GUI).

2. **OCR Processing**: The application processes uploaded files using OCR technology, extracting text from scanned image-based PDFs and image files. This ensures that all relevant information is accessible for further analysis.

3. **Data Cleaning**: The extracted text undergoes data preprocessing using the NLTK library. This step removes unnecessary line breaks, extra spaces, and page breaks, ensuring the text is cleaned and ready for analysis.

4. **Data Analysis and Generation**: The processed text is then sent to the GPT-3.5 engine for analysis and generation of written statements. The generated statements are strategically crafted to counter third-party claims effectively.

5. **PDF Output**: The application saves the generated written statements as a PDF file. Users can access the PDF document, which contains the persuasive written statements for legal use.

## Usage

1. Clone the repository to your local machine.
2. Install the required dependencies using the provided `requirements.txt` file.
3. Run the Flask app locally by executing `python App.py` in your terminal.
4. Access the Graphical User Interface through your preferred web browser (e.g., http://localhost:5000/).
5. Upload the relevant petition files and investigation reports to the application.
6. LegalText will process the uploaded data, generate the written statements, and save them as a PDF file.
7. Obtain the PDF document containing the generated written statements for legal use.

## Dependencies

LegalText utilizes the following libraries and frameworks:

- Flask
- docx
- fitz (PyMuPDF)
- pytesseract
- PIL (Python Imaging Library)
- re
- os
- time
- openai
- fpdf

## Disclaimer

LegalText is intended for research and educational purposes only. It is not a substitute for legal advice and should not be used as such. Users are responsible for verifying the accuracy and validity of the generated written statements before using them in legal proceedings.

## License

This project is licensed under the MIT License.

---

