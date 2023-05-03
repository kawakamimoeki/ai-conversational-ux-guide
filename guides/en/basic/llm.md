## Configuring LLM

LLM can produce different results for prompts by configuring several parameters.

**Temperature** - In short, the lower the temperature, the more deterministic the results in the sense that the highest probable next token is always picked. Increasing temperature could lead to more randomness, which encourages more diverse or creative outputs. You are essentially increasing the weights of the other possible tokens. For tasks such as fact-based Q&A or converting to machine-readable formats like SQL or code, you may want to use a lower temperature value to encourage more factual and concise responses. For creative tasks like brainstorming or design, it might be beneficial to increase the temperature value.

**Top_p** - Similarly, with top_p, a sampling technique with temperature called nucleus sampling, you can control how deterministic the model is at generating a response. If you are looking for exact and factual answers keep this low. If you are looking for more diverse responses, increase to a higher value.

The general recommendation is to alter one, not both.

Before starting with some basic examples, keep in mind that your results may vary depending on the version of LLM you use.
