# AI Concepts

## What is an AI model

An AI model is a computer program that learns patterns from large amount of data and uses what it learned to produce an output.

For example:

```
Large Amount of Data → AI Model → Learn Patterns → Produces Output
```
The output could be:

- Text: answer a question or write an article
- Images: create an image from a description
- Audio: convert speech to text
- Speech: generate human-like speech
- Predictions: predict something based on historical data
- Video - generate or transform video

![AIModels.png](../images/AIModels.png)

## What are there different AI models?
There isn't **one AI model that is good at everything**

Different models are designed for different inputs and outputs

Think of it like this:

| Input        | AI Model                 | Output          |
| ------------ | ------------------------ | --------------- |
| Text         | ChatGPT / LLM            | Text            |
| Text         | Image Generation Model   | Image           |
| Image        | Vision Model             | Text/Analysis   |
| Audio        | Speech Recognition Model | Text            |
| Text         | Text-to-Speech Model     | Audio           |
| Text + Image | Multimodal Model         | Text/Image/etc. |

#### Example: ChatGPT

When you type:

> "Explain Spring AI in simple words"

The flow is 

```
Your text → AI model → Understands patterns/context → Generates → Text Response
```

So ChatGPT is primarily interacting with you through **text input → text output**, although modern models can support other modalities too.

#### But AI isn't only about ChatGPT
The passage is also pointing out that generative AI existed in many forms before ChatGPT became popular.

For example:

                  AI Models
                     │
       ┌─────────────┼─────────────┐
       ↓             ↓             ↓
    Text Models   Image Models   Audio Models
       │             │             │
     ChatGPT      Midjourney    Speech Models
     Stable
     Diffusion

For example, with an image-generation model, you could provide:

> "A futuristic city in the year 2050."

And the model generates:

```
Text Prompt → Image Generation Model → Generated Image
```

**AI model = A trained algorithm that takes some type of input, processes what it has learned, and produces an output.**