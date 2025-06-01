An AI-powered chatbot that helps users verify if their food is spoiled using a CNN-based image classifier and answers food-related queries using an NLP Question Answering model.

## 🔥 Features

- 📸 Detect spoiled food with VGG19-based CNN by uploading food images
- 💬 Chat with a bot trained on food-related Q&A using an LSTM encoder-decoder model
- 🧠 Combines NLP + Computer Vision into a Tkinter-based GUI
- ⭐ User feedback rating system included

## 🛠️ Project Structure

```

FoodAI-ChatBot/
├── chatbot\_app/         # Integrated GUI chatbot
├── nlp\_model/           # LSTM QA model files
├── cnn\_model/           # VGG19 CNN model files
└── main.py              # Main script to launch the chatbot

````

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/FoodAI-ChatBot.git
cd FoodAI-ChatBot
````

### 2. Install Requirements

```bash
pip install -r requirements.txt
```

### 3. Run the App

```bash
python main.py
```

## 🧠 Models Used

### 📘 NLP (LSTM QA Model)

* LSTM-based encoder-decoder
* Tokenizer files included
* Trained on custom Q\&A food dataset

### 🥼 CNN (VGG19)

* Based on VGG19 pretrained model
* Fine-tuned to classify "spoiled" vs. "good" food images

## 🧪 Example Inputs

```bash
You: My food is spoiled
🤖: Please upload an image of the spoiled food.
# Upload Image
🤖: Your food is spoiled. Refund can be claimed.

You: What should I do if my food is rotten?
🤖: You can upload the image of the food, and we will verify it for you.
```

## 🧾 License

This project is licensed under the MIT License.

👨‍🎓 Author
Kottu Saikumar

📧 Email: kottusaikumar2003@gmail.com

📞 Phone: +91 6304830339

📍 Location: Hyderabad, Telangana

🎓 B.Tech in Electronics and Communication Engineering (2020–2024)

🏫 University College of Engineering, JNTUK

💡 Areas of Interest: Data Science, Deep Learning, NLP, Computer Vision
