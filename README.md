# Anagram Finder using Histogram and Array Matching (C#)

## Overview

This C# console application analyzes a predefined list of words and identifies valid **anagram groups** by comparing their letter histograms (frequency counts). It uses arrays to store character 
data and matches words with identical frequency distributions.

## Features

- 📃 Uses a static list of words from an external source
- 📊 Builds histograms (letter frequency maps) for each word
- 🔁 Compares each word's histogram against others to detect anagram matches
- 🧠 Uses arrays and loops for efficient comparison logic
- 🗂️ Outputs groups of words that are valid anagrams

## How It Works

1. The program reads or contains a predefined list of words.
2. It converts each word into a histogram using a character array.
3. Histograms are compared pairwise or grouped based on frequency patterns.
4. Words with matching histograms are considered anagrams and grouped together.

## Sample Output
stop ---> tops

### Requirements

- Visual Studio (2019 or later)
- .NET SDK (Core or Framework)
- Windows OS
  
### How to Run

1. **Download and unzip** the project folder.
2. Open the solution file (`.sln`) in **Visual Studio**.
3. Build the solution.
4. Run the program.

## Future Improvements

- **Load Word List from a File**  
  Allow the program to read words from an external `.txt` file instead of using a hardcoded array.

- **Sort and Group Output Neatly**  
  Group anagrams alphabetically and output them in a clean, readable format with word counts per group.

- **Command-Line Arguments**  
  Add the ability to specify the input word list file path or toggle verbose output via command-line options.

- **Unit Testing**  
  Add tests using NUnit or MSTest to validate histogram creation, matching logic, and output formatting.

- **GUI Version with Windows Forms**  
  Create a user-friendly interface where users can drag and drop a file, view grouped anagrams in a list, and export results.

## License

This project was developed as part of a coursework assignment and is intended for educational use.
