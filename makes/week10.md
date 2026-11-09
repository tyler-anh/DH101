# Week 10 – Games & Play

## The Artifact
[Open in new tab](assets/The_Interview_That_Learns_You.html)

Play-in-page (below):
<iframe
  src="assets/The_Interview_That_Learns_You.html"
  width="100%"
  height="700"
  style="border: 0;"
  title="The Interview That Learns You">
</iframe>

## Process Notes
How did I make this?
- I began by choosing Concept A: The AI Interview. I wanted to explore what happens when people are evaluated by an artificial intelligence system in a situation where the outcome could affect their future opportunities.
- I developed the idea around a fictional company, Meridian Technologies, and its automated interviewer, EVAL. The applicant is interviewing for a Junior Human-AI Evaluation Analyst position. I was interested in the contradiction of applying for a job that involves evaluating AI systems while being evaluated by an AI system oneself.
-I built the interactive story using Twine 2 and Harlowe 3.3.9. Rather than creating a completely separate story for every possible decision, I used a branching-and-converging structure. The player encounters three main dilemmas, and their decisions are recorded through variables. These variables influence the AI's later responses and the final assessment.
-After building the passages, I tested the links and conditional dialogue, corrected syntax errors, and revised parts of the narrative. I also worked on the interface and developed two different endings to show how the applicant's willingness to challenge the system can affect the outcome.

What tools did you use?
- Twine 2: Used to create the interactive story, organize passages, connect choices, and export the final game as an HTML file.
- Harlowe 3.3.9: Used as the story format for implementing variables, conditional dialogue, and passage navigation.
- ChatGPT (OpenAI): Used for brainstorming, exploring dialogue variations, understanding Harlowe syntax, troubleshooting technical errors, reviewing the game's design, and conducting a simulated first-time-player evaluation.
- HTML and CSS through Twine: Used to publish the playable story and customize its visual presentation.

What decisions did you make?
One of my main decisions was to avoid presenting AI as an obviously malicious or hostile interviewer. I wanted EVAL to sound professional and reasonable because I think the more interesting question is how seemingly neutral systems can still produce questionable judgments.

I organized the interview around three decisions:
- Authenticity: Whether to acknowledge a personal failure honestly or present the experience in a more strategic, professional way.
- Privacy: Whether to provide access to previous workplace messages or protect private communications involving other people.
- Algorithmic authority: Whether to challenge the AI's preliminary evaluation or accept its judgment.

I used three variables—$candor, $privacy, and $challenge—to preserve these decisions throughout the interview. I chose two endings rather than making one ending simply represent success and the other failure. One leads to additional human review, while the other leads to a favorable automated recommendation. Both leave the player with something to question.

I also decided to keep the story relatively compact instead of creating many separate branches. This allowed me to concentrate on the consequences of a small number of decisions.

The main idea I wanted to communicate is that AI does not only evaluate people; its evaluation criteria can also influence how people behave, present themselves, and understand their own identities.

## Attribution & AI Use
- Tools used: Twine2, Harlowe 3.3.9, ChatGPT (OpenAI), HTML and CSS throguh Twine.
- AI prompts (summary):
- What AI generated:
- What you changed or decided:
