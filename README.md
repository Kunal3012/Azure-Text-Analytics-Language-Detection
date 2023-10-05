# Language Detection Program using Azure Text Analytics

**Author:** Kunal Yadav  
**Email:** mailmekunal2002@gmail.com

## Introduction

This project utilizes Azure Text Analytics to create a language detection program. The program takes user text input and determines the language of the text using Azure's cognitive services.

## Implementation

### Configuration

The program is configured to use Azure's Text Analytics service. Configuration parameters, such as the service endpoint and key, are loaded from environment variables using the `python-dotenv` library.

### User Interaction

The program prompts the user to enter text continuously until the user inputs "quit." It then sends the input text to Azure Text Analytics for language detection.

### Language Detection

Azure Text Analytics is used to detect the primary language of the input text. The detected language is then displayed to the user.

## Conclusion

This language detection program leverages Azure Text Analytics to accurately determine the language of user-provided text. It provides a simple and effective way to identify the language of textual content.
