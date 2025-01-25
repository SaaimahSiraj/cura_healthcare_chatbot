Cura - AI-Powered Healthcare Chatbot
Cura is an AI-driven healthcare assistant designed to provide users with seamless access to healthcare information, consultation services, and medical insights. Built with advanced technologies like Streamlit, Gemini, and Langchain, Cura enhances the user experience by enabling interactive conversations and personalized healthcare solutions.

## Features

- Symptom Checker: Users can input symptoms to receive potential diagnoses and advice.
- Doctor Recommendation: Suggests suitable specialists based on user inputs.
- Medical Record Reader: Analyzes medical documents and extracts relevant information.
- Home Remedies: Offers simple remedies for diagnosed conditions.
- Interactive Conversations: Facilitates engaging, natural interactions with users.
- 
## File Structure

- **`healthcarechatbot.py`**: The main script handling the chatbot's functionality.
- **`cura.py`**: Streamlit-based interface for deploying the chatbot.
- **`.env`**: Contains environment variables for secure configuration (e.g., API keys).
- **`index.faiss`**: FAISS index file used for efficient similarity search.
- **`index.pkl`**: Pickle file containing additional indexing information.

### Folder Requirement
Place the `index.faiss` and `index.pkl` files inside a folder named `indexes` in the root directory of the project. The structure should look like this:

```
|-- cura
    |-- healthcarechatbot.py
    |-- cura.py
    |-- .env
    |-- indexes
        |-- index.faiss
        |-- index.pkl
```

---

## Installation

Follow these steps to set up and run the Cura chatbot:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/cura.git
   cd cura
   ```

2. **Install Dependencies**:
   Ensure Python 3.8+ is installed, then run:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set Up Environment Variables**:
   Create a `.env` file in the root directory and configure the necessary API keys and credentials as required.

4. **Organize Index Files**:
   Move the `index.faiss` and `index.pkl` files into the `indexes` folder in the project directory.

5. **Run the Application**:
   Launch the chatbot using:
   ```bash
   streamlit run cura.py
   ```

## Usage

1. Access the application via the provided local URL (e.g., `http://localhost:8501`).
2. Start interacting with Cura by entering your symptoms or uploading medical records.
3. Explore features like home remedies and doctor recommendations.

## Technologies Used

- **Streamlit**: For creating an intuitive web-based interface.
- **Gemini**: Powers the conversational and generative AI functionalities.
- **Langchain**: Facilitates language-based tasks and integrations.
- **FAISS**: Ensures efficient similarity searches.
- **Python**: Core language for backend development.

Contributing
Contributions are welcome! Feel free to fork this repository, make improvements, and submit pull requests. Ensure you follow best practices and provide detailed explanations for your changes.

Contact

For questions, feedback, or support, reach out to:
Developer: Saaimah Siraj,Tejaswi Mahadev



