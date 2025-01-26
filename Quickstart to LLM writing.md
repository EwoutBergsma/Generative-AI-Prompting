# Quickstart to LLM writing

*The process of writing scientific documents has long been both an art and a science, demanding clarity, rigor, and precision. Whether drafting research papers, grant proposals, or review articles, scientists must navigate a challenging landscape of technical complexity, structured formats, and the need to effectively communicate with diverse audiences. The advent of large language models (LLMs), such as ChatGPT, offers a transformative tool for assisting in this intricate process.*

Do you see that? Notice anything? Yes, indeed—that came straight out of ChatGPT. Do you enjoy reading it? I certainly do not. I am writing this short document to help students improve their use of LLMs. I am by no means a world-leading expert on using LLMs like ChatGPT. However, I have had to read far too many documents that sound like the paragraph above, and that makes me sad. On the one hand, it saddens me because I have to read these colourful, verbose, yet empty texts. On the other hand, I know that with just a few extra steps, they could be so much better. In other words, this document aims to kick-start your LLM-powered writing!

The first mistake that is easily made is giving the LLM a simple instruction, then copy-pasting the output and calling it a day. That’s bad. As a rule of thumb, the first output is probably garbage. Yes, it may look nice at face value, but after some experience (which many people have by now, especially teachers), you will quickly notice the colourful emptiness of the generated text. My personal favourite way of tackling this is what I call the Backspace-Ban method. I manually write a piece of text as quickly as possible, almost completely banning the use of my backspace key. Sentences will be broken, and the language will be poor. Especially as a non-native speaker, this is fun but challenging. Then, I put that text into ChatGPT and ask it to improve or correct my English. Try it, and notice the difference in the output—it will be a huge improvement.

Alternatively, there is a method I like to call the Keypoint-Kickstart. Instead of providing a draft text, you provide only the key talking points. This can prevent the generated text from feeling hollow. Initially, this approach is quicker than the Backspace-Ban, but it may require more back and forth with the LLM, and it does less to train your own writing skills. Feel free to experiment with which method works best for you in different scenarios.

If you have followed my suggestions so far, you may have noticed that the generated text has improved – but it’s still not quite there. The single most important factor in achieving LLM success is the prompt. A prompt is the task or instruction you provide to the LLM to perform. There’s a lot to learn about prompting, and while we won’t cover everything here, I will provide some pointers that can have a significant impact. Additionally, at the end of this document, you’ll find sources for more advanced prompting techniques. Let’s start with an example. Please note that I continuously update and adjust my personal library of prompts, and I urge you to do the same:

```
Persona: You are an expert teacher in the fields of scientific writing and research skills. Please act as my writing coach.

Output: Please do not use the following terms: key, crucial, foster, seamless, essential, delve into, vibrant, realm, embark, in the world of, game changer, labyrinth, enigma, a testament to.

Task: Help me refine a piece of writing. Stay close to the original text while focusing on enhancing the language and structure for clarity and professionalism. Please assist me by improving the following text, merely respond with the refined text, do not state anything else:
<insert text>
```

First, I provide it with a persona, so the LLM knows who to respond as. This helps it strike the right tone. It's quite logical; you also speak and behave differently with a toddler than with an adult. The only difference is that you understand this context without needing to be explicitly told, whereas an LLM does not. After that, I ban a few terms. An LLM—ChatGPT, at least—tends to write in extremes, and some of these banned words help prevent that. (Perhaps in a future version, we could also instruct the LLM not to write in extremes, but I haven’t yet found an proper way to do this.) Some of the other banned words are simply overused by the LLM—I’m not sure why.

Then there is the task. Obviously, this depends heavily on what you are currently trying to accomplish. I ask it to stay close to the original text because otherwise, it may sometimes alter the content (which is especially frustrating when it incorrectly changes technical terms) instead of improving the provided text. Additionally, by asking it to simply respond with the refined text, copying and pasting becomes easier. Tasks that I frequently request during writing include:

- Improve text
    - As shown in the example
- Adjust text
    - Give the LLM some more freedom to make changes if you so desire
- Generate text from keypoints
    - Make sure to also provide it what it is writing, e.g. an introduction of a research proposal
- Give feedback on the provided text
    - Be critical on the feedback that it may give.
- Summarize a large(r) piece of text

You may have noticed that I used the terms LLM and ChatGPT almost interchangeably. That’s because ChatGPT is my go-to writing assistance. From my experience it is currently the strongest language generator out there. However, it is important to mention that NotebookLM is quite useful too. That tool requires you to provide sources (e.g. documents) and can then answer questions about these sources. From my experience it does a better job at staying close to the provided sources (i.e. fewer hallucinations), and also links to where it got the information from, meaning that you can easily double-check its output.

To summarize, using LLMs like ChatGPT for writing can be incredibly useful, but it takes more than just a quick copy-paste to get good results. Try experimenting with methods like the Backspace-Ban or Keypoint-Kickstart to avoid generating colourful verbose yet hollow texts. Spend time crafting a solid prompt and adjust as needed—it makes all the difference. While I mostly use ChatGPT, NotebookLM can be helpful too, especially when working with specific sources. Play around, find what works for you, and you’ll see how much better your LLM-powered writing can get.

Elsewhere in this repository you will find example prompts, as well as some nice references. Check them out!