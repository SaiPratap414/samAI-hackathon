
# samAI Hackathon Project

## 🚀 Ultimate Goal

The goal of this project is to develop an AI-powered wellness assistant specifically designed for software developers. The assistant helps developers maintain their physical and mental health by providing personalized health plans based on their daily coding-related struggles. This includes detecting symptoms of stress, eye strain, and fatigue, and offering advice and activities to mitigate these issues.

---

## 🧑‍💻 Project Structure

This project consists of two main components:

- **Frontend**: `codefit-client` - A React-based web application where users can input their feelings, and receive personalized wellness plans.
- **Backend**: `codefit-server` - A FastAPI-based server that processes the user's input using AI models and generates a personalized wellness plan.

---

## 🛠️ Requirements

### Backend (FastAPI)
- Python 3.8+
- Install the required dependencies:
  ```bash
  pip install -r codefit-server/requirements.txt
  ```

### Frontend (React)
- Node.js 14+
- Install the required dependencies:
  ```bash
  cd codefit-client
  npm install
  ```

---

## ⚙️ How to Run the Project

### 1. Run the Backend

To start the backend server, navigate to the `codefit-server` directory and run:

```bash
cd codefit-server
uvicorn main:app --reload
```

This will start the backend server locally on `http://localhost:8000`.

### 2. Run the Frontend

Once the backend is running, you can start the frontend application. Navigate to the `codefit-client` directory and run:

```bash
cd codefit-client
npm start
```

This will start the React development server locally on `http://localhost:3000`.

---

## 💡 How It Works

1. **User Input**: The user inputs how they are feeling, such as experiencing eye strain or fatigue.
2. **AI Analysis**: The frontend sends the input to the backend, which uses NLP models to analyze the text, determine the user's symptoms, mood, and energy level.
3. **Wellness Plan Generation**: The backend generates a personalized wellness plan, including tips, activities, and a journaling prompt.
4. **Display to User**: The frontend displays the generated wellness plan to the user in a friendly format. The user can also view their past wellness plans.

---

## 📦 Submodules

This project contains two submodules that handle the frontend and backend components:

- `codefit-client`: The frontend of the web application, built with React.
- `codefit-server`: The backend API, built with FastAPI.

---

## 🔧 Contributing

Feel free to fork the repository and submit pull requests. If you'd like to contribute, follow these steps:

1. Fork the repo.
2. Clone your fork: `git clone <your-fork-url>`
3. Create a new branch: `git checkout -b my-feature-branch`
4. Make your changes and commit: `git commit -m "Added a cool feature"`
5. Push to your fork: `git push origin my-feature-branch`
6. Submit a pull request.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
```

### Key Sections in the README:

1. **Ultimate Goal**: Describes the purpose and focus of the project.
2. **Project Structure**: Outlines the two major components of the project.
3. **Requirements**: Lists the dependencies needed to run both frontend and backend.
4. **How to Run**: Provides step-by-step instructions on how to start the backend and frontend servers.
5. **How It Works**: Explains the flow of data and how the project functions.
6. **Submodules**: Mentions the submodules for frontend and backend.
7. **Contributing**: Explains how others can contribute to the project.
8. **License**: Includes a note on the project's license (assuming it's MIT, but you can change it based on your actual license).
