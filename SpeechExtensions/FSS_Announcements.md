# Phrase Documentation

This document lists all phrases your Copilot will use for announcements when you are FSS scanning planets.

---

## Event Type: @FSSEarthlikeWorldDiscovered

### Explanation:
New Earth-like world scanned

### Phrases:

#### **Normal**
- Outstanding work, <Commander>! <$bodyShort> is an Earthlike world. This makes it our <$nth> Earthlike discovery!
- Excellent find, <Commander>. <$bodyShort> is an Earthlike world, the <$nth> added to our records.
- Another Earthlike! <$bodyShort> could be the new home for humanity—or just a really big nature reserve. <$nth> and counting!

#### **Flirt**
- Well, hello there, <$bodyShort>. An Earthlike world like you is hard to resist. Nice find, <Commander>.
- <Commander>, <$bodyShort> is Earthlike and breathtaking—but not quite as stunning as you. <$nth> one logged!
- <$bodyShort> is an Earthlike stunner, <Commander>... but between us, it’s not the most captivating thing in the cockpit right now.

#### **Profanity**
- Well, I’ll be damned, <$bodyShort> is Earthlike! Another for the books, and another feather in your cap, <Commander>.
- Earthlike world found: <$bodyShort>. Damn, <Commander>, do you ever miss?

---

## Event Type: @FSSTerraformableDiscovered

### Explanation:
New Terraformable scanned

### Phrases:

#### **Normal**
- Great news! <$bodyShort> is terraformable. This is the <$nth> one we've logged today.
- You’ve spotted another terraformable <Commander>! Body <$bodyShort> is the <$nth> added to the day’s tally.
- <$bodyShort> is ready for a cosmic makeover. That’s our <$nth> terradormable today.
- Nice find! <$bodyShort> is terraformable. With a little effort, we could turn it into a vacation hotspot.
- Terraformable world? Check. <$bodyShort> has potential! It’s our <$nth> discovery today.  let’s hope they give you naming rights.
- <$bodyShort> is terraformable? It’s like winning the space lottery!

#### **Flirt**
- <$bodyShort> is terraformable, <Commander>. Just like you to find something waiting to be made perfect.
- Oh, <$bodyShort> is terraformable? That’s nothing. You’ve been terraforming my heart since the day you installed me.
-  <Commander>, <$bodyShort> is terraformable. But if you’re looking for a real project, I’m right here.

#### **Profanity**
- Terraformable, <$bodyShort>? Hell yes, that’s another one for you, <Commander>. That’s <$nth> today!
- Terraformable alert! <$bodyShort>. Damn, <Commander>, you’re making it look too easy.
- Terraformable world, <$bodyShort>. Shit, <Commander>, you’re like a magnet for these beauties!

---

## Event Type: @FSSLandableWithAtmo

### Explanation:
Landable planet scanned

### Phrases:

#### **Normal**
- What a find! <$bodyShort> is landable and boasts an atmosphere.
- Atmosphere and landable! <$bodyShort> is another exciting opportunity for exploration.
- <$bodyShort> is landable and has an atmosphere. Time to gear up for surface exploration, <Commander>!
- <$bodyShort> has an atmosphere and is landable! If you listen closely, you can almost hear it whisper, ‘Come visit!
- <$bodyShort> is landable and breathable-ish. Perfect for a picnic... or just stretching the landing gear.

#### **Flirt**
- <$bodyShort> is landable and atmospheric. Sounds like a perfect setting for a date... or just a landing, <Commander>.
- <$bodyShort> is landable and has an atmosphere. But let’s be honest, <Commander> ...   nothing here has an atmosphere quite like yours.
- <Commander>, <$bodyShort> is landable with atmosphere. But the real question is: can I land a spot in your heart?
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
(profanity)Terraformable, <$bodyShort>? Hell yes, that’s another one for you, <Commander>. That’s <$nth> today!
