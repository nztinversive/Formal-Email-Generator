# Formal Email Generator

The Formal Email Generator is a web application that helps users improve their email writing skills by converting their input into a more professional format. This tool also supports converting input text into different tones and English dialects (American or British).

The application is built using Streamlit and leverages the power of OpenAI's GPT-4, via LangChain, to generate the converted emails.

## Features

- Convert input email into a specified tone (Formal or Informal)
- Convert input email into a specified dialect (American or British)
- Reply to an existing email with the same tone and dialect conversion options
- Maximum email length of 700 words

## How it works

1. The user inputs their OpenAI API key.
2. The user selects the desired tone, dialect, and action (New Email or Reply).
3. The user inputs the email content.
4. The application generates a prompt based on the user's input and uses the OpenAI GPT-4 model to generate the converted email.
5. The user receives the converted email, which is displayed on the web page.

## Credits

This project is inspired by and based on the code from Data Independent's YouTube video: [Build Your Own OpenAI + LangChain Web App in 23 Minutes](https://www.youtube.com/watch?v=U_eV8wfMkXU).

## Usage

Make sure you have Streamlit installed:

```bash
pip install streamlit

streamlit run app.py
