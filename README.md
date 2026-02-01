# Simple Chatbot 💬

A lightweight JavaScript-based chatbot that responds to basic user inputs in real-time.

## 🌟 Features

- **Real-time responses** - Instant chat replies
- **Basic conversation** - Responds to greetings, questions, and common phrases
- **Time display** - Shows current time when asked
- **Simple UI** - Clean and minimal interface
- **No dependencies** - Pure vanilla JavaScript

## 🚀 Demo

**Try it live**: [https://vinayaka-29.github.io/simple-chatbot/](https://vinayaka-29.github.io/simple-chatbot/)

## 💻 How to Use

1. Open `index.html` in your web browser
2. Type a message in the input box
3. Click "Send" or press Enter
4. The chatbot will respond based on your input

## 🎯 Supported Commands

The chatbot understands and responds to:

- **"hello"** or **"hi"** → Greets you
- **"thank"** → Says you're welcome
- **"How are you?"** → Responds about its status
- **"time"** → Shows current time
- **"bye"** → Says goodbye
- Any other input → Default response

## 📁 Project Structure

```
simple-chatbot/
├── index.html      # Main HTML file with embedded JavaScript
└── README.md       # This file
```

## 🛠️ Technologies

- HTML5
- JavaScript (ES6)
- CSS (inline)

## 📝 Code Example

```javascript
function send() {
    let input = document.getElementById("userInput").value.toLowerCase();
    let response = "I didn't understand that.";
    
    if (input.includes("hello") || input.includes("hi")) {
        response = "Hello! How can I help you?";
    } else if (input.includes("thank")) {
        response = "You're welcome!";
    }
    // ... more conditions
}
```

## 🔧 Customization

To add more responses:

1. Open `index.html`
2. Find the `send()` function
3. Add new `else if` conditions with your keywords and responses

Example:
```javascript
else if (input.includes("weather")) {
    response = "I can't check the weather, but I hope it's nice!";
}
```

## 🌐 GitHub Pages Deployment

This chatbot is deployed using GitHub Pages. To deploy your own:

1. Fork this repository
2. Go to Settings → Pages
3. Select "main" branch
4. Click Save
5. Your chatbot will be live at: `https://yourusername.github.io/simple-chatbot/`

## 📈 Future Enhancements

- [ ] Add more conversation patterns
- [ ] Implement AI/ML for better responses
- [ ] Add chat history
- [ ] Improve UI with CSS styling
- [ ] Add voice input/output
- [ ] Multi-language support

## 🤝 Contributing

Feel free to fork this project and add your own improvements!

## 📄 License

MIT License - feel free to use this project for learning purposes

## 👤 Author

**Vinayaka-29**
- GitHub: [@Vinayaka-29](https://github.com/Vinayaka-29)

---

**Happy Chatting!** 🎉
