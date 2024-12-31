# Entity Extraction with Flask and spaCy using NER

This project is a simple Flask web application that allows users to upload a text file, and it will display the named entities extracted from the text using the `spaCy` library.

## Features

- **Text File Upload**: Upload a `.txt` file containing text.
- **Named Entity Recognition (NER)**: Extracts named entities such as Persons, Organizations, and Locations from the provided text using spaCy.
- **Visualized Entities**: Displays the named entities in an interactive HTML format using `displacy` (spaCy's visualization tool).

### `app.py`

The `app.py` file is the main Python script that runs the Flask application. It contains the logic for:

- Setting up the Flask routes.
- Handling the text file upload.
- Extracting named entities using spaCy.
- Rendering the extracted named entities as an interactive HTML visualization using spaCy's `displacy` tool.

## How to Use

Start the Flask Application: 

- Run the app.py file.
- Upload a Text File:
- Open your browser and go to http://127.0.0.1:5000/.
- Click on the "Choose File" button, select a .txt file containing text, and upload it.
- After the file is uploaded, the extracted named entities will be displayed on the page.
- View Extracted Entities: The app will display the named entities recognized in the text, such as people, organizations, and locations. These will be visualized using spaCy's displacy tool.
