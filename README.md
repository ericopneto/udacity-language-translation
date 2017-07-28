# Udacity Deep Laerning Foundations Nanodegree

## Project 4: Language Translation

In this project, i'll going to take a peek into the realm of neural network machine translation. You’ll be training a sequence to sequence model on a dataset of English and French sentences that can translate new sentences from English to French.

## Running using conda!

Run this in command line

**Step 1:** Create a new environment

```terminal
conda create --name language-translation python=3
```

**Step 2:** Use the new env

```terminal
source activate language-translation
```

**Step 3:** Install dependencies

```terminal
conda install -c conda-forge tensorflow=1.2.0
conda install numpy jupyter notebook
```

**Step 4:** Open the notebook to run it

```terminal
jupyter notebook dlnd_language_translation.ipynb
```

## Project structure

This folder contains files for Udacity Deep Laerning Foundations Nanodegree Project 4: Language Translation.

**dlnd_language_translation.ipynb** - Main project file.

**dlnd_language_translation.html** - Language translation results file.

**problem_unittests.py** - Unit tests provided by Udacity.

**helper.py** - Help functions provided by Udacity.

**data/simpsons/moes_tavern_lines.txt** - Some lines from a chapter of "The Simpsons" that will be used as input for the generation of a new scipt.
