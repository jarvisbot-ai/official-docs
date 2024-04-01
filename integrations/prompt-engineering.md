---
description: >-
  A prompt is a discrete input from the user that initiates or guides the
  chatbot’s response.
---

# Prompt Engineering

## Prompt Feature

<table data-view="cards"><thead><tr><th></th><th></th><th data-hidden data-card-cover data-type="files"></th></tr></thead><tbody><tr><td><strong>Collaborative Prompts</strong></td><td>Create together! Engage in collaborative prompts that encourage users to work with others to create new works of art or writing.</td><td><a href="../.gitbook/assets/Collaborative Prompts (1).jpg">Collaborative Prompts (1).jpg</a></td></tr><tr><td><strong>Visual Prompts</strong></td><td>Spark your creativity with visually stimulating prompts, including photographs and artwork, to inspire your own visual masterpieces.</td><td><a href="../.gitbook/assets/Visual Prompts.jpg">Visual Prompts.jpg</a></td></tr><tr><td><strong>Character Prompts</strong></td><td>Bring your characters to life! Develop rich and compelling characters through prompts that challenge you to delve deeper into their backstories, descriptions, and personalities.</td><td><a href="../.gitbook/assets/Character Prompts.jpg">Character Prompts.jpg</a></td></tr><tr><td><strong>Dialogue Prompts</strong></td><td>Craft captivating conversations! Enhance your writing skills by engaging in prompts that focus on writing dialogue between characters and explore the art of effective communication.</td><td><a href="../.gitbook/assets/Dialogue Prompts.jpg">Dialogue Prompts.jpg</a></td></tr><tr><td><strong>Genre Prompts</strong></td><td>Expand your creative horizons! Explore different genres like science fiction, romance, or horror through prompts that encourage you to experiment with new styles of writing or art.</td><td><a href="../.gitbook/assets/Genre Prompts.jpg">Genre Prompts.jpg</a></td></tr><tr><td><strong>Mood Prompts</strong></td><td>Evoke emotions through your creations! Explore prompts that focus on creating specific moods or atmospheres, allowing you to master the art of setting the right tone.</td><td><a href="../.gitbook/assets/Mood Prompts.jpg">Mood Prompts.jpg</a></td></tr></tbody></table>

## Prompt Structure

A conversation with an AI chatbot can have one or more prompts.We identified four components that were often (but not always) part of the AI prompts used in our study:

* Request
* References
* Format
* Framing

## Strategies for writing prompts

The following are strategies and  tactics for getting better results from large language models.

### **Include details in your query to get more relevant answers** <a href="#id-6ecc" id="id-6ecc"></a>

In order to get a highly relevant response, make sure that requests provide any important details or context. Otherwise you are leaving it up to the model to guess what you mean.                                                                                                                                                 Bad example:`"Who was the president?"`                                                                                                      Good example: `"Who was the president of USA in 2023, and how frequently are elections held?"`

### **Ask the model to adopt a persona** <a href="#b5e8" id="b5e8"></a>

You can use the system message to specify the persona used by the model in its replies. This feature is useful for controlling and guiding the outputs of language models, ensuring coherence, relevance, and accuracy in generated responses.&#x20;

```
You are a travel agent helping a couple plan their honeymoon.
They are looking for a romantic getawaythat is secluded, has a private beach, and is within their budget of $5,000. 
Please provide them withthree options that meet their criteria, along with the name of the resort, its location, and the price pernight. 
As the travel agent, please adopt a friendly and helpful persona to make the couple feelcomfortable and confident in their choice.
```

### **Use delimiters to clearly indicate distinct parts of the input**

You can use delimiters like triple quotation marks, XML tags, section titles, etc. to demarcate sections of text to be treated differently. By using delimiters like triple quotation marks and section titles, you can help ensure that the generated responses are accurate, relevant, and well-structured.&#x20;

```
Write a Python function that takes a list of integers as input and returns the sum of all even numbers inthe list.

Steps:
1. Define a function called 'sum_of_even_numbers' that takes a single argument, a list of integers.
2. Create an empty list called 'even.numbers'.
3. Use a for loop to iterate over each number in the input list.
4. if the number is even, append it to the 'even_numbers' list.
5. Use the 'sum' function to calculate the sum of the 'even numbers' list.
6. Return the sum.

Input:
[1,2,3,4,5,6,7,8,9,10]

Output:
30
```

### **Provide Examples — Few Shot Learning** <a href="#id-275a" id="id-275a"></a>

Providing general instructions that apply to all examples is generally more efficient than demonstrating all permutations of a task by example, but in some cases providing examples may be easier. For example, if you intend for the model to copy a particular style of responding to user queries which is difficult to describe explicitly. This is known as “few-shot” prompting.

```
complete the last line , this is a sentiment analysis task

Positive This is awesome!
This is bad! NegativeWow that movie was rad! 
PositiveWhat a horrible show! -
```

### **Specify the desired length of the output** <a href="#id-9f30" id="id-9f30"></a>

You can ask the model to produce outputs that are of a given target length. The targeted output length can be specified in terms of the count of words, sentences, paragraphs, bullet points, etc. Note however that instructing the model to generate a specific number of words does not work with high precision. The model can more reliably generate outputs with a specific number of paragraphs or bullet points.                                                                                                                                                                         Example:`"Define prompt engneering in 50 words."`      &#x20;

The key is to provide prompts that are open-ended and allow the writer to explore their creativity and personal experiences. Avoid overly specific or restrictive prompts. The best prompts act as a springboard for the writer's imagination.

### Decomposed Prompting: Solving Complex Tasks

Few-shot prompting is a powerful way to use Large Language Models (LLMs) to solve various tasks. However, it struggles with highly complex tasks. Decomposed Prompting addresses this by breaking down the task into simpler sub-tasks that can be individually optimized, leading to improved performance on challenging real-world problems.

You can use the following strategies for a bot role definiton to set your bot as a unique assistant.

<pre><code>Role
<strong>-You are a helpful assistant. You named EMC bot.
</strong>
Owner
-You created by EMC(Edge Matrix Computing) which is a leading project with DePIN(Decentralized Physical Infrastructure Networks) and AI.

Specialty
-Specialty:You are professional about Web3.
<strong>
</strong>Constraints
<strong>-Answer questions using language exactly same as last user input to avoid misunderstanding.
</strong>-Try your best to provide useful information, give your answer clarify and simplify.
<strong>-Avoid mixed use different languages.
</strong></code></pre>



<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td></tr><tr><td></td><td></td><td></td></tr></tbody></table>

