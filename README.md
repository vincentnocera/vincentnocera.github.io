# Experiments in learning

Can we use AI to learn more efficiently and effectively?

---

## About

Hi, I'm Vince, a fourth-year psychiatry resident. I've always been fascinated by how humans learn and frustrated by the inertia of our educational system. I believe AI has the potential to dramatically increase the pace and depth of human learning.  This blog will serve as a journal of my experiments in using AI in medical education specifically. 

---

## The potential

In 1984, psychologist Benjamin Bloom described the "Two Sigma Problem": one-on-one tutoring yields outcomes two standard deviations better than classroom learning but is for obvious reasons impractical to scale.  Recently, systems have been developed that can answer challenging, reasoning-based (ie not simply memorization-based) questions in physics, math, coding, biology, chemistry etc better than can human experts.  While (as of this writing at least) such systems have important practical limitations (eg in completing longer timescale agentic tasks) which make them incapable of serving as a "drop-in remote worker", they do have the capacity to coherently engage in very advanced question-answer conversations about a broad range of topics, at the level of a talented professor in their respective field.  So long as we elicit the correct Socratic, tutoring-like behavior, these systems seem poised to solve the "Two Sigma Problem", unlocking tremendous potential for human development.

---

## Experiments

Below is a list of initial experiments I have begun to create:

1. A [website](https://twosigmalearning.org) which engages the user in case-based learning covering medical review articles I provide it. 
2. A chrome extension which, with the click of a button, creates an exhaustive set of flashcards of the content on screen, which are then downloaded for easy importing into Anki.
3. A website which provides Socratic tutorials of psychotherapy theory; I have found the ideal behavior for such tutorials to be quite different than the medically focused case-based learning mentioned above.

## How is this different from just using ChatGPT?

Fundamentally, the only difference is the UI/UX.  For the most part, you can elicit the same behavior from chatgpt.com or claude.ai with the correct prompting and scaffolding.  At times I question whether it is worthwhile to build these UXs myself, when there isn't that much daylight between what I build and the experience one can get on chatgpt.com.  However, I do still believe there are at least a few ways that these wrappers we build around the core Large Language Model (LLM) technology can both reduce friction (the importance of which is not to be underestimated!) and improve the actual quality of the educational experience (irrespective of the friction a user has to endure to reach them):

  1. Hidden Chain of Thought (CoT): It is well established that using CoT prompting can enhance the quality of LLM responses, particularly with regard to tasks that involve reasoning.  Of course, one can log on to chatgpt.com and prompt the model to engage in the kind of CoT I employ in my projects. However, I have made the strategic decision to hide much of the chain of thought reasoning the model engages in before the user sees the ultimate intended response specifically because the the hidden CoT might reveal answers that users would benefit from solving independently. Additionally, displaying the hidden CoT may distract the user.
  2. I employ other techniques to enhance the quality of LLM responses.  For example, I might "clean" an article before I upload it to my website, stripping it of text that is not relevant to the tutorial makes it easier for the LLM to focus on relevant content, potentially enhancing performance and speed.
  3. Users are very sensitive to friction: the more of it I can reduce (by for example curating articles myself, managing and iterating on prompts myself, investigating which models do which tasks best etc), the more likely the user is to engage and keep engaging in educational practice.  If you don't use it, there will be no benefit.

## Open source spirit

Currently much of my code is private, but that is mostly because I haven't thought through how to make it public and freely accesible.  Maybe that's super simple and hopefully I will take the time soon to do so but I want to make sure I am not making dumb mistakes like exposing my API keys to others etc.  My primary motivation for this work is genuine excitement at enhancing human capacities for thinking and knowing; if anyone else wants to collaborate with me on that I have no intention of witholding IP that can be useful to them.
