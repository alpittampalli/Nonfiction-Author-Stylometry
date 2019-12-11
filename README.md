# What Makes Some Writers' Voices So Distinct?: a Stylometric Classification Project

The holy grail for any writer is to have a voice so distinct that readers could recognize it in a given text without knowing who wrote it. But what makes a voice that distinct? To answer that question, I proceeded along two steps.

Build a model that could, first, quantitatively identify modern authors who have a distinct voice. I'll do this by gathering the books of several different authors, training a classification model with their labeled writing samples, and then seeing how well the model can attribute unlabeled writing samples back to those authors. The more acccurate the model it is for a given author's texts, the more distinct the voice, we'll presume.
Inspect the model to learn what makes those authors' voices so recognizable. I'll use feature importance scores, and then using EDA to guide this exploratory analysis.
