# Morty's Thesis

**Title:** Towards a Computational Model of General Cognitive Control Using Artificial Intelligence, Experimental Psychology and Cognitive Neuroscience


## Setup

You need quarto and other required packages to build the thesis. You can install them using the following command:

```bash
mamba create -f environment.yml
mamba activate thesis
# install quarto (e.g., on macOS `brew install quarto`)
```

To render the thesis as PDF, run the following command:

```bash
quarto render --profile thesis
```

To render the defense slides, run the following command:

```bash
quarto render slides --profile slides
```
