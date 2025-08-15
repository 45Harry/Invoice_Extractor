# Invoice Extractor using Google Gemini

This project is an Invoice Extractor application powered by Google Gemini (Generative AI) and Streamlit. Users can upload invoice images and ask questions about the content, receiving intelligent, context-aware answers.

---

## Features

- **Invoice Understanding:** Upload an invoice image and ask questions about its content.
- **Google Gemini AI:** Utilizes Gemini's generative model for extracting and reasoning over invoice data.
- **Streamlit Web App:** Simple, interactive web interface for seamless user experience.
- **Image Support:** Accepts JPG, JPEG, and PNG invoice images.

---

## How It Works

1. **User Uploads Invoice:** Upload an image of an invoice via the web interface.
2. **Ask a Question:** Enter a prompt/question about the invoice (e.g., "What is the total amount?").
3. **AI Analysis:** The app sends the image and question to Google Gemini, which analyzes and returns a relevant answer.

---

## Project Structure

- `app.py` — Main Streamlit app, handles UI, image upload, and Gemini API calls.
- `requirements.txt` — Python dependencies.
- `notebook.ipynb` — (Optional) Jupyter notebook for experimentation.
- `OIP-1722005106.jpg` — Sample invoice image.

---

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone git@github.com:45Harry/Invoice_Extractor.git
   cd Invoice_Extractor
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up Google Gemini API Key:**
   - Create a `.env` file in the project root with your API key:
     ```
     GOOGLE_API_KEY=your_google_api_key
     ```

4. **Run the app:**
   ```bash
   streamlit run app.py
   ```
   - Access the app at the local URL provided by Streamlit.

---

## Example Usage

- Upload an invoice image (JPG, JPEG, PNG).
- Enter a question like: `What is the invoice date?` or `Who is the vendor?`
- Click "Tell me about the invoice" to get an AI-generated answer.

---

## License

This project is licensed under the MIT License.
