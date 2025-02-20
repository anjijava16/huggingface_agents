# huggingface_agents
Huggingface agents


## Understanding Agents

1. What is an Agent, and how does it work?
2. How do Agents make decisions using reasoning and planning?

## The Role of LLMs (Large Language Models) in Agents

1. How LLMs serve as the “brain” behind an Agent.
2. How LLMs structure conversations via the Messages system.

## Tools and Actions
1. How Agents use external tools to interact with the environment.
2. How to build and integrate tools for your Agent.

## The Agent Workflow:

Think → Act → Observe.



![image](https://github.com/user-attachments/assets/40564494-6798-4030-acec-71c062f34694)




An Agent is a system that leverages an AI model to interact with its environment in order to achieve a user-defined objective. It combines reasoning, planning, and the execution of actions (often via external tools) to fulfill tasks.

## Think of the Agent as having two main parts:

### The Brain (AI Model)

This is where all the thinking happens. The AI model handles reasoning and planning. It decides which Actions to take based on the situation.

### The Body (Capabilities and Tools)

This part represents everything the Agent is equipped to do.

The scope of possible actions depends on what the agent has been equipped with. For example, because humans lack wings, they can’t perform the “fly” Action, but they can execute Actions like “walk”, “run” ,“jump”, “grab”, and so on.

### What type of AI Models do we use for Agents?

The most common AI model found in Agents is an LLM (Large Language Model), which takes Text as an input and outputs Text as well.

Well known examples are GPT4 from OpenAI, LLama from Meta, Gemini from Google, etc. These models have been trained on a vast amount of text and are able to generalize well. We 

will learn more about LLMs in the next section.

## Agents flow
1. Implement and modify the Thought → Act → Observe cycle to create robust and maintainable Function-calling workflows.



## To summarize, an Agent is a system that uses an AI Model (typically an LLM) as its core reasoning engine, to:

1. Understand natural language: Interpret and respond to human instructions in a meaningful way.

2. Reason and plan: Analyze information, make decisions, and devise strategies to solve problems.

3. Interact with its environment: Gather information, take actions, and observe the results of those actions.

Now that you have a solid grasp of what Agents are, let’s reinforce your understanding with a short, ungraded quiz. After that, we’ll dive into the “Agent’s brain”: the LLMs.


# References 
1. https://github.com/huggingface/agents-course/tree/main
2. https://www.youtube.com/watch?v=iLVyYDbdSmM&t=981s
