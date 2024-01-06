# Flet Chat App with Google AI and Dynamsoft Barcode Reader
The project demonstrates how to integrate [Dynamsoft Barcode Reader](https://pypi.org/project/dbr/) and [Gemini APIs](https://ai.google.dev/tutorials/python_quickstart) into a Flet chat app.

https://github.com/yushulx/flet-chat-app-gemini-barcode/assets/2202306/ef159de0-cdf9-48e2-91d9-3da3ce9f85a0

## Installation

```bash
pip install -r requirements.txt

```

## Getting Started
1. Get an [API key](https://makersuite.google.com/app/apikey) for Gemini in Google AI Studio and replace the value of `API_KEY` in `chatbot.py`.
    
    ```python
    genai.configure(api_key='API_KEY')
    ```
2. Request a [free trial license](https://www.dynamsoft.com/customer/license/trialLicense?product=dbr) for Dynamsoft Barcode Reader and replace the value of `LICENSE-KEY` in `chatbot.py`.

    ```python
    license_key = "LICENSE-KEY"
    ```

3. Run the app:

    ```bash
    flet run chatbot.py
    ```