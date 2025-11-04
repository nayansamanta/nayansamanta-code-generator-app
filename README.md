Gemini-Powered Code Generator

A Streamlit web app powered by Google Gemini (Generative AI) that converts plain English descriptions into working code across multiple programming languages — with simple explanations included.

🧩 Features
Generate code from natural language prompts
Supports multiple programming languages (Python, Java, C++, C#, JavaScript, SQL, R, Go)
Provides syntax-highlighted output
Includes a plain-English explanation of the generated code

🖥️ How It Works
You describe the program in plain English.
The app sends your request to Gemini 1.5 Pro (via Google’s Generative AI API).
Gemini returns a code snippet and an explanation.
Streamlit displays the results neatly on the page.

⚙️ Setup Instructions
1. Clone the Repository
git clone https://github.com/yourusername/code-generator-app.git
cd code-generator-app

2. Create and Activate a Virtual Environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

3. Install Dependencies
pip install -r requirements.txt

4. Add Your API Key
Create a file named .streamlit/secrets.toml in your project folder and add this line:
GOOGLE_API_KEY = "your_actual_api_key_here"
(Alternatively, you can directly include the API key in your script — not recommended for public repos.)

5. Run the App
streamlit run Webpage.py

🌐 Supported Languages
🐍 Python
🦬 JavaScript
🦣 Java
🦍 C#
🦏 C++
🕸 C
🐦‍🔥 SQL
🦩 R
🐎 Go

📁 File Structure
📦 your-project/
 ┣ .streamlit/
 ┃ ┗ secrets.toml
 ┣ Webpage.py
 ┣ requirements.txt
 ┣ README.md
 ┗ SECURITY.md

🔒 Notes

Do not share your API key publicly.

https://nayansamanta-code-generator-app-e7hunusdjwqswnf8ys3cal.streamlit.app/  ---- this is the direct link you can use on browser with correct setup

The app uses Gemini 1.5 Pro; you can change to another model in the code if needed.

Works well on both local and cloud environments (e.g., Streamlit Cloud or Codespaces).
