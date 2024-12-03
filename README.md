# AnyFileConverter

**AnyFileConverter** is a versatile tool for converting files across multiple formats, such as PDF to DOCX, DOCX to PDF, JPEG to JPG, and more. It also ensures privacy by automatically removing metadata from all processed files.  

---

## Features

- **PDF to DOCX Conversion**: Convert PDF files into editable DOCX documents.
- **DOCX to PDF Conversion**: Transform DOCX files into professional-grade PDF documents.
- **Extract Images from PDFs**: Save all images from a PDF file to a specified folder.
- **JPEG to JPG Conversion**: Quickly convert JPEG images to JPG format.
- **Metadata Removal**: Automatically strips metadata from all processed files to enhance privacy.

---

## Prerequisites

Ensure you have Python 3.7 or higher installed. Use the following commands to verify:
```bash
python3 --version
pip --version
```

---

## Installation

Follow these steps to configure and run **AnyFileConverter**:

### Step 1: Clone the Repository
```bash
git clone https://github.com/itsdk109/AnyFileConverter.git
cd AnyFileConverter
```

### Step 2: Set Up a Virtual Environment

1. **Create the Virtual Environment**: 
   ```bash
   python3 -m venv venv
   ```
2. **Activate the Virtual Environment**:
   - On **Linux/macOS**:
     ```bash
     source venv/bin/activate
     ```
   - On **Windows**:
     ```cmd
     venv\Scripts\activate
     ```

3. **Install Dependencies**:
   Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

### Run the Tool
Execute the following command to start the tool:
```bash
python anyfileconverter.py
```

### Interactive Menu
Once the tool is running, follow the on-screen prompts to select your desired operation:
1. **Convert PDF to DOCX**
2. **Convert DOCX to PDF**
3. **Extract Images from a PDF**
4. **Convert JPEG to JPG**
5. **Exit the Tool**

### Example Workflow
- **PDF to DOCX**:
  - Input the path to your PDF file.
  - Specify the output path for the DOCX file.
  - The tool converts the file and removes metadata automatically.
  
- **Extract Images from PDF**:
  - Provide the PDF file and an output folder.
  - The tool saves all images from the PDF into the specified folder.

---

## Configuration Notes

1. **Metadata Removal**:
   - All converted files are processed to remove sensitive metadata.
   
2. **File Paths**:
   - Use absolute paths for better reliability.
   - Ensure the input file exists and the output folder is writable.

---

## Troubleshooting

1. **Error: `externally-managed-environment`**:
   - This occurs if you try to install dependencies globally in a managed Python environment.
   - Use a virtual environment as described above.

2. **Module Not Found**:
   - Ensure all dependencies are installed:
     ```bash
     pip install -r requirements.txt
     ```

3. **Permission Denied**:
   - Check file and folder permissions for both input and output paths.

---


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## YouTube Channel
 - [Channel Link:](https://www.youtube.com/@learntechwithdeepak)

## Author

Developed by **Learn Tech With Deepak**.  
For inquiries, contact [Email:](mailto:learntechwithdeepak@gmail.com).

---
