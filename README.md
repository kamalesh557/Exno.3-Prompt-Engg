# Exno.3-Scenario-Based Report Development Utilizing Diverse Prompting Techniques

DATE: 29-08-2025

REGISTER NUMBER: 212223030021



Aim

To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should efficiently handle various customer queries while maintaining a conversational and user-friendly tone. In this experiment, different prompting techniques are employed to guide the chatbot’s development, ranging from task-oriented prompts to persona-driven and reflective prompts.



Algorithm

1. Direct Instruction Prompting
	•	Objective: Provide concise replies to customer inquiries.
	•	Prompt Pattern:
“When a customer asks for the status of their order, reply with: ‘Your order is currently being processed and will be delivered by [date].’”

2. Contextual Prompting
	•	Objective: Use previous interactions to provide context-aware responses.

	•	Prompt Pattern:
“If the customer previously mentioned that they haven’t received their order, say: ‘I see that you mentioned your order hasn’t arrived yet. Let me check the details for you and get back shortly.”

4. Persona-Based Prompting
	•	Objective: Make chatbot interactions more engaging by assigning it a persona.
	•	Prompt Pattern:
“Pretend you are a friendly, helpful customer service representative. Use a conversational tone, such as ‘Hey there! I’m here to help with any questions you might have. Let’s get your issue sorted!

5. Few-Shot Prompting
	•	Objective: Provide examples to help the AI generalise responses.
	•	Prompt Pattern:
“Here are some examples of how to handle technical questions:
	•	‘My phone isn’t charging.’ → ‘Have you tried using a different cable? If that doesn’t work, it may be an issue with the port.’
	•	‘The screen is flickering.’ → ‘It sounds like a display issue. Have you tried restarting the device?’
Now, respond to: ‘My app keeps crashing.’”

6. Chain of Thought Prompting
	•	Objective: Use step-by-step reasoning for complex issues.
Prompt Pattern: “When a customer reports their laptop overheating, guide them through the following steps: Ask if they are using the laptop on a soft surface. Suggest moving it to a flat, hard surface. Ask if vents are clean. Recommend restarting. Now, solve: ‘My laptop fan is making a loud noise.’”

7. Instruction with Constraints
	•	Objective: Ensure responses are clear, concise, and within constraints.
Prompt Pattern: “Respond to order inquiries in no more than 50 words and avoid using technical jargon. For example: ‘Your order is on the way and should arrive by [date]. Feel free to reach out if you need anything else.’”

8. Reflective Prompting
	•	Objective: Reduce misunderstandings by reflecting the customer’s query.
	•	Prompt Pattern:
“When a customer asks for help, first reflect their question. For example, if they ask, ‘How can I reset my password?’ respond with, ‘You’re asking how to reset your password, correct? Here’s how you can do it.’”

Comparison Table of Prompting Techniques

| **Prompting Technique**       | **Objective**                          | **Example**                                           | **Advantage**                         |
|--------------------------------|----------------------------------------|-------------------------------------------------------|---------------------------------------|
| Direct Instruction             | Give concise replies                   | “Your order is being processed and will be delivered by [date].” | Quick and straightforward response    |
| Contextual Prompting           | Use past interactions for better replies | “I see that you mentioned your order hasn’t arrived yet…” | Personalised, context-aware support   |
| Persona-Based Prompting        | Adopt a friendly/helpful personality   | “Hey there! I’m here to help…”                        | Builds customer trust and engagement  |
| Few-Shot Prompting             | Learn from examples to handle queries  | “My phone isn’t charging → Try a different cable.”     | Helps AI generalise across similar cases |
| Chain of Thought Prompting     | Break down complex issues step by step | Guiding steps for laptop overheating                  | Structured, logical troubleshooting   |
| Instruction with Constraints   | Respond with specific limits           | Max 50 words, no jargon                               | Ensures clarity and brevity            |
| Reflective Prompting           | Repeat query before answering          | “You’re asking how to reset your password, correct?”   | Reduces misunderstandings             |


Result

The various types of prompts (Direct, Contextual, Persona-Based, Few-Shot, Chain of Thought, Instruction with Constraints, and Reflective) were successfully executed and demonstrated.
