# Simple Rule Based System 
A simple chatbot built with Python that responds to user input based on predefined rules.  
This project demonstrates the basics of rule-based artificial intelligence and keyword matching.

## Features
- Responds to greetings like **hello** and **hi**
- Handles farewells like **bye**
- Provides help when asked
- Answers simple questions about weather and its identity
- Returns a default response for unknown inputs
- Allows users to exit with `exit` or `quit`

## How It Works
The chatbot uses a dictionary of predefined rules where:
- **Keys** = Keywords or phrases
- **Values** = Corresponding chatbot responses
When a user enters text:
1. The input is converted to lowercase.
2. The chatbot checks if any keyword matches.
3. If a match is found, the chatbot returns the related response.
4. If no match is found, a default response is given.

## Requirements
- Python3.6 or higher

## Installation
Clone this repository:
```bash
git clone <your-repository-url>
```
Move into the project folder:
```bash
cd rule-based-chatbot
```

## Running the Project
Run the chatbot using:
```bash
python rule_based_chatbot.py
```

## Example Usage
```text
You: hello
Chatbot: Hello! How can I help you today?
You: what is your name?
Chatbot: I'm a simple rule-based chatbot. I don't have a name, but you can call me Chatbot!
You: weather
Chatbot: The weather is sunny today. Don't forget your sunglasses!
You: exit
Chatbot: Goodbye! Have a great day!
```

## Project Structure
```bash
kbs.ipynb
README.md
```

## Future Improvements
Possible upgrades for this chatbot:
- Add more conversation rules
- Support multiple languages
- Use regular expressions for smarter matching
- Connect to APIs for real-time weather updates
- Build a graphical user interface

## Concepts Learned
This project helps in understanding:
- Object-Oriented Programming (OOP)
- Dictionaries in Python
- String manipulation
- Conditional logic
- Building interactive console applications

## Author
Created as part of learning chatbot development and rule-based AI systems.