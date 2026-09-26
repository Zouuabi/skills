## What it does

`ping-pong` switches the conversation into a quick back-and-forth. The [agent](https://www.aihero.dev/ai-coding-dictionary/agent) answers first, makes one point per turn, and hands the ball back to you. No preamble, no recap, no menu of options.

It sets a mode for the rest of the conversation, not a fix for one message. It stays on until you say otherwise, and it only shortens the agent's talk: code, commands and file edits stay complete.

## When to reach for it

You invoke it by typing `/ping-pong`, and the agent won't reach for it on its own.

| Situation | Reach for |
| --- | --- |
| You want to think out loud with the agent in short turns (a design chat, a quick opinion, rubber-ducking) | `/ping-pong` |
| One message just lost you and you need it explained again | [wait-what](https://aihero.dev/skills-wait-what) |
| You want the agent to interview you until a plan is settled | [grill-me](https://aihero.dev/skills-grill-me) |

## The name is the mechanism

The leading word is **ping-pong**. "Be concise" names the output, and the [model](https://www.aihero.dev/ai-coding-dictionary/model) obeys it by clipping words into a telegram that is shorter and no clearer. **Ping-pong** names the rhythm of the conversation instead: one hit, then it's your turn. Short turns come from the rhythm, and each turn stays a normal sentence you can read at a glance.

The rhythm also moves control to you. The agent gives the one point that matters most; if you want the second, you ask for it.

## Common questions

**Does it make the agent's code or edits shorter too?**
No. Only what the agent says to you gets short. The work it does stays complete.

**How do I turn it off?**
Say so in plain words ("stop ping-pong", "give me the full version"). The mode lasts until you do.

## It's working if

- Most replies fit on your screen without scrolling.
- The first sentence answers your question.
- Replies read as plain sentences, not fragments.
- You steer the depth by asking follow-ups, instead of skimming past parts you didn't need.

## Where it fits

`ping-pong` is a reach-for-it-anytime standalone, for casual discussion in any project, code or not. Its neighbour is [wait-what](https://aihero.dev/skills-wait-what), because `wait-what` repairs one message after the fact, while `ping-pong` sets the pace for the rest of the conversation. For the whole map, [ask-matt](https://aihero.dev/skills-ask-matt) routes you.
