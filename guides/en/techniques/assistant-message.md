# Assistant Message

When outputting assistant messages as a result of an application, it is crucial for the user experience. If the latency of the assistant message is several seconds, the user experience is likely to be greatly compromised.

## Achieving Low Latency through Stream Reception

When using ChatGPT's API, it is recommended to receive responses through stream reception. This method involves receiving a response one character at a time, rather than waiting for the entire response to be completed before returning it.

For detailed implementation instructions, please refer to technical blogs such as the following:

Using the ChatGPT streaming API from Python | Simon Willison’s TILs

## Formats

For example, ChatGPT can output not only plain text but also various text formats, such as:

- JSON
- CSV
- XML
- YAML
- TOML
- LaTeX
- MathML
- Markdown
- HTML
- CSS
- SVG
- Various popular programming languages

Please ensure that the formats you want to handle in your application are supported and displayed correctly.

For example, if you want to display Markdown, please use a program that parses the assistant's message and converts it to HTML.
