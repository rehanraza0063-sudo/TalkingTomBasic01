# 🐾 Talking Pet Web Application

An interactive **Talking Pet Web Application** built with Python and Flask. The project is inspired by virtual pet games and allows users to interact with a virtual pet through voice, buttons, and animations.

## 🌟 Features

* 🐱 Interactive virtual pet
* 🎤 Voice input using the microphone
* 🔊 Text-to-speech responses
* 👄 Animated mouth while speaking
* ❤️ Pet the virtual animal
* 🍎 Feed the pet
* 🎾 Play with the pet
* 💬 Random conversations and reactions
* 😊 Happiness level system
* ❤️ Floating heart animations
* 📱 Responsive design for desktop and mobile
* 🌐 Runs locally in a web browser

## 🛠️ Technologies Used

* **Python**
* **Flask**
* **HTML5**
* **CSS3**
* **JavaScript**
* **Web Speech API**
* **Browser Speech Recognition**
* **Browser Text-to-Speech**

## 📂 Project Structure

```text
Talking-Pet/
│
├── talking_pet.py
└── README.md
```

The complete web application is contained in a **single Python file**.

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/talking-pet.git
```

### 2. Open the project folder

```bash
cd talking-pet
```

### 3. Install Flask

```bash
pip install flask
```

## ▶️ Run the Project

Run:

```bash
python talking_pet.py
```

You should see:

```text
🐾 TALKING PET WEB APP
Open: http://127.0.0.1:5000
```

Open the following address in your browser:

```text
http://127.0.0.1:5000
```

## 🎤 Voice Interaction

Click **"Talk to Me"** and allow microphone access when your browser asks for permission.

The pet can respond to phrases such as:

* "Hello"
* "How are you?"
* "What is your name?"
* "Let's play"
* "Give me food"
* "I love you"
* "Bye"

The browser's **Speech Recognition API** converts your voice into text, and the application generates a response using JavaScript.

## 🐾 Pet Interactions

| Action        | Reaction                     |
| ------------- | ---------------------------- |
| 💬 Talk       | Pet says a random message    |
| 🍎 Feed       | Increases happiness          |
| 🎾 Play       | Pet jumps                    |
| ❤️ Pet        | Pet reacts and hearts appear |
| 🎤 Talk to Me | Pet listens to your voice    |
| 🐱 Click Pet  | Pet gives a random reaction  |

## ❤️ Happiness System

The virtual pet has a happiness score starting at **80**.

Different interactions increase the happiness level:

```text
🍎 Feed  → +5
🎾 Play  → +8
❤️ Pet   → +4
```

The score is displayed at the top of the application.

## 🔊 Text-to-Speech

The project uses the browser's built-in **Speech Synthesis API** to make the virtual pet speak.

No external AI or paid API is required.

## 🎤 Speech Recognition

The application uses the browser's **Speech Recognition API** for voice input.

Browser support can vary. Chrome-based browsers generally provide the best compatibility.

## 🎨 UI & Animation

The application includes CSS animations for:

* 🐱 Pet movement
* 👄 Talking mouth
* 🎾 Jumping
* ❤️ Hearts
* 😄 Reactions
* 🔄 Shake animation

## 🔮 Future Improvements

Possible future upgrades include:

* 🤖 AI-powered conversations
* 🧠 Memory for previous conversations
* 🎭 Multiple pet characters
* 👕 Custom clothes and accessories
* 🍕 More food items
* 🎮 Mini-games
* 🪙 Coins and reward system
* 🌙 Day/night mode
* 💾 Saving pet progress
* 📊 Pet health, hunger, and energy levels
* 🗣️ Multiple languages
* 📱 PWA/mobile-app support

## 🎯 Learning Outcomes

Through this project, I explored:

* Python Flask web development
* Frontend and backend integration
* HTML/CSS UI development
* JavaScript browser APIs
* Voice recognition
* Text-to-speech
* Interactive animations
* Event handling
* Responsive web design

## 📸 Project Preview

Add screenshots or a GIF of your application here:

```text
![Talking Pet Screenshot](screenshot.png)
```

## 🚀 Project Goal

The goal of this project was to create a simple and interactive virtual pet experience while learning how **Python, Flask, JavaScript, browser APIs, and animations** can work together in a web application.

## 👨‍💻 Author

**Rehan Raza**

Built as a personal learning and portfolio project.

---

⭐ If you like this project, consider giving the repository a star!
