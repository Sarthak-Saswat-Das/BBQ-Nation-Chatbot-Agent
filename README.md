# Barbeque Nation Conversational AI Agent

This project implements a multi-modal (voice and chat) conversational AI agent for Barbeque Nation, built using Retell AI’s advanced Conversation Flow platform.

The agent guides users step-by-step through booking a table, modifying existing reservations, or cancelling bookings at Barbeque Nation outlets in Delhi and Bangalore. It is designed to provide a seamless, human-like experience across both phone calls and web chat, leveraging Retell AI’s robust voice recognition, natural language understanding, and structured state-machine logic.

## Key Features

- **Voice & Chat Support:**  
  Users can interact with the agent via phone (voice) or web chat, ensuring accessibility and convenience for all customer preferences.

- **Structured Conversational Flow:**  
  The agent uses Retell AI’s Conversation Flow to manage each step as a distinct state, including city and outlet selection, booking type, date/time, and party size.

- **Booking Management:**  
  Handles new reservations, modifications, and cancellations with clear, user-friendly prompts and dynamic transitions.

- **Natural Language Understanding:**  
  Built on Retell AI’s NLU and speech-to-text capabilities, enabling fluid, context-aware conversations in both modalities.

- **Scalable and Reliable:**  
  Designed to handle multiple concurrent calls and chats, ensuring consistent service for all users.

## How It Works

- The entire conversational logic is implemented using Retell AI’s visual flow builder, with each node representing a specific step in the booking or support process.
- The agent can be accessed via a dedicated phone number (voice) or through the chat simulation interface.
- Knowledge base documents (PDFs) are uploaded directly to the Retell AI platform for agent reference.


## Submission Links

- **Knowledge Base API Endpoints:** N/A (used Retell AI’s built-in KB by Uploading Files directly)
- **Chatbot Link:** 
- **Agent Linked Phone Number:** +1 (724) 414-2167

## Technical Documentation

- The agent’s architecture leverages a state-machine model, with each node corresponding to a step in the conversation.
- All prompts and transitions are managed within Retell AI’s platform; no external backend or custom API is used.

