# LearnWithAI
AI Tools &amp; Pipeline to create &amp; manage a full-blown course from an instructor video lesson


# UPoD AI
## Existing Relevant Tools

We've identified several examples, both paid and open-source, that can elevate coding skills:

* __Copilot__
* __Codellama__
* __Starcoder__
* __SQLCoder__

However, we require a more advanced solution that provides explanations and constraints, rather than simply writing code. This leads us to consider fine-tuning options for an LLM model.

## Fine-Tuning Options

We can either:

1. **Fine-tune**: Use paid services like Modal or Vast AI to fine-tune our open-source LLM model with a specific style and instructions.
2. Use __OpenAI__ fine-tuning service.

## Potential Alternative: Prompt Tuning (To be elaborated...)
Prompt tuning can also involve using a small trainable model to encode the text prompt and generate task-specific virtual tokens. These tokens are pre-appended to the prompt and passed to the large language model. This parameter-efficient tuning technique allows for more nuanced and tailored responses from the generative AI model, enhancing its applicability and effectiveness across a variety of tasks.

## Vector Database and AI Agents

To structure our RAG (Retrieval Augmented Generation), we can create a vector database that feeds on course content, books, examples, etc. We'll need to decide whether to utilize AI __agents__ at this stage.

Note: Agents are operational components that for example may search/query, calculate, summarize, make API requests and return answers.

## UI Options and Iterative Development

Once we've established the base LLM model, we'll focus on finding a suitable UI (User Interface) to operate with. Initial options include:

1. **Open Web UI**: A straightforward approach for starters.
2. **Tappy**: Allows us to use LLMs in IDEs like VSCode.
3. Other...

## Iterative Approach

We'll start by using a simpler model, such as one with 7 billion parameters, and iterate our way forward:

1. **Initial Model**: Start with a simpler model and test its effectiveness.
2. **Iterate**: If the initial model works well, we can refine it further. If not, we'll switch to another, potentially better, model.

## Next Step
We iteratively test base models such as llama3, codellama etc. and see hot are doing, then proceed.