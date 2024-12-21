# Experiments in Learning

Can we use AI to learn more efficiently and effectively?

## About Me

Hi, I'm Vince, a fourth-year psychiatry resident. I've always been fascinated by how humans learn and frustrated by the inertia of our educational system. I believe AI has the potential to dramatically increase the pace and depth of human learning. This blog will serve as a journal of my experiments in using AI in medical education specifically.

## The Potential

In 1984, psychologist Benjamin Bloom described the "Two Sigma Problem": one-on-one tutoring yields outcomes two standard deviations better than classroom learning but is, for obvious reasons, impractical to scale. Recently, AI systems have emerged that can answer challenging, reasoning-based questions (not just memorization) in physics, math, coding, biology, chemistry, and more—often surpassing human experts.

While current AI systems have important limitations (particularly in completing longer-term autonomous tasks) that prevent them from being "drop-in remote workers," they excel at engaging in sophisticated question-answer conversations across diverse topics, matching the level of talented professors in their fields. By eliciting the right Socratic, tutoring-like behavior, these systems appear positioned to solve the "Two Sigma Problem," unlocking unprecedented potential for human development.

## Current Experiments

I'm currently working on several projects to explore AI's educational potential:

1. A [website](https://twosigmalearning.org) that engages users in case-based learning using medical review articles
2. A Chrome extension that instantly generates comprehensive Anki flashcards from any webpage content
3. A platform providing Socratic tutorials on psychotherapy theory, using interaction patterns distinct from the medical case-based learning approach

## Why not just use ChatGPT?

You totally could, but building bespoke wrappers has some advantages.  While these projects fundamentally rely on the same AI technology available through chatgpt.com or claude.ai, they offer distinct advantages through thoughtful UI/UX design. The value comes from things like:

1. **Hidden Chain of Thought (CoT)**: CoT prompting enhances performance in reasoning dependent tasks. I deliberately hide CoT tokens that might:
   - Reveal answers students should discover independently
   - Distract from the learning flow

2. **Enhancing Response Quality**: I employ techniques like "cleaning" articles before upload, removing irrelevant content to help the AI focus on tutorial-relevant material, potentially improving both performance and speed. I plan to experiment with many other such techniques

3. **Reduced Friction**: By handling the technical details—curating articles, optimizing prompts, selecting the best AI models for specific tasks—I lower barriers to engagement. This matters because educational tools only work if people actually use them

## Commitment to Openness

While my code is currently private (mainly to avoid silly issues like exposed API keys that I haven't checked for or other issues I haven't thought about yet), I'm committed to making it publicly accessible. My goal is to enhance human cognitive capabilities, and I welcome collaboration with others who share this vision. I have no intention of restricting access to potentially useful intellectual property.

*Note: I'm working on properly open-sourcing the code and will update when that's available.*
