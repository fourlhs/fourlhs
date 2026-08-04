### hey, i'm nikos 👋

ece student at ntua (athens), national-level karate competitor, and i build ai systems around one question: **can you actually trust what a model outputs?**

that thread runs through most of what's here. some of it is training models from scratch to see how they work from the inside. some of it is making models honest about when they're wrong. all of it i try to build carefully and report honestly.

**what i'm into:** interpretability, model reliability, and understanding models from the inside out. currently starting research at the [AILS lab](https://ails.ece.ntua.gr/) on interpretability and machine unlearning.

---

**a few things i've built:**

**[greek-scaling-laws](https://github.com/fourlhs/greek-scaling-laws)** — empirically derived neural scaling laws for a greek LM from scratch (tokenizer, model, training loop, power-law fits). reproduced kaplan's parameter exponent, then tracked down exactly why my data exponent was confounded. the write-up is as much about what *didn't* reproduce and why as what did.

**[nano-gpt-z](https://github.com/fourlhs/nano-gpt-z)** — a 17M-param GPT trained from scratch on 1B tokens, then fine-tuned into gen-z slang to study catastrophic forgetting. it forgot english faster than i ran out of tokens. [live demo](https://nikosfourlis.com/nano-gpt-z) · custom c++/wasm inference engine.

**[chandra-quant-deploy](https://github.com/fourlhs/chandra-quant-deploy)** — FP8/INT4 quantization + vLLM deployment pipeline for chandra OCR, with a CER/latency/VRAM benchmark suite. (from my work on greece's first sovereign LLM.)

**[micrograd-cpp](https://github.com/fourlhs/micrograd-cpp)** — scalar-valued autograd engine and neural net library from scratch in modern c++, no dependencies.

**[karate-zombie](https://nikosfourlis.com/karate-zombie)** — a browser game where a karateka fights zombies, built in an afternoon. global leaderboard, plays on mobile. because sometimes you just wanna build something fun.

---

**stack:** python · c++ · typescript · pytorch · cuda-adjacent (tensorrt, quantization, kv-cache, wasm)

📫 [nikosfourlis.com](https://nikosfourlis.com) · [linkedin](https://www.linkedin.com/in/nikos-fourlis/)
