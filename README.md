# SLR Parser using Streamlit

This is a Python implementation of an SLR Parser that utilizes the Streamlit library for creating an interactive user interface. The SLR Parser is capable of parsing a context-free grammar and generating the parsing automaton, along with providing detailed parsing steps for a given input string.

## Usage

To use this SLR Parser, follow these steps:

1. **Upload Grammar File**: Upload a text file containing the grammar you want to parse. The grammar should be in a specific format.

2. **View Grammar Information**: Once the grammar file is uploaded, expand this section to view detailed information about the grammar, including terminals, non-terminals, FIRST and FOLLOW sets, and the augmented grammar.

3. **Enter Tokens**: Enter the tokens you want to parse separated by spaces.

4. **Parse Input**: Click on the "Parse Input" button to start parsing the input tokens using the SLR Parser. The parsing steps will be displayed, indicating whether the parser shifts, reduces, or encounters an error during parsing.

5. **Generate Automaton**: Optionally, you can check the box to generate and visualize the parsing automaton corresponding to the grammar.

## Grammar Format

The grammar should be provided in a text file with the following format:

- Each production rule should be on a separate line.
- Use `->` to denote the production.
- Terminals and non-terminals should be separated by spaces.
- Use `^` to represent the empty string (epsilon).

## Dependencies

This SLR Parser relies on the following Python libraries:

- Streamlit
- Graphviz
- Pandas

## Running the Application

To run the SLR Parser application, execute the Python script containing the Streamlit application code. Make sure you have installed the required dependencies beforehand.

```bash
streamlit run app.py
```

## Credit

This project was made by taking reference from: [Vipul97-SLR Parser](https://github.com/Vipul97/slr-parser/tree/master)
