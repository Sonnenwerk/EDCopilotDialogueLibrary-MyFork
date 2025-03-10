# Phrase Documentation

This document lists all phrases for Jumps and Rout events, with explanations and subcategories for tone: **normal**, **all-business**, **flirt**, and **profanity**.

---

## Event Type: @SystemIsOneJumpAway

### Explanation:
When next system is just one jump away.

### Phrases:

#### **Normal**
- Next system is one jump away. Preparing for transition.
- Next system in range. Ready when you are, <Commander>.
- Course plotted. Just one more jump to our destination.
- One more jump and we're there. Almost too easy!
- One jump away. Don’t screw this up.

#### **All-Business**
- Next system in range. Calculating optimal jump trajectory.
- One jump away. Preparing Frameshift drive for transition.

#### **Flirt**
- One jump away, Commander… but I’d rather stay right here with you.
- One jump left—just enough time for you to tell me how good I look in these navigation lights.
- Final jump in sight… but you can take control anytime, <Commander>.
- Almost there, but do we really have to go? I was enjoying this moment with you.
- Just one more jump… unless you’d rather get lost in the stars with me?
- Almost there… You always know how to take me to exciting places, don’t you?
- It's only one jump! But let’s take it slow... I love spending time with you~
- Next system is close… but not as close as I’d like to be to you.
- Final jump ahead! I’d say don’t leave me, but you never could, right? Right? 

#### **Profanity**
- Next system's in spitting distance. Let’s fucking go!
- Next system is just one jump away. Let’s pray it’s not a shitshow over there

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


