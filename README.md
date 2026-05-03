Foundation & Environment Setup
**Project:** Healthcare Monitoring AI Agent (MediBook India / Health Assistant)[cite: 1]
**Track:** Track A (Essential)[cite: 1]

This report outlines the initial phase of the project, focusing on establishing a functional development environment and securing the necessary free-tier resources to build the core health monitoring functionality[cite: 1].

---

### 1. Required API Keys (Free Tier)
To keep the project simple and cost-effective, we will use the following non-paid APIs for medication tracking, fitness data, and medical information[cite: 1]:

| Service | Purpose | API/Source | Link/Instructions |
| :--- | :--- | :--- | :--- |
| **Fitness Data** | Steps and activity tracking | **Google Fit API** | Use Google Cloud Console to enable "Fitness API."[cite: 1] |
| **Nutrition** | Indian diet tracking | **Edamam API** | Free tier available for developers (Nutrition Wizard).[cite: 1] |
| **Medical Info** | Reliable health lookup | **MedlinePlus API** | Free, high-quality medical information from the NIH.[cite: 1] |
| **LLM Core** | AI Chatbot logic | **Groq / Hugging Face** | Use free-tier Llama 3 or MedAlpaca models (Healthcare focused).[cite: 1] |

2. Useful Resources for Google Colab
Since the goal is to complete the project within Google Colab, use these resources to streamline your development[cite: 1]:

*   **Development Frameworks:**
    *   **LangChain:** The core framework for building the healthcare chatbot[cite: 1].
    *   **Streamlit-Colab:** Use `pytunnel` or `localtunnel` to preview your Streamlit dashboard directly from a Colab cell[cite: 1].
*   **Data Handling:**
    *   **Pandas:** For parsing health data and metrics[cite: 1].
    *   **SQLite:** A lightweight database (included in Python) to store medication schedules and patient metrics locally in Colab[cite: 1].
*   **Documentation & Safety:**
    *   **NIH MedlinePlus Connect:** Documentation on how to link your app to official medical data.
    *   **Open Government Data (OGD) Platform India:** For datasets related to Indian healthcare facilities[cite: 1].



3. Week 1 Checklist & Progress
*   [ ] **Environment Setup:** Installed `langchain`, `pandas`, and `streamlit` in the Colab notebook[cite: 1].
*   [ ] **Repository:** Created a GitHub repository to track weekly progress[cite: 1].
*   [ ] **Basic Bot logic:** Initialized a simple Python script to handle "Medication Reminders" (e.g., "Remind me to take Paracetamol at 8 PM")[cite: 1].
*   [ ] **Database Initialization:** Created a local `.db` file using SQLite to store user-entered health goals[cite: 1].



