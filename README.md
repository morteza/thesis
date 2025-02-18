# Morty's Thesis

***Title:** Towards a Computational Model of General Cognitive Control Using Artificial Intelligence, Experimental Psychology and Cognitive Neuroscience* ([pdf](https://github.com/morteza/thesis/blob/main/PhD_Dissertation_Morteza_Ansarinia.pdf) &bull; [slides](https://github.com/morteza/thesis/blob/main/slides/annotated_defense_slides.pdf) &bull; [a brief video overview](https://www.youtube.com/watch?v=S6zIn1HjJfk&t=3180s))


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
