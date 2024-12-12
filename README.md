# League of Legends Champion Query Tool

This program allows users to fetch detailed data about League of Legends champions and interact with a Language Model (LLM) to ask questions about the fetched data. The tool integrates the Riot Games API and an LLM service for a seamless experience.

## Features
- Fetch champion data from Riot Games' Data Dragon API.
- Query the fetched data interactively using an LLM.
- Easy-to-use terminal-based interface.

## Requirements

Before running the program, ensure you have the following:

- Python 3.8 or higher
- Installed Python libraries:
  - `requests`
  - `json`
  - `groqcloud` (or appropriate library for your LLM integration)
  - `termcolor` (for colored terminal output)


## Usage



1 Enter the name of a League of Legends champion when prompted. Example:
   Enter the name of a League of Legends champion: Ahri

2 The program will fetch the champion's data from the Riot Games API.

3 Interact with the LLM by asking questions about the champion's data. Example:
   Ask me something about Ahri: What are Ahri's abilities?

4 Type `exit` to end the session.

## Program Flow
- The user inputs a champion's name.
- The program fetches data from the Riot Games API.
- The user interacts with the LLM by posing queries about the fetched data.

## Example Output
```
Enter the name of a League of Legends champion: Yasuo
Ask me something about Yasuo: What is Yasuo's passive ability?
Response: Yasuo's passive ability is "Way of the Wanderer"...
Ask me something about Yasuo: exit
```

