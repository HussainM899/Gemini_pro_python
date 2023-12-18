# Gemini-Pro Python Integration

This Python script showcases the integration of Gemini-Pro, a generative model from Google, using the Google Generative AI library. With an API key obtained from [Google Studio](https://makersuite.google.com/app/apikey), users can leverage the power of Gemini-Pro for content generation.

## Setup

1. **Obtain API Key:**
    - Visit [Google Studio](https://makersuite.google.com/app/apikey) to get your API key.
    - Copy and paste the API key in the designated area of the script.

2. **Run the Script:**
    - Execute the Python script after configuring the API key.

## Configuration

The script sets up the generative model with the following configurations:

- **Generation Config:**
  - Temperature: 0.9
  - Top-p: 1
  - Top-k: 1
  - Max Output Tokens: 2048

- **Safety Settings:**
  - HARM_CATEGORY_HARASSMENT: BLOCK_MEDIUM_AND_ABOVE
  - HARM_CATEGORY_HATE_SPEECH: BLOCK_MEDIUM_AND_ABOVE
  - HARM_CATEGORY_SEXUALLY_EXPLICIT: BLOCK_MEDIUM_AND_ABOVE
  - HARM_CATEGORY_DANGEROUS_CONTENT: BLOCK_MEDIUM_AND_ABOVE

## Usage

The model is initialized with the specified configurations, and a prompt is provided for content generation. The generated content is then printed to the console.

## Note

Ensure proper permissions and adhere to safety settings to prevent undesirable content generation.

