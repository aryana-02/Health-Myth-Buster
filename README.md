# Health Myth Buster App

## Overview

Health Myth Buster is a simple, interactive Python application designed to help users distinguish between common health myths and evidence-based facts. By inputting any health-related claim, users instantly receive a verdict—True, False, or Uncertain—along with a concise explanation. This project aims to promote accurate health information and dispel misinformation in an accessible way.

## Features

- **Instant Myth Busting:** Enter any health claim and receive a True/False/Uncertain verdict with an explanation.
- **Preloaded Knowledge Base:** Quickly identifies several widespread health myths and facts.
- **User-Friendly Loop:** Allows repeated checks until the user decides to exit.
- **Case-Insensitive Matching:** Recognizes claims regardless of capitalization for better accuracy[web:2][web:3][web:6].

## Technologies/Tools Used

- **Python 3.x:** Core programming language.
- **Standard Library:** No external dependencies, using basic Python data structures and control flow.

## Steps to Install & Run

1. **Clone or Download:** Get the project files from the repository.
2. **Verify Python Installation:** Ensure Python 3.x is installed by running `python --version` or `python3 --version` in your terminal or command prompt.
3. **Run the Script:**
    - Open a terminal in the project directory.
    - Start the app with:
      ```
      python health_myth_buster.py
      ```
      or, depending on your system:
      ```
      python3 health_myth_buster.py
      ```

## Instructions for Testing

1. **Launch the App:** Follow the steps above to start.
2. **Input Health Claim:** Type a health-related statement, e.g.:
   - *"Vaccines cause autism"*
   - *"Washing hands prevents infection"*
   - *"Lemon cures cancer"*
3. **View Result:** The app responds with a verdict and clear explanation.
4. **Repeat or Exit:** Enter additional claims or type `'exit'` to quit the program.

Feel free to extend the knowledge base by adding more myths and facts to the respective dictionaries!
