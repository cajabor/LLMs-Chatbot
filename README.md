# Conversational AI Chatbot

This project implements a chatbot using the **BlenderBot 400M** model from Facebook. The chatbot maintains conversation history and generates responses based on user input, creating a more context-aware interaction.

## Watch a Demo
[Demo](#)  <!-- Replace with actual demo link when available -->

## Technical Challenges Solved
- **Context-Aware Responses**: The chatbot retains conversation history, allowing it to generate contextually relevant responses rather than treating each input as an isolated query.
- **Efficient Tokenization and Generation**: Utilizes Facebook's **BlenderBot 400M** for text generation, efficiently encoding conversation history and user input for coherent responses.
- **Dynamic Interaction**: A real-time, command-line-based chatbot capable of sustaining multi-turn conversations with minimal lag.

## Features
- **Conversational Memory**: The chatbot retains context throughout interactions to provide more natural responses.
- **Pretrained Model Integration**: Uses **Facebook’s BlenderBot 400M** for high-quality conversational AI.
- **Seamless Execution**: Runs in a simple command-line interface with real-time response generation.

## Installation
Ensure you have the necessary dependencies installed:

```bash
python3 -m pip install transformers==4.30.2 torch
