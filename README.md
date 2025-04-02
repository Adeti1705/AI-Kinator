AI-Kinator: A Reverse Akinator Game

Try it out
[www.reddit.com](https://www.reddit.com/r/Reverse_Akinator/)

🌟 Inspiration
We wanted to build a fun, interactive puzzle game for the HACK-REDDIT 2025 hackathon. After rejecting several ideas, inspiration struck when YouTube randomly recommended an old Akinator video.
What if, instead of answering, the player asks questions to guess a secret entity?

And just like that, AI-Kinator was born!

🕹️ What It Does
AI-Kinator flips Akinator on its head! Instead of the AI guessing, you ask yes/no questions to figure out the secret entity. The challenge? Can you outsmart the AI before running out of guesses?

🏗️ How We Built It
We used:
- Google Gemini API for processing user questions.
- Devvit (Blockposts) for simple Reddit integration.

We initially considered a Web UI, but due to time constraints, we simply stuck with blockposts for a smoother experience.

🚧 Challenges We Ran Into
- No Fixed Decision Tree: Unlike Akinator, our game required AI to handle unstructured guesses dynamically.
- Finding a Free AI API: Being broke college students, paid options were out, and Reddit limits LLMs. We settled on Google Gemini since it’s free (for now at least).
- Devvit’s Limitations: Web UI was tricky, so we kept it simple with blockposts.

🏆 Accomplishments
- Built a fully functional, engaging game.
- Implemented AI-driven responses dynamically.
- Worked around budget and Devvit constraints to deliver a fun experience.

📚 What We Learned
- AI-driven guessing is harder than static decision trees.
- Free tools can work if you get creative (shoutout to Google Gemini).
- Simplicity wins—blockposts made development smoother.

🚀 What’s Next?
- More themes & categories
- Multiplayer mode
- Better AI response tuning

We hope Redditors enjoy playing AI-Kinator as much as we enjoyed building it! 🎉

Built With: 
- Devvit
- Gemini API
- Typescript

