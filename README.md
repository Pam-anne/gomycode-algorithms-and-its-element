# Sentence Analysis Algorithm

This repository contains a solution for the "Sentence Analysis" checkpoint. The objective is to create an algorithm that processes a sentence character-by-character to extract specific metadata using three distinct counters.

## 📝 Problem Description

The algorithm reads a sentence that ends with a period (`.`) and determines:
1.  **The length of the sentence:** Total number of characters (including the period).
2.  **The number of words:** Calculated based on the number of spaces between words.
3.  **The number of vowels:** A count of characters that are 'a', 'e', 'i', 'o', or 'u' (case-insensitive).

## 🚀 The Logic

The algorithm follows these specific constraints:
* Processes characters one at a time.
* Uses exactly three variables as counters.
* Stops execution immediately when a period (`.`) is encountered.

### Logic Flow Diagram


## 🛠️ Implementation Details

The solution uses a **WHILE loop** to iterate through the input string. 

* **Length Counter:** Increments on every iteration.
* **Word Counter:** Initialized at 1 (to account for the last word) and increments every time a space character (`" "`) is detected.
* **Vowel Counter:** Uses a conditional check (IF/OR) to match the current character against the set of vowels $\{a, e, i, o, u\}$.

## 📂 Project Structure

* `analyze_sentence.algo`: Contains the pseudocode/source code for the logic.
* `README.md`: Project documentation and evaluation overview.

