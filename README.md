# PDF Visionary 🤖

**PDF Visionary** is a powerful tool that transforms your PDFs into interactive insights. Upload your PDF, and explore the content by asking questions about the text within it. Our tool allows you to interact with the document and get insights directly from the content.

## Features

- **Upload PDF:** Drag & drop or select your PDF file.
- **Interactive Exploration:** Enter a prompt to interact with the document.
- **Text-to-Speech:** Listen to the response using the integrated audio controls.
- **Copy Text:** Easily copy the generated response to your clipboard.

## How It Works

1. **Upload Your PDF:** Select or drag and drop your PDF file to upload it.
2. **Enter a Prompt:** Type in a question or prompt related to the content of your PDF.
3. **Process and Get Insights:** Our tool processes the PDF and returns interactive insights.
4. **Interact with the Response:** Use text-to-speech to listen to the response or copy it to your clipboard.

## Installation

To get started with the project, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/shahram8708/pdf-visionary.git
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd pdf-visionary
   ```

3. **Create a Virtual Environment:**

   ```bash
   python -m venv venv
   ```

4. **Activate the Virtual Environment:**

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS/Linux:

     ```bash
     source venv/bin/activate
     ```

5. **Install the Required Packages:**

   ```bash
   pip install -r requirements.txt
   ```

6. **Set Up API Key:**

   - Ensure you have your Google Gemini API key available.
   - Set the environment variable `API_KEY` with your API key:

     ```bash
     export API_KEY='your_google_gemini_api_key'
     ```

7. **Run the Application:**

   ```bash
   python app.py
   ```

   The application will be available at `http://127.0.0.1:5000`.

## Usage

1. **Open the Web Application:**
   - Visit `http://127.0.0.1:5000` in your browser.

2. **Upload Your PDF:**
   - Drag & drop your PDF file or click to select it.

3. **Enter Your Prompt:**
   - Type in a question or prompt about the PDF content.

4. **Submit the Form:**
   - Click the ✅ button to process your PDF.

5. **Interact with the Response:**
   - Use the play (▶️) and stop (⏹️) buttons to listen to the response.
   - Click the copy (📋) button to copy the response text.

## Technologies Used

- **Flask:** Web framework for building the application.
- **Google Gemini API:** For generating content based on the PDF and prompt.
- **pdf.js:** For converting PDF pages to images.

## Contributing

If you want to contribute to this project, please fork the repository and create a pull request with your changes. Make sure to follow the project's coding standards and write clear commit messages.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please reach out to:

- **Email:** shahram8708@gmail.com
- **GitHub:** [Shah Ram](https://github.com/shahram8708)
