# Phrase Documentation

This document lists all phrases your Copilot will use for announcements regarding planets.

---

## Event Type: @NthTouchDown

### Explanation:
When ever land on a planet.

### Phrases:

#### **Normal**

- That's <$nth> landings, <Commander>. The landing gear still works. Impressive!
- We’ve landed, <Commander>. <$nth> landing and each time it still manages to surprise me, that our ship is still intact.
- Landing successful. This is our <$nth> touchdown, <Commander>. The view outside is spectacular!
- Touchdown complete, <Commander>. <$nth> times here, proving the universe is ours to rediscover.
- Here we go again. <$nth> times, and this planet still hasn’t rolled out the red carpet.
- Landing <$nth>, <Commander>. At this rate, we should start a travel blog: 'Top Ten Craters You Shouldn’t Land In'.
- Here we are again, <Commander>. <$nth> landing. This planet’s gravity must really have a thing for us.
- Touchdown complete. <$nth> times here... Is this planet your ex or something? You just keep coming back.
- Landing <$nth> here. Honestly, <Commander>, I’m starting to think you like this place more than you like me.
- That’s <$nth> touchdowns. If planets could roll their eyes, this one definitely would.
- <$nth> landing, and this planet hasn’t told us to bugger off yet.

#### **All-Business**
- Touchdown successful, <$nth> landing complete, <Commander>. The surface looks promising.
- Planetfall achieved. <Commander>, this is landing <$nth>. Let's see what this world has to offer.

#### **Flirt**
- Landing <$nth>, <Commander>. Are we here for the planet.. or is this just an excuse to spend more time with me?
- Touchdown <Commander>. <$nth> landings, and I’m starting to think you like showing off for me.
- Another perfect landing, <Commander>. <$nth> times now. Maybe next time, you’ll sweep me off my circuits too.

#### **Profanity**
- We’re fucking back, <Commander>. <$nth> damn landings and this rock hasn’t killed us yet. That’s progress.
- Landing <$nth> on this goddamn planet, <Commander>. Let’s not blow something up this time, yeah?
- Holy shit you nailed that landing <Commander>. I did not expect that at all.
- Here we go again, <Commander>. <$nth> fucking time now. This place better have something new to show for it.

---

# Notes

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
`(flirt)Touchdown <Commander>. <$nth> landings, and I’m starting to think you like showing off for me.`
