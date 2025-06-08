# 🏥 AI-Powered Medical Chatbot 🤖

A Flask-based medical chatbot that uses machine learning to provide medical information and support.

## 🌟 Features

- 🤖 AI-powered medical responses
- 💬 Natural language understanding
- 🏥 Medical intent classification
- ⚡ Real-time responses

## 🛠️ Tech Stack

- Python
- Flask
- TensorFlow
- NLTK
- React (Frontend)

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- pip (Python package manager)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/rupakghanghas/MedBot.git
cd MedBot
```

2. Install dependencies:
```bash
cd Medical-Chatbot/prediction
pip install -r requirements.txt
```

3. Run the application:
```bash
python main.py
```

The application will be available at `http://localhost:5000`

## 📝 API Endpoints

- `GET /`: Home page
- `POST /predict`: Chat endpoint
  - Request body: `{"message": "your message here"}`
  - Response: `{"answer": "bot response"}`

## 🔧 Configuration

The chatbot uses the following configuration files:
- `intents.json`: Contains training data and responses
- `chatbotmodel.h5`: Trained neural network model
- `words.pkl` and `classes.pkl`: Preprocessed data files

## 📫 Contact

- LinkedIn: [Rupak Ghanghas](https://www.linkedin.com/in/rupak-ghanghas-23652b244/)
- Email: rupakghanghas999@gmail.com

## 📄 License

This project is licensed under the MIT License. 