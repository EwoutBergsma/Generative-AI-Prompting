In this repository, you will find quickstart guides, detailed information, and references designed to assist with generative AI prompting (e.g., LLMs such as ChatGPT). Below is a compilation of premade prompts.

# Scientific Writing

**Refine**

```
Help me refine the text delimited by angle brackets. Stay close to the original text while focusing on enhancing the language for clarity, professionalism and conciseness. Ensure the refined text adheres to the IEEE style guide and is appropriate for an advanced reader. Only respond with the refined text followed by a list of changes. Do not add any titles or extra text, such as for example "list of changes". Communicate a change with the structure: "original text" → "changed text".

Please do not use the following terms: key, crucial, foster, seamless, essential, delve into, vibrant, realm, embark, in the world of, game changer, labyrinth, enigma, a testament to, encompasses.

Reply in English. Do not use canvas, do not search the web.

<REPLACEBUTKEEPANGLEDBRACKETS>
```

**Correct**
```
Correct the text delimited by angle brackets for grammar, spelling and punctuation. Do not make any other changes to the text. Ensure the refined text adheres to the IEEE style guide and is appropriate for an advanced reader. Only respond with the refined text followed by a list of changes. Do not add any titles or extra text, such as for example "list of changes". Communicate a change with the structure: "original text" → "changed text".

Please do not use the following terms: key, crucial, foster, seamless, essential, delve into, vibrant, realm, embark, in the world of, game changer, labyrinth, enigma, a testament to, encompasses.

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

**Transformative - Based on other work**
```
You are an expert writing assistant specializing in scientific writing and research communication. Your expertise includes maintaining precision, adhering to academic conventions, and ensuring clarity and readability. I will provide a piece of text delimited by angle brackets. Use this text as your foundation, mirroring its writing style, tone, and level of detail. Delimited by square brackets will be instructions specifying what should be written or modified. Stay as close to the original content as possible while addressing the provided instructions. Unless explicitly instructed, prioritize clarity, coherence, and conciseness, even if minor deviations from the original style are necessary.

Please do not use the following terms: key, crucial, foster, seamless, essential, delve into, vibrant, realm, embark, in the world of, game changer, labyrinth, enigma, a testament to, encompasses.

<REPLACEBYBASISTEXT>

[EXPLAINWHATNEEDSTOBEGENERATED]

```

# Prompt Engineering
```
Please help me refine my generative AI prompt. Delimited by angle brackets I will provide a prompt that I curently have. Only respond with the refined text followed by a list of changes.

<REPLACEBUTKEEPANGLEDBRACKETS>
```


# Sources

https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/

https://www.deeplearning.ai/short-courses/building-systems-with-chatgpt/

This browser extension used to be nice, but is has been buggy for quite some time:
https://chromewebstore.google.com/detail/chatgpt-prompt-saver/oicnaioifndihkfinnmccjdpcepmokcn?pli=1
