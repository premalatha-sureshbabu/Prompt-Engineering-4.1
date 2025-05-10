# Prompt-Engineering-4.1
# EXP 4 Scenario-Based Report Development Utilizing Diverse Prompting Techniques- Lab Scenario: Smart Health Assistant System
# Description:
To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts. Case study 2 with Comparative Analysis Prompt, Comparative Analysis Prompt and Prompt Size Limitations
## Background:
You are part of a development team working on an AI-based Smart Health Assistant named "MediGuide" that assists elderly patients in managing chronic diseases like diabetes, hypertension, and arthritis. The assistant must provide tailored health advice, medication reminders, daily tips, and emotional support through natural language conversations.

## Objective:
Develop a scenario-based report that demonstrates how diverse prompting techniques (zero-shot, few-shot, chain-of-thought, role-based, and multi-modal prompts) can be used to optimize MediGuide’s responses in different use cases.

## Algorithm:
1.Collect user preferences: destination, duration, interests, and budget.

2.Apply different prompt techniques: zero-shot, role-based, few-shot, chain-of-thought.

3.Generate AI outputs for personalized travel plans.

4.Compare responses from ChatGPT and Gemini.

5.Analyze creativity, contextual relevance, and user experience.

6.Summarize findings.

### Use Case
Travel Planner Use Case: AI-driven Travel Recommendations and Itinerary Generation

### Objective:
To compare the effectiveness of three distinct prompt types—
->Straightforward Prompts
->Tabular Format Prompting,
->Missing Word Prompting
—across two different AI platforms (e.g., ChatGPT and Claude) for generating travel recommendations, personalized itineraries, and activity suggestions.

AI Tools Used:
->ChatGPT (GPT-4)

->Claude (Anthropic AI)

Prompts Used:
### 1. Straightforward Prompts:
Objective: Directly ask the AI to provide a travel itinerary based on provided preferences and destination.

Prompt Example:
"I am planning a trip to Paris for 5 days and I enjoy historical sites, museums, and local cuisine. Can you recommend a travel itinerary for me?"

### ChatGPT Output:
"Here’s a suggested 5-day itinerary for Paris:

Day 1: Explore the Eiffel Tower and Champ de Mars park. Visit the Louvre Museum in the afternoon.

Day 2: Visit Notre-Dame Cathedral and Sainte-Chapelle. Enjoy a walking tour along Seine River.

Day 3: Spend the day at the Palace of Versailles, including a tour of the gardens.

Day 4: Explore Montmartre, visit Sacré-Cœur Basilica and Moulin Rouge.

Day 5: Visit the Musée d'Orsay and enjoy dinner at a local French bistro."

### Claude Output:
"Here’s a recommended 5-day itinerary for Paris:

Day 1: Visit Eiffel Tower and Louvre Museum. Have dinner at Le Jules Verne on the Eiffel Tower.

Day 2: Explore Musée d'Orsay in the morning, then visit Montmartre for local art and cafes.

Day 3: Day trip to Versailles Palace and gardens.

Day 4: Visit Notre-Dame Cathedral and Latin Quarter for a historical walk.

Day 5: Spend the day exploring Le Marais district, shop at local boutiques, and end with a Seine River cruise."

### Evaluation:
| **Criteria**        | **ChatGPT**                                                                | **Claude**                                                                              |
| ------------------- | -------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- |
| **Accuracy**        | Suggested relevant and iconic Parisian landmarks and activities.           | Suggested relevant landmarks, with additional focus on dining and shopping experiences. |
| **Coherence**       | Structured and balanced itinerary with historical and cultural highlights. | Structured itinerary, with a good mix of activities and dining suggestions.             |
| **Simplicity**      | Easy to follow itinerary with sufficient detail.                           | Detailed itinerary, but more options could be overwhelming for some users.              |
| **User Experience** | The itinerary was straightforward and easy for a general audience.         | Response included more personalized details but was more complex in nature.             |


### Final Summary:
->ChatGPT provided a clear, simple, and user-friendly itinerary suitable for general travelers.

->Claude provided a more detailed itinerary, with suggestions for dining and local experiences, making it more suited for travelers looking for an in-depth experience.

### 2. Tabular Format Prompting:
Objective: Present information in a tabular format for clarity, then ask the AI to analyze and generate a travel itinerary.

Prompt Example:
"Below is a table with the traveler's preferences and constraints. Based on this, can you recommend a 5-day itinerary for a trip to Rome?

| Preference         | Details                                    |
| ------------------ | ------------------------------------------ |
| Destination        | Rome                                       |
| Duration           | 5 days                                     |
| Interests          | History, Museums, Food, Architecture       |
| Budget             | Moderate                                   |
| Travel Constraints | No walking tours longer than 2 hours daily |


### ChatGPT Output:
"Here’s a 5-day itinerary for Rome:

Day 1: Visit Colosseum and Roman Forum (2 hours). Lunch at a traditional trattoria. Evening visit to Pantheon.

Day 2: Explore the Vatican Museums and St. Peter’s Basilica (with short breaks). Enjoy dinner in the Trastevere district.

Day 3: Visit Borghese Gallery and Villa Borghese Gardens. Relax and enjoy Piazza Navona in the evening.

