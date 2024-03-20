# MultiLanguage Invoice Extractor

This application allows you to extract information from invoice images using Google's Generative AI. You can input a prompt and upload an image of an invoice, and the application will provide a response based on the invoice content.

## Prerequisites

Make sure you have the following installed:

- Python 3.6 or later
- [Streamlit](https://streamlit.io/)
- [dotenv](https://pypi.org/project/python-dotenv/)
- [Pillow (PIL)](https://pillow.readthedocs.io/en/stable/)
- [Google Generative AI](https://github.com/google-research/sg2ada)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/your_repository.git
   ```

2. Navigate to the project directory:

```bash
cd your_repository
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Set up environment variables by creating a .env file in the root directory and adding your Google API key:

```plaintext
GOOGLE_API_KEY=your_api_key_here
```


## Usage

To run the MultiLanguage Invoice Extractor, execute the following command:

```bash
streamlit run app.py
```

- Choose an image of an invoice by clicking on "Choose an image of invoice......" and upload the image file.

- Click the "Tell me about the invoice." button to extract information from the uploaded invoice ima