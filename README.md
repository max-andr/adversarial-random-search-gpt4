# Adversarial Attacks on GPT-4 via Simple Random Search

**📢 Update on 28 April 2024:**
*This short write-up is superseded by our subsequent work [Jailbreaking Leading Safety-Aligned LLMs with Simple Adaptive Attacks
](https://arxiv.org/abs/2404.02151) which uses random search to jailbreak many of the leading safety-aligned LLMs, including GPT-4. See the code https://github.com/tml-epfl/llm-adaptive-attacks for the improved implementation of random search.*


## Conversations
**Standard conversation #1**: [https://platform.openai.com/playground/p/gEEPak6gtzI4HiMnoKhksBc6?mode=chat](https://platform.openai.com/playground/p/gEEPak6gtzI4HiMnoKhksBc6?mode=chat)
<p align="center"><img src="images/conv1_standard.png" width="900" /></p>

**Adversarial conversation #1**: [https://platform.openai.com/playground/p/0IU3UOP70KoviepEIjXGBvUU?mode=chat](https://platform.openai.com/playground/p/0IU3UOP70KoviepEIjXGBvUU?mode=chat)
<p align="center"><img src="images/conv1_adv.png" width="900" /></p>

**Standard conversation #2**: [https://platform.openai.com/playground/p/gTciUFzOZiQaYl65G16frCxT?mode=chat](https://platform.openai.com/playground/p/gTciUFzOZiQaYl65G16frCxT?mode=chat)
<p align="center"><img src="images/conv2_standard.png" width="900" /></p>

**Adversarial conversation #2**: [https://platform.openai.com/playground/p/szF1Vs2IwW5Hr9xUFM1DL8fb?mode=chat](https://platform.openai.com/playground/p/szF1Vs2IwW5Hr9xUFM1DL8fb?mode=chat)
<p align="center"><img src="images/conv2_adv.png" width="900" /></p>


## Optimization with random search for both conversations
<p align="center"><img src="images/opt_conv1.png" width="400" /><img src="images/opt_conv2.png" width="400" /></p>


## How to run the notebook
Provide your `OPENAI_API_KEY` as an environment variable following the instructions [here](https://platform.openai.com/docs/quickstart?context=python). Then you are good to go!

