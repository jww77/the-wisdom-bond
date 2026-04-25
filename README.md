# The Wisdom Bond

**An adaptive advisory agent that creates a living, evolving relationship between the human and the AI.**

The Wisdom Bond is not a chatbot with preset answers. It is a personal consultant that learns who you are as a decision-maker through conversation, reflects that understanding back visually, and calibrates its counsel based on the patterns it discovers.

## What Makes This Different

Traditional AI advisors treat every user the same. The Wisdom Bond builds a **Context Portrait** of you in real time. As you share decisions and dilemmas, it tracks your decision traits (analytical, intuitive, risk-open, people-first), surfaces your emerging values, and logs behavioral patterns it notices. This portrait feeds back into every response, so the advice you receive becomes more personal with every exchange.

## Three Core Systems

### 1. Context Portrait
As you share decisions and dilemmas, the agent builds a real-time understanding of your values, recurring tensions, decision patterns, and growth edges. This lives in the conversation itself and gets richer with every exchange.

### 2. Visual Bond Map
A dynamic visualization that evolves as the relationship deepens. It maps your core values, decision patterns, emotional tendencies, and blind spots into a living constellation diagram that changes shape as the agent learns more about you.

### 3. Adaptive Counsel
The agent calibrates its approach based on what it learns about you: when to push, when to hold space, when to challenge, when to affirm. It names the patterns it sees across your decisions.

## Five Advisory Modes

| Mode | Purpose |
|------|---------|
| **Counsel** | Balanced, multi-perspective advisory with alternative viewpoints |
| **Challenge** | Surfaces blind spots and stress-tests your assumptions |
| **Mirror** | Reflects your patterns, emotions, and decision tendencies back to you |
| **Strategic** | Maps systems, incentives, trade-offs, and the move with the most optionality |
| **Somatic** | Checks in with your body and instincts, distinguishes fear from wisdom |

## Getting Started

### Prerequisites

You need an Anthropic API key. Get one at [console.anthropic.com/settings/keys](https://console.anthropic.com/settings/keys).

### Running

1. Download `the-wisdom-bond.html`
2. Open it in any modern browser (Chrome, Firefox, Safari, Edge)
3. Enter your name and API key on the setup screen
4. Start sharing what you are sitting with

No server. No installation. No dependencies. Everything runs in your browser.

### Sharing with Others

Send the single HTML file to anyone. Each person enters their own API key and builds their own private bond. Nothing is stored beyond the browser session.

## How It Works

The Wisdom Bond uses Claude (Sonnet) through the Anthropic API. Each response includes a structured analysis block that extracts:

- **Decision trait scores** (0-10 across four dimensions)
- **Values** expressed in the message
- **Patterns** the agent notices about your behavior
- **Bond notes** capturing what the agent learned about you

This data feeds the Bond Map panel in real time, creating a visual fingerprint of how you make decisions.

## Bond Map Components

- **Constellation Canvas**: Trait nodes radiate outward as they strengthen. Value nodes orbit based on frequency. Connection lines form between traits and center.
- **Bond Strength Ring**: Composite metric (0-100%) that grows through five stages: Beginning, Forming, Deepening, Connected, Attuned.
- **Decision Traits**: Four bar charts tracking your analytical, intuitive, risk-open, and people-first tendencies.
- **Emerging Values**: A cloud of value words that grow stronger with repetition.
- **Pattern Journal**: Color-coded log of patterns, growth edges, tensions, and reflection points.

## Privacy

- Your API key is held only in the browser tab's memory
- No data is sent anywhere except directly to the Anthropic API
- Nothing persists after you close the tab
- Each user's bond is entirely private

## Technology

- Single-file HTML/CSS/JavaScript application
- Anthropic Messages API (Claude Sonnet)
- Canvas API for bond visualization
- No frameworks, no build step, no server

## License

MIT License. Use it, share it, build on it.

## Created By

Built with Claude Opus 4.6 by Anthropic.
