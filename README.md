🎯 Interview Preparation AI
An interactive AI-powered assistant built using Streamlit and LangChain to help users practice for job interviews. The app generates dynamic questions, evaluates your answers, and suggests improvements — making your preparation smarter and more effective.

📂 Project Structure
bash
Copy
Edit
.
├── chains/                  # LangChain chains for question generation, evaluation, and suggestions
├── prompts/                 # Prompt templates for chains
├── venv/                    # Virtual environment (not tracked)
├── .env                     # Environment variables (e.g., API keys)
├── config.py                # Configuration (e.g., LLM setup, environment loading)
├── main.py                  # Main Streamlit app
├── requirements.txt         # Python dependencies
🚀 Features
✅ Role-specific interview question generation (e.g., "ML Intern")

🔄 Choose question type: technical or behavioral

📋 Answer submission with real-time feedback

📈 Automatic evaluation with scoring or analysis

💡 Improved answer suggestions using LLMs

🧠 Conversation memory for better continuity

🛠️ Getting Started
1. Clone the repository
bash
Copy
Edit
git clone https://github.com/yourusername/interview-prep-ai.git
cd interview-prep-ai
2. Create and activate a virtual environment
bash
Copy
Edit
python -m venv venv
source venv/bin/activate      # Windows: venv\Scripts\activate
3. Install dependencies
bash
Copy
Edit
pip install -r requirements.txt
4. Add your environment variables
Create a .env file with your API keys, for example:

ini
Copy
Edit
OPENAI_API_KEY=your_openai_key_here
5. Run the app
bash
Copy
Edit
streamlit run main.py
🧠 Core Components
🔹 chains/
question_chain.py: Generates role-specific questions.

evaluation_chain.py: Evaluates answers based on criteria.

better_answer_chain.py: Generates improved answers.

🔹 prompts/
Stores prompt templates for chaining and customization.

🔹 config.py
Loads API keys and configures LLM providers.

📌 Example Workflow
Input a job role (e.g., "ML Intern").

Choose between technical or behavioral questions.

Answer the question shown in the app.

Get an AI evaluation and a better suggested response.

Continue the interview with a new question.

📃 License
MIT License

🙌 Contributions
Pull requests and ideas are welcome! Want to add new question types, improve evaluation logic, or integrate new LLMs? Go for it.
