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
- **Chatbot Link:** https://agency-zu7o11.chat-dash.com/prototype/6829d54a079fdb17d516ec05   (Configured Retell AI Agent to ChatDash for a prototype Link)
- **Agent Linked Phone Number:** +1 (724) 414-2167


## Retell AI Identifiers

- **Agent ID:** `agent_5dcff38c33a28144f38945686d`
- **Conversation Flow ID:** `conversation_flow_b4fbdbd6b0fd`
- **Knowledge Base IDs:**
  - `knowledge_base_dc1750652380a5f0`
  - `knowledge_base_90555ff7f7d1e619`
  - `knowledge_base_967e560ad8ea1e4f`
- **API Key:** `key_1b16a6eb498744bf1bf2ac43a358`


## Technical Documentation

- The agent’s architecture leverages a state-machine model, with each node corresponding to a step in the conversation.
- All prompts and transitions are managed within Retell AI’s platform; no external backend or custom API is used.

