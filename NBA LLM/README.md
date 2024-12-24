# NBA LLM Development

This was a fun, independent project that sparked my interest one day to delve into the realm of LLMs. 

I figured this was a way to showcase a few more skills I had not demonstrated as much, such as web scraping with BeautifulSoup, deep learning, LLM, and GPU-based training. Thankfully, my laptop has a RTX 4060 which is adequate enough for building a decent-enough LLM. That also brings in the fun and challenge to this project in figuring out how to train without overloading the memory in my GPU and still creating a smart model.

This project is still subject to updates, as I wanted to display the first iteration of my LLM and the reponses it gives to certain prompts based on NBA knowledge. I originally used a gpt2-large model as my base, but switched to Falcon 7b as I felt it was more suited for my hardware limitations.

It's safe to say it's not perfect by any means, but needs some work as far as staying on topic and avoiding extra rambling and giving concise answers. It did give the correct answer for the first question but then just added nonsense and repetition. The second question was close but it was wrong. The third question was wrong but historically was correct for a long time, a little context would help the model.