Day 4: Explore Piazza del Popolo, Spanish Steps, and Trevi Fountain. Have dinner at a rooftop restaurant.

Day 5: Day trip to Tivoli Gardens with lunch at a local vineyard."

### Claude Output:
"Here’s a suggested 5-day itinerary for Rome:

Day 1: Visit the Colosseum, Roman Forum, and Palatine Hill (break after each location). Lunch at Piazza della Rotonda. Evening stroll near the Trevi Fountain.

Day 2: Spend the day at the Vatican Museums and St. Peter's Basilica. Short walk through Piazza del Popolo.

Day 3: Explore Villa Borghese, and enjoy Borghese Gallery. Lunch in Trastevere followed by an afternoon at Piazza Navona.

Day 4: Visit the Pantheon, then head to Campo de' Fiori and explore the Spanish Steps.

Day 5: Visit Castel Sant'Angelo and take a day trip to Ostia Antica for ancient ruins."

### Evaluation:
| **Criteria**        | **ChatGPT**                                                                                   | **Claude**                                                                             |
| ------------------- | --------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| **Accuracy**        | Identified relevant attractions and activities in Rome, with sufficient details for each day. | Identified major attractions with slightly more focus on exploring less crowded areas. |
| **Clarity**         | Clear and straightforward itinerary.                                                          | Slightly more detailed, could be overwhelming for users looking for simplicity.        |
| **Simplicity**      | Suitable for travelers looking for a concise plan.                                            | Ideal for those who prefer more variety in their daily plans.                          |
| **User Experience** | Simple to follow, focused on historical and cultural attractions.                             | More comprehensive, included a day trip and suggested quieter locations.               |


### Final Summary:
->ChatGPT provided a concise and easy-to-follow itinerary, ideal for travelers who prefer simplicity.

->Claude offered a more detailed, varied itinerary with a mix of well-known and less-visited locations, which could appeal to more seasoned travelers.

### 3. Missing Word Prompting:
Objective: Provide a partially completed sentence or data and ask the AI to fill in the missing words or information.

Prompt Example:
"The traveler is interested in historical landmarks, museums, and good food in Rome. Based on these preferences, the ideal destination for a 5-day itinerary is _____. Fill in the missing destination and suggest an itinerary."

### ChatGPT Output:
"The ideal destination is Rome. Here’s a suggested itinerary:

Day 1: Visit Colosseum, Roman Forum, and Pantheon.

Day 2: Explore Vatican Museums and St. Peter’s Basilica.

Day 3: Visit Borghese Gallery and enjoy the Villa Borghese Gardens.

Day 4: Explore Trevi Fountain, Spanish Steps, and Piazza del Popolo.

Day 5: Day trip to Tivoli Gardens."

### Claude Output:
"The ideal destination is Rome. Here’s a suggested itinerary:

Day 1: Visit Colosseum, Roman Forum, and Palatine Hill.

Day 2: Explore Vatican Museums and St. Peter’s Basilica.

Day 3: Discover Villa Borghese and take a relaxing walk through Piazza Navona.

Day 4: Visit Pantheon, Campo de' Fiori, and enjoy a leisurely lunch at Trastevere.

Day 5: Take a trip to Ostia Antica and enjoy the archaeological sites."

### Evaluation:
| **Criteria**     | **ChatGPT**                                                                                                    | **Claude**                                                                                                     |
| ---------------- | -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| **Accuracy**     | Both outputs correctly identified Rome and provided relevant itinerary options.                                | Both outputs correctly identified Rome and provided a well-balanced itinerary.                                 |
| **Completeness** | Both responses provided a comprehensive 5-day itinerary, with no critical information omitted.                 | Both responses provided a comprehensive 5-day itinerary, with a variety of attractions.                        |
| **Simplicity**   | ChatGPT’s output was clearer and simpler for general users.                                                    | Claude’s output offered more variety, suitable for travelers looking for a wider range of activities.          |
| **Coherence**    | Both responses were coherent and logically structured; however, Claude’s included a more diverse mix of sites. | Both responses were coherent and logically structured; however, Claude’s included a more diverse mix of sites. |


### Conclusion:
->ChatGPT delivered a simple and straightforward itinerary, ideal for general audiences.

->Claude provided a more diverse and varied itinerary, with additional options for a richer experience.

### Final Comparative Evaluation:
| **Prompt Type**              | **Best Performing Platform** | **Strengths**                                     | **Weaknesses**                                      |
| ---------------------------- | ---------------------------- | ------------------------------------------------- | --------------------------------------------------- |
| **Straightforward Prompts**  | **Tie** (ChatGPT & Claude)   | Both platforms provided accurate recommendations. | Claude’s output was slightly more detailed.         |
| **Tabular Format Prompting** | **ChatGPT**                  | Clear and concise recommendations.                | Claude provided more diverse activity options.      |
| **Missing Word Prompting**   | **ChatGPT**                  | Clear and straightforward output.                 | Claude’s suggestions were more varied and detailed. |


### Final Conclusion:
->ChatGPT performed well in terms of clarity and simplicity, making it ideal for general travelers who prefer a concise and easy-to-follow plan.

->Claude provided more detailed, varied suggestions, which would benefit travelers looking for a richer experience or seeking specific, off-the-beaten-path locations.
# Result:
Thus the Prompts were exected succcessfully.




