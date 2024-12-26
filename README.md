
# 🌟 AI-Agent Business Analyst Assistant

An advanced AI-powered Business Analyst Assistant designed to automate report generation and streamline data analysis using a multi-agent architecture and cutting-edge AI tools.

---

## 📜 Features

### 🎯 Key Highlights
- **Multi-Agent Architecture**:
  - **Business Analyst Agent**: Understands business requirements and queries.
  - **SQL Developer Agent**: Writes and executes SQL queries.
  - **Report Writer Agent**: Generates professional reports from query results.
- **Retrieval-Augmented Generation (RAG)**: Enhances accuracy in handling complex queries by retrieving relevant data.
- **Reasoning and Acting (ReAct)**: Empowers agents to reason through tasks and act dynamically to resolve issues.
- **Custom LangChain Tools**: Built and integrated tools from the LangChain community for SQL query generation, execution, and validation.
- **Interactive Query Input**: Frontend allows users to input queries for data analysis and report generation.
- **Executable IPython Notebook**: Includes a `.ipynb` file for testing and running the assistant locally.

---

## 🛠️ Tech Stack

| **Category**            | **Technologies Used**                                 |
|-------------------------|------------------------------------------------------|
| **Frontend**            | React.js                                             |
| **Backend**             | Flask                                                |
| **Agent Framework**     | CrewAI, LangChain                                    |
| **Agent Enhancements**  | LangGraph, Retrieval-Augmented Generation (RAG), ReAct |
                                              

---

## 🏗️ Architecture Flow

1. **Query Input**: Users input business queries through the React-based frontend.
2. **Agent Interaction**:
   - The **Business Analyst Agent** interprets the input query.
   - The **SQL Developer Agent** writes and executes SQL queries on the database.
   - The **Report Writer Agent** compiles query results into a professional report.
3. **Custom Tool Integration**:
   - LangChain tools are used for SQL generation, execution, and verification.
   - Enhanced capabilities ensure agents adapt dynamically to user needs.
4. **Result Delivery**:
   - Reports are displayed on the frontend.
   - Users can test and debug the process using the provided IPython Notebook.

---

## 🚀 Quick Start Guide

### 📋 Prerequisites
- Install [Python](https://www.python.org/), [Flask](https://flask.palletsprojects.com/), and required Python libraries.
- Install [Node.js](https://nodejs.org/) and npm.
- Install Jupyter Notebook for running `.ipynb` files.

### 🖥️ Setting Up the Application

1. **Clone the repository**:
   ```bash
   git clone <[repository-url](https://github.com/alok12-3/aiagent_dataAnalyst-assistant)>
   cd <repository-directory>
   ```

2. **Install backend dependencies**:
   ```bash
   cd sqlflask
   pip install -r requirements.txt
   flask run
   ```

3. **Install frontend dependencies**:
   ```bash
   cd sqlreact
   npm install
   npm start
   ```

4. **Run the IPython Notebook** (optional):
   - Navigate to the `notebooks` directory.
   - Open the `.ipynb` file in Jupyter Notebook.
   - Run the cells to interact with the AI agents directly.

5. Access the application on `http://localhost:3000` (default for React).

---

## 🌐 Deployment

- The application is deployed using Flask for the backend and React for the frontend.
- Hosted on a reliable infrastructure for optimal performance and scalability.

---

## 📂 File Structure

```plaintext
.
├── sqlreact/                # React frontend
├── sqlflask/                 # Flask backend
├── sql-agents/               # IPython Notebook for testing
├── requirements.txt         # Python dependencies
└── README.md                # Project documentation
```

---

## 🤝 Acknowledgments

- **[CrewAI](https://crewai.com)**: For multi-agent framework support.
- **[LangChain](https://langchain.com)**: For building and managing custom agents.
- **[Flask](https://flask.palletsprojects.com/)**
- **[React](https://reactjs.org/)**: For seamless integration.

---

## 📌 Future Improvements
- Expand agent capabilities to handle diverse data sources beyond SQL.
- Introduce support for visualization tools for graphical data representation.
- Add role-specific querying templates for tailored insights.

---

### 📧 Contact
For questions or suggestions, feel free to contact **[Anupunj Alok](anupunj1alok@gmail.com)**.

---

**⭐ Star this repository if you found it helpful!**
```
