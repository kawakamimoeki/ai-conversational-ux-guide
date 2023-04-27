# Products Patterns

Language models are highly versatile. They can handle a wide range of language processing tasks, such as summarization, completion, brainstorming, and information extraction.

Moreover, with multimodal models, they can process not only language but also images and videos.

Given the versatile nature of language models, approaches to incorporating them into product design can take two directions: extending their generality even further, or enhancing their specificity through prompt control.

## Extending Language Models
In this pattern, the language model's output is converted into something other than language to add value to the product. Examples include SQL queries, graphical content design, and web browsing.

One important consideration for these applications is to avoid latency between prompts and actual results due to the language model's processing time, which is still relatively long compared to modern computing. This latency could lead to poor performance compared to operations performed with GUI or program inputs.

It is also important to increase the reproducibility of the conversion from prompt to output. Transformers have a parameter called "temperature" that controls output diversity. When the temperature is high, entering the same prompt could result in different results from previous runs, reducing user trust in the prompt. Therefore, a lower temperature setting is recommended.

## Specializing Language Models for Specific Purposes
In this pattern, the language model's prompt is controlled to specialize it for specific purposes, adding value to the product. For example, by instructing an assistant to behave like a specific character through a system prompt, a chatbot with character traits can be created.

Similarly, by providing information about a document, the user can receive information based on the document's knowledge.

One crucial consideration for these applications is prompt injection. This attack occurs when a user resets an assistant's instructions, causing the application to behave dangerously or abnormally. Addressing this attack is crucial to ensure that the application behaves as intended by its developers.
