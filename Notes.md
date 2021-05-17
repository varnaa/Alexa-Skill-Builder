# Alexa Skill Builder Speciality Certification

### Types of Alexa Skills
- Custom skills - Defining your own custom interaction model
- Smart Home skills -  for building a skill to communicate with smart home devices using a pre-built model.
- Flash Briefing skills - For building a skill that provides a short overview of the news or other content.
- Video skills - For providing video contents such as movies and TV shows
- Music skills - For providing audio content such as radio stations and songs
- List skills - For tracking, adding, updating or removing items from a list.
---

### Case Study - Adventure guru
This, [Github repository](https://github.com/ACloudGuru-Resources/Course_Alexa_Skill_Builder) contains all the necessary code required for this case study and is separated chapter wise.

---

### Design Patterns

- #### Adaptability
An adaptable skill is one that can understand and process what a user says appropriately.

- #### Personalization 
A personalized skill is one that remembers interactions with and information about the user.

- #### Availability 
A skill that is available is designed to guide users and keep all options open.

- #### Relatability
A skill that is relatable allows the user to feel like they are having a proper human like conversation.

---


### Steps involved in designs
- Multiple utterances.
- Account for Over-Answering.
- Request Additional Information.
- Handle Corrections.
- Plan for Errors.
- Anticipate Alexa not understanding.

---

### Personalization
- Custom welcome and returning user messages.
- Remember User Information such as name, location etc.
- Remember User Interactions such as details between requests, persist details to database, past interactions.

---

### Availability
#### Consider Response Time Limits 
- 8-Second time limit
- Ask clarifying questions

#### Effectively manage lists
- Keep options simple
- Add "paging"
- Start with top 3 best matches
- Ensure effective pacing using SSML

#### Complete Task and End Sessions
- After fulfilling a user's request, end session ( Close the mic )

---

### Relatability
- Write it how you say it
- Don't make it formal
- Use Contractions
- Vary Alexa's Responses
- Use transitions
- Use Timeline markers

---

### Types of Interaction model

#### Intents 
An action that fulfills a user's request or intention.

#### Sample utterances
A list of spoken phrases the user will say to alexa

#### Custom slots
A list of possible values

#### Dialog model
defines the steps for a multi-turn conversation between Alexa and the user.


Example: 
 
> Alexa, tell adventure guru, I want to visit Italy.

- Alexa - wake word
- Tell - Launch
- Adventure guru - Invocation name
- I want to visit - Utterance
- Italy - Custom slots