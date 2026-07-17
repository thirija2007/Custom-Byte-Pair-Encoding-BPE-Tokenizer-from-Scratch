# Custom Byte Pair Encoding (BPE) Tokenizer from Scratch

## Project Overview

The Custom Byte Pair Encoding (BPE) Tokenizer from Scratch project implements the Byte Pair Encoding algorithm used in Natural Language Processing (NLP). The tokenizer learns subword units by repeatedly merging the most frequent adjacent character pairs in a given dataset. This approach helps reduce vocabulary size and efficiently handle unknown words.

## Objective

* To understand the working of the Byte Pair Encoding algorithm.
* To build a custom tokenizer from scratch using Python.
* To learn how subword tokenization works in Natural Language Processing.
* To implement encoding and decoding of words using learned BPE merge rules.

## Features

* Character-level vocabulary creation.
* Frequency-based pair counting.
* Automatic merging of frequent symbol pairs.
* Generation of BPE merge rules.
* Word encoding using learned merge rules.
* Word decoding back to the original form.
* Training corpus support using corpus.txt.
* Simple and lightweight implementation in Python.

  
## Project Structure

Custom_BPE_Tokenizer/
│

├── BPE_Tokenizer.ipynb

├── corpus.txt

├── README.md

## Workflow

Start

↓

Read Training Corpus (corpus.txt)

↓

Create Initial Vocabulary

↓

Count Adjacent Symbol Pairs

↓

Find Most Frequent Pair

↓

Merge Symbol Pair

↓

Update Vocabulary

↓

Repeat Merge Process

↓

Store Merge Rules

↓

Encode Input Word

↓

Decode Tokens

↓

Display Results

↓

Stop


# Algorithms

1.Import the required library.

2.Read the training corpus from corpus.txt.

3.Create the initial character-level vocabulary.

4.Count the frequency of adjacent symbol pairs.

5.Select and merge the most frequent pair.

6.Update the vocabulary with merged tokens.

7.Repeat the merging process for multiple iterations.

8.Store the learned merge rules.

9.Encode a new word using the merge rules.

10.Decode the encoded tokens.

11.Display the results and final vocabulary.

12.Stop

## Technologies Used

* Python
* Jupyter Notebook
* Collections Module (Counter)
* File Handling
* Byte Pair Encoding (BPE) Algorithm

## Applications

* Natural Language Processing (NLP)
* Machine Translation
* Text Summarization
* Chatbots and Virtual Assistants
* Search Engines
* Large Language Models (LLMs)
* Text Generation Systems
* Sentiment Analysis
* Speech Recognition
* Language Modeling

## Output

<img width="405" height="425" alt="Screenshot 2026-07-14 231358" src="https://github.com/user-attachments/assets/67e5d76b-cf0a-4224-873b-c7ecaf04a26e" />



## Result

The Custom Byte Pair Encoding (BPE) Tokenizer was successfully implemented. The tokenizer learned merge rules from the training corpus (corpus.txt), generated a final vocabulary, and correctly encoded and decoded the input word.

## Conclusion

The Custom Byte Pair Encoding (BPE) Tokenizer was successfully implemented using Python. The tokenizer learns subword units from the training corpus by repeatedly merging the most frequent character pairs. The system successfully generates merge rules, encodes input words into subword tokens, and decodes them back to the original form. This project provides a basic understanding of tokenization techniques used in modern Natural Language Processing (NLP) and Transformer-based language models.
