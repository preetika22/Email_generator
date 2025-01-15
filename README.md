# AI-Powered Email Generator
This project demonstrates the integration of advanced AI models with a user-friendly interface, making it a practical tool for automating the email generation process for job applications.
It is an AI-driven email generator that leverages LangChain, ChromaDB, Streamlit, and Llama 3.1 to automate the generation of professional emails based on job postings. The system scrapes job descriptions from websites, analyzes the content, and generates personalized emails.

## Features

- **Job Description Scraping**: Scrapes job descriptions from websites and processes the text for further analysis.
- **AI-Generated Emails**: Uses AI models to generate contextually relevant emails based on the scraped job descriptions.
- **Skill Matching**: Matches skills mentioned in job descriptions with a portfolio of technologies and links.
- **Interactive Web Interface**: Provides a user-friendly interface using Streamlit for easy interaction and email generation.
- **Data Persistence**: Stores job descriptions and related metadata in ChromaDB for efficient querying and retrieval.

## Tech Stack

- **[LangChain](https://www.langchain.com/)**: A framework for developing applications powered by language models.
- **[ChromaDB](https://www.chromadb.com/)**: A vector database for storing and querying embeddings efficiently.
- **[Streamlit](https://streamlit.io/)**: An open-source app framework for Machine Learning and Data Science projects.
- **[Llama 3.1](https://huggingface.co/models)**: A state-of-the-art language model used for natural language understanding and generation.
- **[Python](https://www.python.org/)**: The programming language used for the development of this project.

## Installation

1. **Clone the repository**:
   git clone (https://github.com/preetika22/Email_generator)
   cd email-generator-ai
2. **Create a virtual environment:**
   python -m venv env
   source env/bin/activate
3. **Install dependencies:**
   pip install -r requirements.txt
4. **Set up environment variables:**
    Create a .env file in the root directory and add your API keys and other configuration details:
   GROQ_API_KEY=your_groq_api_key
5. **Run the Streamlit app:**
   streamlit run main.py

**Project Structure**
*app.py*: Main entry point for the Streamlit app.
*portfolio.py*: Manages portfolio data and handles skill matching queries.
*chain.py*: Contains the AI logic for extracting job details and generating emails.
*requirements.txt*: Lists the Python dependencies required for the project.

### Tips for Customization:
- **Replace placeholders** (`yourusername`, `your_groq_api_key`, `your email`) with your actual details.
- **Include screenshots**: Add images of the application interface to make the README more engaging.
- **Add a demo**: If possible, include a link to a live demo or a video walkthrough of the application.

**Contact**
For any inquiries or feedback, please contact *@gmail.com.
