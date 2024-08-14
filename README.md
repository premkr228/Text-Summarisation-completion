# Text-Summarisation-completion
This program utilizes OpenAI's GPT-2 language model to perform two main tasks: Text summarization and Text completion.

Text Summarization: The program takes a long input text and generates a concise summary. It uses a tokenizer to encode the input and then employs the GPT-2 model to create a summary that captures the key points while maintaining coherence. The output is a summarized version of the original text, suitable for quick understanding.

Text Completion: The program also provides text completion, where users input a sentence or phrase, and the GPT-2 model generates possible continuations. The model generates multiple sequences of text that continue the initial input in a coherent and contextually relevant manner.

The program uses the Gradio library to create a user interface, allowing users to easily input text and view the generated summaries or completions. The expected output includes concise summaries or multiple text completions, depending on the user's input.
