cat <<EOF > README.md
# GenAI Flask App with IBM WatsonX

A robust Generative AI application built with **Flask** that integrates multiple LLMs (**Llama 3, Granite, Mistral**) using **IBM WatsonX** and **LangChain**. This project demonstrates how to build a scalable AI-powered web interface with real-time model switching.

## 🚀 Features
- **Multi-Model Support:** Seamlessly switch between Llama 3, Granite, and Mistral models.
- **Interactive UI:** Clean, responsive chat interface built with HTML, CSS, and JavaScript.
- **Real-Time Performance:** Tracks and displays response generation time.
- **Scalable Architecture:** Modular backend design separating model logic from application routes.

## 🛠️ Tech Stack
- **Backend:** Python, Flask
- **AI Integration:** LangChain, IBM WatsonX.ai
- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Version Control:** Git, GitHub

## ⚙️ Setup & Installation
1. **Clone the repository:**
   \`\`\`bash
   git clone https://github.com/Leelaissakattaota/genai-flask-app.git
   cd genai-flask-app
   \`\`\`

2. **Install dependencies:**
   \`\`\`bash
   pip install -r requirements.txt
   \`\`\`

3. **Configure Environment:**
   - Create a \`.env\` file.
   - Add your IBM WatsonX API key and Project ID.

4. **Run the Application:**
   \`\`\`bash
   python app.py
   \`\`\`
   Access the app at \`http://127.0.0.1:5000\`.

## 📂 Project Structure
- \`app.py\`: Main Flask application handling routes and API requests.
- \`model.py\`: Logic for initializing and querying the LLMs.
- \`templates/index.html\`: The frontend user interface.
- \`static/\`: CSS styles and JavaScript logic.

EOF
