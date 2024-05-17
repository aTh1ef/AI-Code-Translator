Sure! Here is the updated README file for your project:

---

# AI Code Translator - BridgeX

AI Code Translator is a web application that showcases two chatbots side-by-side, enabling users to input code or text into the left chatbot and view AI-generated translations or responses on the right. It uses Google Generative AI (Gemini model) to create dynamic responses.

## Project Structure

- `index.html`: The main HTML file containing the structure for both chatbots, input fields, and AI-generated response handling.
- `<style>`: Embedded CSS to style the chatbots, user interface, and chat messages.
- `<script type="importmap">`: Import map to import Google Generative AI.
- `<script type="module">`: JavaScript module handling user input and AI interaction, including sending user messages and receiving AI responses.
- `analysis.html`: A page dedicated to analyzing pasted code, providing insights and suggestions.
- `documentation.html`: A page for generating documentation of the pasted code, including explanations and usage examples.

## Dependencies

- [Google Generative AI](https://cloud.google.com/generative-ai): Requires an API key to access the Gemini model for generating AI responses.
- [Google Fonts](https://fonts.google.com/): Utilizes "Material Symbols" for icons and "Inter" for font styling.

## Usage

To use this project, ensure you have a Google Generative AI API key. Follow these steps to set up and use the chatbots:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/aTh1ef/AI-Code-Translator.git
   cd AI-Code-Translator
   ```

2. **Configure API Key**
   - Obtain your Google Generative AI API key.
   - Add your API key to the appropriate configuration file or script.

3. **Run the Application**
   - Open `index.html` in your web browser to start using the AI Code Translator.

## Features

- **Chatbots Interface**: Input code or text on the left and view AI-generated translations or responses on the right.
- **Analysis Page**: Analyze pasted code to get insights, suggestions, and potential improvements.
- **Documentation Page**: Generate detailed documentation of pasted code, including explanations and usage examples.

## Contribution

We welcome contributions from the community. To contribute, please follow these steps:

1. **Fork the Repository**
2. **Create a Feature Branch**
   ```bash
   git checkout -b feature-branch
   ```
3. **Commit Your Changes**
   ```bash
   git commit -m "Add some feature"
   ```
4. **Push to the Branch**
   ```bash
   git push origin feature-branch
   ```
5. **Open a Pull Request**

