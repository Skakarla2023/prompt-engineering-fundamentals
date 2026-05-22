# Prompt Engineering

- A prompt is a specific instruction or question or text input given to Artificial Intelligence, to direct its output.
- It is like a message or instruction that tells the AI what to create, how to behave and which context to consider.


<img width="977" height="383" alt="image" src="https://github.com/user-attachments/assets/28eb2f8b-bec5-41ab-b750-2a377aafa50f" />

- One needs to improve the clarity and specificity of the prompts to ensure that we precisely get the response we need.

<img width="746" height="421" alt="image" src="https://github.com/user-attachments/assets/391f8344-ef20-4d49-b006-048d829088ee" />


## Core Principles of Prompt Engineering

### 1. Be Specific

- Instead of giving a single line prompts or simple prompts, the prompt should be detailed enough to explain the context.

**Eg:**

Weak:
> Write an essay about AI

Strong:
> Write a 200 word essay about AI, focusing on its uses, applications, pros and cons , and its applications in real life. Use simple language , include examples in the end and end end with some suggestions of how to use AI.

### 2. Give AI a role

- Assigning AI a role improves consistency, it does not give biased responses.

**Eg:** 

> You are a senior cybersecurity analyst explaining risks to a non-technical executive team.


### 3. Add Constraints

- Constraints reduce ambiguity.

**Eg:**

> Use under 200 words to explain the impact of AI on agriculture.

### 4. Provide Examples

- By providing examples, models imitate the patterns in the examples pretty well.

**Eg:**

> Input: “App crashes on launch”
> Output: “Troubleshooting → Stability”


### 5. Give output format

- Providing a specific format helps us to get the output that we desire.

**Eg:**

> return the answer in a step by step manner.

### 6. Break complex tasks into steps

- This makes it simpler for the AI to understand the problem at different levels.

**Eg:**

Weak:
> Build a study plan

Strong:
1. Analyze the study pattern
2. Identify gaps
3. Suggest for study hours
4. Create a study plan


### 7. Ask for reasoning carefully

For difficult tasks:

> Explain your reasoning step-by-step.

But for production systems, concise reasoning is often better:

> Briefly justify each recommendation.
