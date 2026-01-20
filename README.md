# InfoBOT (Agricultural Chatbot) Using Python

This project is a simple command-line chatbot called **InfoBOT**, built to help users get quick information about crops. It uses basic Python I/O and a modular structure for easy extension.

---

## What This Project Does

* Greets the user and interacts in a conversational style
* Recognizes basic greetings and polite commands
* Asks for the user's name and agricultural background
* Takes crop names and provides relevant information
* Handles unknown crops with a friendly fallback response

---

## Key Steps

**Startup**

* `chatbot.py` welcomes the user and enters a loop waiting for input

**User Interaction**

* Detects greetings (`hi`, `hello`, `namaste`, `hey`, `yo`)
* Prompts for name and agricultural background
* Handles `ok` to prompt for crop input
* Handles `yes` or `no` for background and guides accordingly
* Ends session politely if user says `thank you.`

**Crop Lookup**

* Uses `agriculture.py` to fetch crop details
* Prints info if crop found
* Apologizes and asks for another crop if not found

---

## Technologies Used

* Python 3.x
* Standard Input/Output (`input()`, `print()`)
* Modular design (`import`)
* Simple `if-elif-else` logic

---

## How to Run

Clone this repo:

```bash
git clone https://github.com/yourusername/infobot-agriculture-chatbot.git
cd infobot-agriculture-chatbot
```

Run the chatbot:

```bash
python chatbot.py
```

Then interact by typing:

* Greetings (`hi`, `hello`, etc.)
* `ok` to enter crop names
* Crop names directly
* `thank you` to exit

---

## Extending This Project

* Add more crops to `agriculture.py`
* Improve the conversation flow and understanding
* Integrate weather data, tips, or suggestions
* Add better natural language handling and error checks

---

## Report

For detailed code explanation and flow, check the comments inside `chatbot.py` and `agriculture.py`.

---

## License

Fork it, build on it, adapt it for your own needs, just credit this repo if you reuse or share.
