# Flash Card Game

## Overview

This Python application helps you transform your notes into a flashcard game, making it easier to review and remember information, especially for language learning!

## How It Works

The application extracts flashcard terms from a `lesson.md` file. It identifies terms enclosed in double backticks (``) as the prompt and their corresponding meanings or translations after `->`.

### Example Format

Your `lesson.md` file should follow this structure:

```md
- `hi` -> a way of greeting
- `bonjour` -> French for "hello"
- `ありがとう` -> Japanese for "thank you"
```

The application will generate flashcards based on this format and quiz you accordingly.

## Requirements

- Python 3.x must be installed on your system.

## Installation

1. Clone this repository or download the script.
2. Ensure Python is installed by running:

   ```sh
   python --version
   ```

3. Install dependencies if any are required (refer to `requirements.txt` if included):

   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. Modify `lesson.md` to include your notes in the specified format.
2. Run the flashcard game with:

   ```sh
   python main.py
   ```

3. Follow the on-screen prompts to test your knowledge.

## Features

- Simple and easy-to-use markdown-based input.
- Interactive flashcard system.
- Great for memorization and language learning!

## Contributing

Feel free to contribute by improving the functionality or adding new features! Submit a pull request or open an issue.

## License

This project is licensed under the MIT License.
