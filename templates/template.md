# Phrase Documentation

This document lists all phrases categorized by event type, with explanations and subcategories for tone: **normal**, **all-business**, **flirt**, and **profanity**.

---

## Event Type: [Event Name]

### Explanation:
[Brief explanation of what this event type represents and when it is triggered.]

### Phrases:

#### **Normal**
- "Example phrase 1 for normal tone."
- "Example phrase 2 for normal tone."
- "Example phrase 3 for normal tone."

#### **All-Business**
- "Example phrase 1 for all-business tone."
- "Example phrase 2 for all-business tone."
- "Example phrase 3 for all-business tone."

#### **Flirt**
- "Example phrase 1 for flirt tone."
- "Example phrase 2 for flirt tone."
- "Example phrase 3 for flirt tone."

#### **Profanity**
- "Example phrase 1 for profanity tone."
- "Example phrase 2 for profanity tone."
- "Example phrase 3 for profanity tone."

---

## Event Type: [Next Event Name]

### Explanation:
[Brief explanation of what this event type represents and when it is triggered.]

### Phrases:

#### **Normal**
- "Example phrase 1 for normal tone."
- "Example phrase 2 for normal tone."
- "Example phrase 3 for normal tone."

#### **All-Business**
- "Example phrase 1 for all-business tone."
- "Example phrase 2 for all-business tone."
- "Example phrase 3 for all-business tone."

#### **Flirt**
- "Example phrase 1 for flirt tone."
- "Example phrase 2 for flirt tone."
- "Example phrase 3 for flirt tone."

#### **Profanity**
- "Example phrase 1 for profanity tone."
- "Example phrase 2 for profanity tone."
- "Example phrase 3 for profanity tone."

---

# Notes

[Add any additional notes or instructions here, such as placeholders like `<Commander>` or `<$nth>` and their usage.]

You can add these phrases to your `EDCoPilot.SpeechExtensions.Custom.txt` in `\EDCoPilot\User custom files`.
The format is a @event-type assigned to a particular event in EDCoPilot, followed by a list of sentences you want to be selected from when the event is triggered
The correct format looks like this:  
@EventType <!-- replace this with the event type.  
REPLACE <!-- only put REPLACE here if you DONT want to use the build in phrases.  
phrase <!-- phrases you want to use   
phrase2 <!-- phrases you want to use   

Before each sentence you can add the following 'tags'. These will detemine whether the phrase is used based on your AI-Personality Settings  
(profanity) = dont consider picking this sentence unless Profanity mode is on  
(dislikesmining) = only add this sentence to the candidate list for random selection if Dislikes Mining preference is on  
(flirt) = only add this sentence to the candidate list if the Flirt mode is on  
(allbusiness) = if All Business mode is on, ONLY select items in the list that are flagged as (allbusiness)  

Example:  
[Add an example from this file here]  
