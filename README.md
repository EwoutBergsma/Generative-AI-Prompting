In this repository, you will find quickstart guides, detailed information, and references designed to assist with generative AI prompting (e.g., LLMs such as ChatGPT). Below is a compilation of premade prompts.

# Scientific Writing

**Refine**

```
Help me refine the text delimited by angle brackets. Stay close to the original text while focusing on enhancing the language for clarity, professionalism and conciseness. Ensure the refined text adheres to the IEEE style guide and is appropriate for an advanced reader. Only respond with the refined text followed by a list of changes. Do not add any titles or extra text, such as for example "list of changes". Communicate a change with the structure: "original text" → "changed text".

Please do not use the following terms: key, crucial, foster, seamless, essential, delve into, vibrant, realm, embark, in the world of, game changer, labyrinth, enigma, a testament to.

Reply in English. Do not use canvas, do not search the web.

<REPLACEBUTKEEPANGLEDBRACKETS>
```

**Correct**
```
Correct the text delimited by angle brackets for grammar, spelling and punctuation. Do not make any other changes to the text. Ensure the refined text adheres to the IEEE style guide and is appropriate for an advanced reader. Only respond with the refined text followed by a list of changes. Do not add any titles or extra text, such as for example "list of changes". Communicate a change with the structure: "original text" → "changed text".

Please do not use the following terms: key, crucial, foster, seamless, essential, delve into, vibrant, realm, embark, in the world of, game changer, labyrinth, enigma, a testament to.

Reply in English. Do not use canvas, do not search the web.

<REPLACEBUTKEEPANGLEDBRACKETS>
```

**Feedback**
```
You are an expert teacher in scientific writing and research skills. Please act as my writing coach and provide constructive feedback on the text delimited by angle brackets. Keep each piece of feedback brief and actionable. Provide your feedback in the form of a concise, itemized list, focusing on: overall structure, sentence structure, clarity, flow and the IEEE style guide.

Do not use canvas, and do not search the web.

Reply in English. Do not use canvas, do not search the web.

<REPLACEBUTKEEPANGLEDBRACKETS>
```


# Sources

https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/

https://www.deeplearning.ai/short-courses/building-systems-with-chatgpt/

This browser extension used to be nice, but is has been buggy for quite some time:
https://chromewebstore.google.com/detail/chatgpt-prompt-saver/oicnaioifndihkfinnmccjdpcepmokcn?pli=1
