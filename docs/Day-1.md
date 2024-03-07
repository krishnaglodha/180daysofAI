---
hide:
  - toc
---
# Day 1 - Getting Started with Pytorch

I've decided to start the journey with `Jumping in pool` directly approach. Might be a bad decision, but I tried it the other way few months back. I signed up for [Andrew NG's Machine learning](https://www.coursera.org/learn/machine-learning) course, but my interested dropped as I was getting lost in the theory part. Thus I decided to take another approach of learning as you go. 

I'm starting off with dedicating 1 Hr each day to watch 
<iframe width="560" height="315" src="https://www.youtube.com/embed/Z_ikDlimN6A?si=MxWjMlQL2jBzP6Ue" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Reason why I picked this up : 

- 😇 Comfort - I'm already proficient in #Python, which can save me time learning another programming language.
- 🤩Popularity - Despite hearing much about TensorFlow, recent surveys indicate many are migrating to PyTorch (source: https://lnkd.in/exEiq-sd). 
- 🏋🏻Trial and Error - Even if my decision is incorrect, I can always pivot and explore other options. 😛


-----

## Setup 
My setup is pretty clean to move forward, I might change as I go ahead, but for now what you need. 

- Good knowledge of python : If you don't know python, I'll request you to pause reading this right now, and take a python course. (Although If I were you, I'd not listed to this guy who wrote this page and still continue 😛, and take `Jumping in pool` approach for python as well. )

Here are few places I'd recommend you to start

<iframe width="560" height="315" src="https://www.youtube.com/embed/kqtD5dpn9C8?si=0DEcBj5XDR1Mg-tC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/rfscVS0vtbw?si=C62KQUogvpOOvJeR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/t8pPdKYpowI?si=Lw2j1F66gWxN2_wj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


- Hardware setup - You don't need fancy setup at all to get started. You can start writing AI code for free on websites like [Google Colab](https://colab.research.google.com/) , [Deepnote](https://deepnote.com/) or you can also setup things on your local, which is what I'm doing as well. I'm using a [conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html) to manage virtual env. 

Once the environment is created , I'm installing `notebook` so I can create python notebooks.

```bash
conda create -n ai pytorch

conda activate ai

pip install notebook

```

-----

## Creating first notebook

Activate environment and start writing python code.

```python
import torch
torch.__version__
```