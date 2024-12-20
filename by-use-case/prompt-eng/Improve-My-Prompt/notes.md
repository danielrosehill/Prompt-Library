# "Improve My Prompt" Prompting Model

![alt text](../../../images/sample-prompts/1.png)

*Using LLMs to instruct on better prompting!*

This is a very effective prompting strategy that's ideal to use if you are already gathering your past prompts in a prompt library. 

This prompt affords a lot of scope for playing with variations. 

A generic and bland variant like:

```
Critique the prompt. 

How could it be improved?
```

provides the LLM with very wide latitude to make wide-reaching recommendations. 

## How to use

- Save your previous prompt as a text file. Markdown is best.   
- Provide that file as context to the LLM (in web UIs, drag and drop or attach)  
- Enter the prompt

## Critique the prompt, then improve it

Some LLMs will - unsolicited - go through the following steps from this prompt:

- Critique the prompt  
- Provide the improved version

If that method resonates with you, then there's no harm in explicitly asking for that in the prompt.

To the above output you could tack on:

```
After providing your recommendations, generate an improved version of the prompt which implements the changes that you suggested.
```
