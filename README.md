# Fine-Tuning-LLMs-with-QATCH
### What project is about:
This is a semester project at EURECOM Spring, conducted under the supervision of Professor Paolo Pappotti (EURECOM), Simone Papicchio PhD (EURECOM, Politecnico di Torino), and Professor Luca Cagliero (Politecnico di Torino).

It is focused on fine-tuning language models for question answering on proprietary data, using the [QATCH](https://github.com/spapicchio/QATCH) toolbox developed by Simone Papicchio, PhD, and directly builds up on this work.


The project investigates whether synthetic examples provided by the QATCH toolbox can improve the performance of these models and benchmarks them using the metrics provided by the toolbox. It also attempts to make these examples more complex and realistic (as they are template-based) by using LLMs such as GPT-4 to reformulate the questions.

### Useful ressources:
This project could be particularly useful to you as I couldn't find any open source comprehensive notebooks that detail how to fine-tune these models in a realistic setting using datasets that do not conform to the TSV format. In this project, we use the SPIDER dataset as a generic multi-dataset and include a data pipeline to convert it into TSV format.




Furthermore, the part of formulating the queries using LLMs is also very helpful because it can be used beyond just the reformulation of queries. We provide some functions and code snippets that will facilitate how you work with the OpenAI API.

### Refactor in the future:
The code is a little messy for now, but I will try to clean it up in the future.


Just remember that if you are working with the SPIDER dataset, the datasets are not included in the HuggingFace dataset library; you have to download them from the official website.


### Template of the report:
If you're curious about the template I used in the report, as I couldn't find such a template in Overleaf, you can take the TeX source for a research paper (on arXiv, look for one with TeX source that are available and choose the style that you like; I based mine on the [TAPAS](https://arxiv.org/abs/2004.02349) paper) and modify them to your desires. It's a bit difficult for the BibTeX file, as it isn't included, and you have to create a references .bib file and compile each time in three steps when you add a reference to it.
### Latex locally instead of overelaf
Also, working with LaTeX locally on VS Code is much better than Overleaf if you are not collaborating with anyone; it's much faster for compilation. However, make sure to push to Git or keep a version in the cloud in case your computer fails.

A tutorial on this I found useful:
[VsCode Mac/Windows Latex](https://mathjiajia.github.io/vscode-and-latex/)


### Acknowledgment
I would like to thank Paolo Pappotti (EURECOM), Simone Papicchio, PhD (EURECOM, Politecnico di Torino), and Professor Luca Cagliero (Politecnico di Torino) for their supervision on this project. A special thanks to Professor Paolo Pappotti for providing such a valuable learning opportunity and to Simone Papicchio, PhD, for helping me push through with regular meetings every week, offering valuable advice and insights.

