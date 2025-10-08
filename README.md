#### Welcome to ascent minded!

Hi, I’m NB, and I thrive at the intersection of computation and biology. While I've primarily worked on datasets in a neuroscientific context, I'm excited to apply my skillset to new real-world research problems.

As a computational neuroscientist, I've modelled all kinds of data: 2-photon images ,EEG, spike trains and so on, and continue to use code (primarily in Python) to build models of how the brain learns, predicts and adapts. Many of those won't find their way here, but I hope to slowly open source more of my work. In neuro labs, I've also collated image datasets for cognition and biomedical research, although those are still locked away, awaiting publication.

Over the years, I've used machine learning, deep learning and multiple other modalities to explore my interests. Recently, for instance, I've explored transformers and LLMs, hoping to interpret their 'thinking' and gain insights into how we predict and process language.

Learning is rarely a linear process, as you can tell, and my many side projects will find their way here -- from automation to image analysis, game design to brain scans!

Thanks for dropping by,

~NB

### An index of repos:
0. [ascentminded.github.io](ascentminded.github.io) or [its repository](https://github.com/ascentminded/ascentminded.github.io) houses some of my unconventional projects, a website in the making.

1. [Stargazzers Allen Project](https://github.com/ascentminded/Stargazzers_Allen_project) is a repo from the 2021 Neuromatch course project. 
- My team Stargazzers (the typo was a joke that stuck) worked with calcium imaging data, predictive weather a mouse was looking at a familar or unfamiliar image from its brain activity.
- Primarily Machine learning tools, using SkLearn to run Logistic Regression, Random Forest, and a rudimentary neural net.

1b. As a sort of followup, I built [Predictive brain](https://github.com/ascentminded/pred-brain) 
- Pred-brain simulates the complex interplay between certain regions of the brain (VIP, SST, PY interneurons and Pyramidal neurons)
- I essentially built a literature backed, simple solution.
- Some math, but mostly intuitive pure python logic.

#### Dabbling in deep learning
2. [SmaLLM](https://github.com/ascentminded/SmaLLM) is an implementation of GPT2
- It is built as a Jupyter notebook (.ipynb), with plenty of comments, allowing new students to follow along and understand how transformers work.
- It helped me understand the seminal paper 'Attention is all you need', and transformers in general.

2b (dead). [CNN Analysis](https://github.com/ascentminded/CNN_Analysis) and dl-cellcount are currently a fairly dead repository, check back in later!
   - (I want to turn my experience with CNNs into a series of easy-to-understand jupyter notebooks, but I'm fairly short on time and some of the code is in uncertain IP. One day)

#### It also led to my experiments with agentic AI:
3. The [PhD vacancy agent](https://github.com/ascentminded/PhD-vacancy-agent) was something I built twice: once in n8n (a no-code, javascript based software) and once in pure python.
- The n8n workflow is still there for you to use, although it's imperfect. 
- The python code uses Python's Requests module to scrape vacancy aggregator websites, the Google Sheets API to store them, and an LLM (Gemini is what I used) to parse the job titles and pick out the ones that fit my prompt.

4. The [Cognitive companion](https://github.com/ascentminded/cognitive-companion) combined the Agentic AI framework with implementation -- I built a react.js website that allows users to interact with it.
- The website takes in user data, summarizes it, and provides socratic questions that lead to better understanding of the material.
- This way, I got to work with LLMs, web dev, and build a tool that does one task well.

5. The imaginatively named [LLaMa agent](https://github.com/ascentminded/llama-agent) was my support for the open source community:
- AI APIs like ChatGPT and Gemini provide an easy-to-use framework for building AI agents: They make formatted outputs, prompting, tool use, etc easy.
- LLaMa hasn't quite caught up, and its syntax can come off as a little clunky. There's also a lot less documentation for it.
- As such, I built a repository that people can use as a handy reference when building their first LLaMa agent in python.

#### Just for fun.
6. [Canvas.py](https://github.com/ascentminded/Canvas) is just for fun.
- Game engines like Unity and Godot makes scaling up a game a lot easier, but sometimes you want to build very simple games -- pygame comes in there.
- This specific game is a lightweight python file, requiring one image for your character, and one image (a 'canvas') for a large background
- Much like in xkcd's Hoverboard game, this setup is meant for artists to let their readers explore the worlds they create in an organic way. Try it out :)!

7. For the fluroescent microscope users, I also built some [ImageJ/Fiji macros](https://github.com/ascentminded/Fluorescent_Image_Macro), which may fit your use case:
- Give it a shot :)
