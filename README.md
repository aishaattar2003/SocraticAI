# SocraticAI – Learn to Think, Not Just Get Answers

**Building AI course project | University of Helsinki & Reaktor**

## Summary

SocraticAI is an AI-powered learning assistant that helps students solve programming problems through guided questions rather than providing immediate answers. By encouraging critical thinking and independent problem-solving, it aims to make AI a tool for learning, not just completing assignments.

## Background

AI tools are becoming increasingly common in education, especially among university students learning programming. While these tools can explain complex concepts and generate code within seconds, they also introduce a challenge: students may receive correct solutions without fully understanding how they work.

As a Software Engineering and Management student and Teaching Assistant, I have seen how important it is for students to develop their own problem-solving skills. Getting the correct answer is not always the same as understanding the reasoning behind it.

SocraticAI aims to address three main problems:

- **Overreliance on AI:** Students may become dependent on AI-generated solutions instead of developing their own reasoning.
- **Limited active learning:** Receiving complete answers can reduce opportunities to explore different approaches and learn from mistakes.
- **Lack of personalized guidance:** Students have different levels of knowledge and may need different explanations or hints.

The goal is not to replace teachers or existing AI assistants, but to explore how AI can support more active and independent learning.

## How is it used?

SocraticAI would function as an interactive learning assistant, primarily designed for university students studying programming and software development.

Instead of immediately generating a solution, the system would guide students through a conversation.

For example:

**Student:** "I don't understand why my Python loop isn't working."

**SocraticAI:** "What do you expect the loop to do, and what happens when you run it?"

**Student:** "I want it to print five numbers, but it only prints one."

**SocraticAI:** "Interesting! Can you check where your print statement is placed? What difference would indentation make?"

The assistant would gradually provide more specific hints if the student continued struggling.

Students could also request a complete explanation when necessary, ensuring the system remains helpful rather than frustrating.

The main users would be programming students, but teachers and Teaching Assistants could also use the system to support learning activities.

## Data Sources and AI Methods

SocraticAI would primarily use Natural Language Processing (NLP) and large language models (LLMs) to understand students' questions and generate appropriate responses.

The proposed system would combine several techniques:

- **Natural Language Processing:** Interpret questions, explanations, and programming-related discussions.
- **Large Language Models:** Generate context-aware questions, explanations, and hints.
- **Prompt Engineering:** Guide the AI to use a Socratic teaching approach instead of immediately providing complete solutions.
- **Classification:** Identify whether a student needs a conceptual explanation, a debugging hint, or more detailed assistance.

Initially, the project could use an existing language model rather than training a new neural network.

Potential evaluation data could include publicly available programming exercises, example student questions, and manually created learning scenarios.

A small prototype could compare two approaches:

1. A conventional AI assistant that provides direct solutions.
2. SocraticAI, which guides students through questions and progressive hints.

The two approaches could then be evaluated based on response quality, helpfulness, and their ability to encourage independent reasoning.

Any real student data would require appropriate privacy protections and consent.

## Challenges

Although SocraticAI has potential, several challenges must be considered.

**1. Learning is difficult to measure**

A student successfully completing an exercise does not necessarily mean they understand the underlying concept. Evaluating actual learning would require more than measuring correct answers.

**2. AI-generated explanations may be incorrect**

Language models can produce misleading explanations or misunderstand programming problems. Students should therefore be encouraged to verify important information.

**3. Too many questions may become frustrating**

A purely question-based approach might not suit every student or situation. The system should allow users to request clearer explanations or direct assistance when necessary.

**4. Different students have different needs**

Some students benefit from guided discovery, while others need concrete examples. The system should adapt to different experience levels.

**5. Privacy and academic integrity**

Student conversations and submitted code may contain sensitive information. The system would need clear privacy practices and should support learning without encouraging academic dishonesty.

## What Next?

The first step would be to develop a simple prototype using an existing language model and a carefully designed system prompt.

The prototype could include:

- A chat interface for programming questions.
- Different assistance levels, from small hints to detailed explanations.
- A feature that encourages students to explain their reasoning.
- A comparison between direct-answer and Socratic tutoring modes.

A future version could be evaluated through a small study comparing students' problem-solving experiences with the two approaches.

If the results are promising, SocraticAI could eventually support additional subjects beyond programming, including mathematics, software engineering, and language learning.

The long-term goal would be to explore how AI assistants can become more effective educational tools by helping students develop understanding rather than simply producing answers.

## Acknowledgments

This project idea was inspired by:

- **Building AI**, a course created by the University of Helsinki and Reaktor, which introduced the AI and machine learning concepts behind the proposed solution.
- **The Socratic method**, an educational approach that uses questioning to encourage reflection and critical thinking.
- My experiences as a Software Engineering and Management student and Teaching Assistant, which motivated my interest in AI-supported learning.

This repository presents a proposed project concept. No external code, datasets, or third-party images have been incorporated into the project.
