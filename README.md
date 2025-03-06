# 🤖 AI Chatbot for eCommerce  

## 📌 Overview  
This project implements an **AI-powered chatbot** for an **eCommerce website**, using **Deep Learning and NLP models** to provide automated responses to customer queries. The chatbot is trained using **a custom dataset** and deployed via a **Falcon API**.  

## 📂 Project Structure  
```
|-- API_Falcon.py               # Falcon API for chatbot integration
|-- Deep learning chatbot.py     # Deep learning model for chatbot training
|-- dialogs.txt                  # Training dataset (questions & answers)
|-- requirements.txt              # List of dependencies
|-- index.html                   # Chatbot frontend interface
|-- dashboard.html                # Admin panel (optional)
|-- login.html                    # Admin login page (optional)
|-- README.md                     # Project documentation
```

## 🚀 Installation  
Clone the repository and install dependencies:  
```sh
git clone https://github.com/mfahadrafiq/AI Chatbot for eCommerce.git
cd AI-Chatbot-for-eCommerce
pip install -r requirements.txt
```

## 🛠️ Usage  
1. **Run the chatbot API**  
   ```sh
   python API_Falcon.py
   ```
2. **Train the deep learning model** (if needed)  
   ```sh
   python Deep learning chatbot.py
   ```
3. **Access the chatbot via the frontend**  
   - Open `index.html` in a browser.  

## 🔍 Model Pipeline  
- **Data Processing**: Cleans & tokenizes text from `dialogs.txt`.  
- **Feature Extraction**: Uses TF-IDF & CountVectorizer.  
- **Model Training**: Implements a **Deep Learning NLP model**.  
- **Deployment**: Served via **Falcon API** for real-time chatbot responses.  

## 📈 Features  
✔️ **Pre-trained chatbot model** for customer interaction  
✔️ **Deep learning-based text classification**  
✔️ **Web-based chatbot interface** for easy access  
✔️ **Scalable API** using Falcon  
