                                                              WhatsApp AI Assistant – n8n Workflow
                                                              
This is an n8n automation workflow that connects WhatsApp with an AI assistant using OpenRouter. It lets users chat with an AI through WhatsApp in a conversational way.


What It Does:
Triggers whenever a WhatsApp message is received.
Sends the message to an AI assistant (via OpenRouter).
Maintains memory of the chat for each user.
Sends the AI's response back to the user via WhatsApp.


Key Features:
WhatsApp webhook trigger (using WhatsApp Business Cloud API)
AI-powered response using OpenRouter LLMs
Chat memory using Simple Memory node
Full loop: receive → process → respond
