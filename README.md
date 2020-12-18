# AYO-orchestration

- Alternate between a Fashion chit-chat model and a FAQ replies bot
- Implement an intent dispatcher between query type and non query type messages
- Create conversation scenarios to maintain an engaging flow (e.g greetings, chit-chat, diagnosis, goodbyes)

# AYO-chitchat

Fine-tune an engaging chit-chat dialog system for Fashion using extracts from the Social Media and examples of Customer conversations.

- Set up an env to access your GPU machine
- Install ParlAI
- Download and run Blender 2.7B
- Chat with Blender
- Fine-tune the model
- Deploy the model on a conversational channel

# AYO-FAQ-replies

Fine-tune a pre-trained BERT model to solve a qa task on our FAQ self serve content.
1. as a first step, learn to map a user question to a faq question entry,
1. then learn to map a user question to a faq reply sub-section,
1. finally, make the solution robust by augmenting the set of training data with synthetic and user conversations data
