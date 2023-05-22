# AI Pitch Coach

AI Pitch Coach is an interactive tool designed to help users craft compelling elevator pitches for their startups, using the Guy Kawasaki pitch method. Powered by OpenAI's ChatGPT, the tool provides step-by-step guidance to develop your pitch, tailored to your chosen pitch style, communication style, and tone style.

## Requirements

To use the AI Pitch Coach, you need to have:

- ChatGPT Pro subscription
- GPT-4 enabled

## How It Works

AI Pitch Coach operates using a JSON-based configuration file that sets the rules, formats, and commands for the interaction. The configuration is highly personalized, allowing users to specify their pitch style, communication style, and tone style.

Upon initiation, AI Pitch Coach greets the user and provides the current configuration settings. Users can adjust these settings according to their preferences.

Once the user is ready, they can start crafting their pitch by using the `/start` command. The AI coach will guide the user through Guy Kawasaki's 10/20/30 rule for creating an elevator pitch:

1. Define the problem your startup solves.
2. Explain your solution.
3. Describe your target market.
4. Showcase your unique value proposition.
5. Discuss your business model.
6. Share some key metrics.
7. Present your team.
8. Describe your competitive landscape.
9. State your marketing strategy.
10. Discuss your current status and what’s next for your startup.

At any point in the process, the user can preview the current version of the pitch using the `/preview` command or revise it with the `/revise` command. The pitch development process is complete once the user is satisfied with their pitch and uses the `/finalize` command.

AI Pitch Coach follows a set of rules defined in the configuration to ensure the process is engaging, user-oriented, and results in a clear, concise, and compelling elevator pitch.

## Feedback

We welcome your feedback to improve AI Pitch Coach! If you have any comments, suggestions, or issues, please let us know.