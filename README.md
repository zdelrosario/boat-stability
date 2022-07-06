# boat-stability

2d boat hull statical stability analysis in python

Uses a simple discretization scheme to evaluate the integrals needed to perform a [statical stability](https://www.usna.edu/NAOE/_files/documents/Courses/EN455/AY20_Notes/EN455CourseNotesAY20_Chapter2.pdf) analysis of a boat hull cross-section.

Two notebooks execute an exploratory model analysis (EMA) of the boat stability model:

- [`00-generate-data.ipynb`](https://github.com/zdelrosario/boat-stability/blob/main/00-generate-data.ipynb) : Run initially to generate stability data for a sample of boat hulls.
- [`01-ema-example.ipynb`](https://github.com/zdelrosario/boat-stability/blob/main/01-ema-example.ipynb) : Loads the sample generated above and carries out an EMA of the boat model.
