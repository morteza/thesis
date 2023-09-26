# Morty's Thesis

**Title:** Towards a Computational Model of General Cognitive Control Using Artificial Intelligence, Experimental Psychology and Cognitive Neuroscience


## Setup

You need quarto and other required packages to build the thesis. You can install them using the following commands:

```bash
mamba env create -f environment.yml
mamba activate thesis
# quarto on conda raises error (missing tlmgr), so install it manually.
# manually install quarto and tinytex (e.g., `brew install quarto` on macOS, and then `quarto install tinytex`).
```

## Rendering Thesis

To render the thesis as PDF, run the following command:

```bash
quarto render --profile thesis
```

The output PDF will be in `_book/` folder.


## Rendering Slides

To render the defense slides, run the following command:

```bash
quarto render slides --profile slides
```

> [!NOTE]
> See the [annotated_defense_slides.pdf](https://github.com/morteza/thesis/blob/main/slides/annotated_defense_slides.pdf) file for the final slides and speaker notes.
